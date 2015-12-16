#### Test 50650278e989a4f_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
E/Zygote  ( 7329): MountEmulatedStorage()
E/Zygote  ( 7329): v2
--------- beginning of system
E/Watchdog(  869): !@Sync 3
D/PackageManager(  869): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/libpersona( 7329): KNOX_SDCARD checking this for 10057
I/libpersona( 7329): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7329 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7329): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7329): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7329): TimaSignature is unavailable
D/ActivityThread( 7329): Added TimaKeyStore provider
D/ResourcesManager( 7329): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7329): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7329): onReceive() it will make start service
D/Compatibility( 7329): onHandleIntent()
D/Compatibility( 7329): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
D/Compatibility( 7329): found: 2
I/UpdateIcingCorporaServi( 1564): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7329): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7329): skipping ResolveInfo{347741e6 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7329): considering ResolveInfo{abf5327 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7329): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7329): enabling receiver ResolveInfo{15f679d4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 7350): MountEmulatedStorage()
I/libpersona( 7350): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7350): v2
I/libpersona( 7350): KNOX_SDCARD not a persona
E/SMD     (  285): DCD ON
I/ActivityManager(  869): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7350 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/Compatibility( 7329): enabling receiver ResolveInfo{108a77d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,I/SELinux ( 7350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7350): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 7329): enabling receiver ResolveInfo{1b659672 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7329): enabling receiver ResolveInfo{2c43fac3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7329): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 7350): TimaSignature is unavailable
D/ActivityThread( 7350): Added TimaKeyStore provider
I/ActivityManager(  869): Killing 5660:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
D/ResourcesManager( 1564): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ResourcesManager( 7350): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
I/UpdateIcingCorporaServi( 1564): UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
W/libprocessgroup(  869): failed to open /acct/uid_10039/pid_5660/cgroup.procs: No such file or directory
W/ContextImpl( 7350): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7368): MountEmulatedStorage()
E/Zygote  ( 7368): v2
I/libpersona( 7368): KNOX_SDCARD checking this for 10085
I/libpersona( 7368): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=7368 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  318): Explicit concurrent mark sweep GC freed 8739(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 12.891ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.091ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 8.082ms
I/SELinux ( 7368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  869): Killing 6024:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
I/SELinux ( 7368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7368): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7368): TimaSignature is unavailable
D/ActivityThread( 7368): Added TimaKeyStore provider
D/ResourcesManager( 7368): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 7368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
D/PushModule( 7368): [PushClientApplication] (main) PushClientApplication.onCreate()
I/PushModule( 7368): [PushClientApplication] (main) PushModule version: 0.9.01.12
D/PushModule( 7368): [PushClientApplication] (main) Discovered public push client. disable in app push client.
D/AndroidRuntime( 7365): 
D/AndroidRuntime( 7365): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7365): CheckJNI is OFF
D/AndroidRuntime( 7365): setted country_code = Poland
D/AndroidRuntime( 7365): setted countryiso_code = PL
D/AndroidRuntime( 7365): setted sales_code = XEO
D/AndroidRuntime( 7365): readGMSProperty: start
D/AndroidRuntime( 7365): readGMSProperty: already setted!!
D/AndroidRuntime( 7365): readGMSProperty: end
D/AndroidRuntime( 7365): addProductProperty: start
D/ChatON  ( 7368): [1][isApplicationInstalled] com.android.mms was installed
W/ContextImpl( 7368): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
W/ActivityManager(  869): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
W/libprocessgroup(  869): failed to open /acct/uid_10167/pid_6024/cgroup.procs: No such file or directory
D/ChatON  ( 7368): [1][a] ChatONV isn't installed.
D/ChatON  ( 7368): [1][a] ChatONVPlugIn.isAvailable()
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  869): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7394 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  869): Killing 6264:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
E/Zygote  ( 7394): MountEmulatedStorage()
I/libpersona( 7394): KNOX_SDCARD checking this for 10097
E/Zygote  ( 7394): v2
I/libpersona( 7394): KNOX_SDCARD not a persona
I/SELinux ( 7394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7394): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/AffinityControl( 7365): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 7394): TimaSignature is unavailable
D/ActivityThread( 7394): Added TimaKeyStore provider
D/AndroidRuntime( 7365): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  869): failed to open /acct/uid_10004/pid_6264/cgroup.procs: No such file or directory
D/ResourcesManager( 7394): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
E/PersonaManagerService(  869): inState():  stateMachine is null !!
V/ApplicationPolicy(  869): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  869): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  869): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  869): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 869  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  869): mDVFSHelper.acquire()
D/FocusedStackFrame(  869): Set to : 0
D/Launcher.HomeView( 1474): onPause
D/AndroidRuntime( 7365): Shutting down VM
D/Launcher( 1474): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/Zygote  ( 7416): MountEmulatedStorage()
E/Zygote  ( 7416): v2
I/libpersona( 7416): KNOX_SDCARD checking this for 10356
I/libpersona( 7416): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7416 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7416): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
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
D/StatusBarManagerService(  869): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/MicrophoneInputStream( 1564): mic_close gfk@1d1cd1ee
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/TimaKeyStoreProvider( 7416): TimaSignature is unavailable
D/ActivityThread( 7416): Added TimaKeyStore provider
V/AudioPolicyManager(  292): stopInput() input 29
V/AudioPolicyManager(  292): releaseInput() 29
V/AudioPolicyManager(  292): closeInput(29)
I/HotwordRecognitionRnr( 1564): Hotword detection finished
I/HotwordRecognitionRnr( 1564): Stopping hotword detection.
V/audio_hw_primary(  292): in_standby: enter
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  869): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  869): Display changed displayId=0
D/Launcher.HomeView( 1474): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2075): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2075): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2075): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2075): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetView( 1474): destroyHardwareResources():349554730
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2075): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
V/audio_hw_primary(  292): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  292): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  292): disable_audio_route: reset mixer path: audio-record
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): disable_audio_route: exit
V/audio_hw_primary(  292): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: DEC2 Volume
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): Setting mixer control: SLIM TX7 MUX, value: 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/audio_route(  292): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  292): Setting mixer control: value: 0
D/StatusBarManagerService(  869): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  292): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): stop_input_stream: exit: status(0)
V/audio_hw_primary(  292): in_standby: exit:  status(0)
V/audio_hw_primary(  292): adev_close_input_stream
V/audio_hw_primary(  292): in_standby: enter
V/audio_hw_primary(  292): in_standby: exit:  status(0)
E/audio_hw_primary(  292): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  292): releaseInput() exit
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/accuweather( 2075): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2075): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/Launcher( 1474): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/SurfaceWidgetView( 1474): destroyHardwareResources():349554730
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7416): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/DocsApplication( 7394): Installing DEX configuration.
D/DexInstaller( 7394): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
I/PackageInfoHelper( 7394): Provided clientMode=RELEASE, packageInfo=PackageInfo{1c38c841 com.google.android.apps.docs}
D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/TAG     ( 7394): onCreate()
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/CrossAppStateProvider( 7394): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/WebViewFactory( 7416): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7416): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/LibraryLoader( 7416): Loading: webviewchromium
,I/LibraryLoader( 7416): Time to load native libraries: 2 ms (timestamps 4220-4222)
,I/LibraryLoader( 7416): Expected native library version number "",actual native library version number ""
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/WebViewChromiumFactoryProvider( 7416): Binding Chromium to main looper Looper (main, tid 1) {1b659672}
,I/LibraryLoader( 7416): Expected native library version number "",actual native library version number ""
I/chromium( 7416): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7416): Initializing chromium process, renderers=0
,W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/chromium( 7416): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7416): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7416): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Adreno-EGL( 7416): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7416): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7416): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7416): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7416): Remote Branch: 
I/Adreno-EGL( 7416): Local Patches: 
I/Adreno-EGL( 7416): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,W/chromium( 7416): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7416): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7416): onDetachedFromWindow called when already detached. Ignoring
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/SystemWebViewEngine( 7416): CordovaWebView is running on device made by: samsung
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7416): Attempt to remove local handle scope entry from IRT, ignoring
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
,D/Activity( 7416): performCreate Call secproduct feature valuefalse
D/Activity( 7416): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7416): Render dirty regions requested: true
,D/ActivityManager(  869): post active user change for 0
D/KnoxTimeoutHandler(  869): postActiveUserChange for user 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KnoxTimeoutHandler(  869): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/OpenGLRenderer( 7416): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/OpenGLRenderer( 7416): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7416): Enabling debug mode 0
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/InputMethodManagerService(  869): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/ActivityManager(  869): Displayed com.test.thalitest/.MainActivity: +557ms
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Timeline( 7416): Timeline: Activity_idle id: android.os.BinderProxy@14f769ed time:104543
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SurfaceFlinger(  257): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  257): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
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
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/JsMessageQueue( 7416): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/chromium( 7416): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7416): 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/jxcore_app_log( 7416): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360705408
,D/JX-Cordova( 7416): jxcore cordova android initializing
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SurfaceFlinger(  257): id=14 Removed Starting com.test.thalitest (7/8)
,I/SurfaceFlinger(  257): id=14 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
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
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/CustomFrequencyManagerService(  869): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 869  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  869): mDVFSHelper.release()
,I/Timeline(  869): Timeline: Activity_windows_visible id: ActivityRecord{22e6e7d5 u0 com.test.thalitest/.MainActivity t3} time:104845
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/CustomFrequencyManagerService(  869): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 869  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,V/AlarmManager(  869): waitForAlarm result :4
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  869): Plugged
I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CustomFrequencyManagerService(  869): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 869  tag : ACTIVITY_RESUME_BOOSTER@10
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 7394): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 7478): MountEmulatedStorage()
,E/Zygote  ( 7478): v2
I/libpersona( 7478): KNOX_SDCARD checking this for 10098
I/libpersona( 7478): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7478 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,I/SELinux ( 7478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7478): TimaSignature is unavailable
,D/ActivityThread( 7478): Added TimaKeyStore provider
,D/ResourcesManager( 7478): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 7478): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 7478): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7478): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7478): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7498): MountEmulatedStorage()
,E/Zygote  ( 7498): v2
I/libpersona( 7498): KNOX_SDCARD checking this for 10032
I/libpersona( 7498): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7498 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
,I/SELinux ( 7498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7498): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7498): TimaSignature is unavailable
,D/ActivityThread( 7498): Added TimaKeyStore provider
,D/ResourcesManager( 7498): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7498): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/System.out( 7498): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 7498): Inside WakeupProvider
,E/DatabaseUtils( 7498): Writing exception to parcel
E/DatabaseUtils( 7498): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7498): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7498): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7498): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7498): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7498): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7498): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7498): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7498): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7498): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7498): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7478): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/GAV2    ( 7394): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  869): Killing 6328:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/VlingoApplication( 7498): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
,W/System.err( 7478): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7478): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7478): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7478): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7478): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7478): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7478): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7478): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7478): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7478): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7478): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7478): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7478): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7478): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7478): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7478): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7478): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7478): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7478): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7478): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7478): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7478): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7478): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7478): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7478): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7478): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7478): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7478): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7478): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7478): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 1 -> 1
I/VlingoAndroidCore( 7498): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
E/[CarMode]( 7478): [DLApplication]-Init Called!:false
E/[CarMode]( 7478): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 7478): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7478): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7478): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7478): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7478): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7478): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7478): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7478): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7478): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7478): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7478): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7478): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7478): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7478): ### com.android.internal.os.ZygoteInit::main(1194)
,I/MessageDataHandler( 7478): initialize
,D/[CarModeFW]( 7478): CDH-initiazlieCaches : before sync
,D/[CarModeFW]( 7478): CDH-initiazlieCaches : after sync
W/libprocessgroup(  869): failed to open /acct/uid_10043/pid_6328/cgroup.procs: No such file or directory
,D/[CarModeFW]( 7478): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7478): DrivingManager-initialize...
,D/[CarModeFW]( 7478): CDH-ContactDataHandler initiazlieCaches time : 15
D/[CarModeFW]( 7478): CDH-initiazlieCaches : end sync
,I/SensorService(  869): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  869): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  869): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/VlingoApplication( 7498): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 7498): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 7478): Need to enable context aware info
,V/MediaPlayer-JNI( 7478): native_setup
V/MediaPlayer( 7478): constructor
,V/MediaPlayer( 7478): setListener
,E/MediaPlayer-JNI( 7478): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 7478): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 7478): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 7478): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/PowerManagerService(  869): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  869): Nap time (uid 1000)...
I/PowerManagerService(  869): !@[ps] Screen__Off(2) : 
D/InputManager-JNI(  869): setDeviceInteractive: 0
I/PowerManagerService(  869): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  869): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  869): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  869): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  869): handleSandman : startDream()
E/PowerManagerService(  869): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  869): Sleeping (uid 1000)...
D/PowerManagerService(  869): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  869): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  869): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  257): id=16 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  869): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  869): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  869): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  869): 	.unregisterCallback : 1, client=
D/SContextService(  869): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@36831052, Service = Auto Rotation, used = 1
,W/CAE     (  869): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  869): stop(ContextProvider.java:149)
,V/CAE     (  869): clear(AutoRotationRunner.java:182)
V/CAE     (  869): disable(AutoRotationRunner.java:171)
,I/CAE     (  869): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  869): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  300): sendContextData: -78, 7, 0, 0
,D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1450233118323
,D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1450233118330
,D/[CarModeFW]( 7478): CDH-buildContactCacheWireFrame : cur len =0
,D/CAE     (  869): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,D/[CarModeFW]( 7478): RecommendHandler-selection = type = '3'
I/CAE     (  869): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7534): MountEmulatedStorage()
I/libpersona( 7534): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7534): v2
I/libpersona( 7534): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7534 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1450233118352
,D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1450233118354
,D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1450233118356
,D/[CarMode]( 7478): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1450233118357
,I/[CarMode]( 7478): [LogNotNull]-Package name is: com.google.android.apps.maps
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,I/SELinux ( 7534): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CAE     (  869): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  869): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
I/SELinux ( 7534): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/CAE     (  869): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  869): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  869): removeSContextService() : service = Auto Rotation
D/SContextService(  869): ===== SContext Service List =====
D/SContextManager(  869):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1573a841, service=Auto Rotation
E/SELinux ( 7534): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1181): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): timeout : 5000
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SQLiteSecureOpenHelper( 3505): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3505): getDatabaseLocked(b,b,pwd)...
,D/LightsService(  869): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 869) 
,D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1181): handleNotifyScreenOff
,D/LightsService(  869): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  869): [SvcLED]  onSensorChanged::light value = 0
,D/DisplayPowerController(  869): ColorFade: onAnimationStart
D/DisplayPowerController(  869): getFinalBrightness : 8 -> 0
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 8 -> 0
D/[CarModeFW]( 7478): CDH-buildContactCacheWireFrame : cur len =0
,D/SensorManager(  869): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  869): turn on LED for fully charged
,D/SensorManager(  869): unregisterListener ::   
D/lights  (  869): led_pattern : 5 +
,D/DisplayPowerController(  869): getFinalBrightness : 8 -> 0
,D/TP/SmsProvider( 1468): query,matched:2, calling pid = 7478
,E/[CarMode]( 7478): [DLApplication]-Init End!:true
,D/TP/SmsProvider( 1468): query,matched:2, calling pid = 7478
,D/lights  (  869): led_pattern : 5 -
D/lights  (  869): lcd : 0 +
,D/LightsService(  869): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TP/SmsProvider( 1468): match 2:Elapsed time : 3.353 ms
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1468): match 2:Elapsed time : 7.076 ms
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7534): TimaSignature is unavailable
,D/ActivityThread( 7534): Added TimaKeyStore provider
,D/lights  (  869): lcd : 0 -
,E/Zygote  ( 7549): MountEmulatedStorage()
E/Zygote  ( 7549): v2
I/libpersona( 7549): KNOX_SDCARD checking this for 10003
I/libpersona( 7549): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7549 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/CAE     (  869): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  869): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  869): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  869): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  300): sendContextData: -76, 13, -46, 0
I/SELinux ( 7549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CAE     (  869): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 2, 31, 58,
,D/SensorHubManager(  869): SendSensorHubData: send data = -63, 14, 2, 31, 58
D/Sensorhubs(  300): sendContextData: -63, 14, 2, 31, 58
,E/LightSensor(  869): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  869): mCallbacks.updateBrightness()
D/DisplayPowerController(  869): getFinalBrightness : 8 -> 0
,D/MessageDataHandler( 7478):  getInboxList smsCursor : 212
,D/ResourcesManager( 7534): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/[CarMode]( 7478): [DLApplication]-GooglePlayServices SUCCESS.
,D/TimaKeyStoreProvider( 7549): TimaSignature is unavailable
,D/ActivityThread( 7549): Added TimaKeyStore provider
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/[CarMode]( 7478): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 7478): Intent : android.intent.action.PACKAGE_ADDEDWed Dec 16 03:31:58 GMT+01:00 2015
,E/MotionRecognitionService(  869):  handler : SCREEN_OFF end 
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,D/[CarModeFW]( 7478): CDH-buildContactCacheWireFrame : cur len =0
,E/Zygote  ( 7564): MountEmulatedStorage()
I/libpersona( 7564): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7564): v2
I/libpersona( 7564): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7564 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/NotificationService(  869): ACTION_SCREEN_OFF
,D/WifiStateMachine(  869): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  869): handleScreenStateChanged Exit: false
,D/LightsService(  869): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 869) 
,D/LightsService(  869): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,E/WifiStateMachine(  869): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,D/LightsService(  869): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine(  869): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  869): do suspend true
,D/SensorManager(  869): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  869): unregisterListener ::   
,D/LightsService(  869): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/SELinux ( 7564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7564): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsProvider( 1468): Query uri=content://mms/inbox, match=2, calling pid = 7478
,I/ActivityManager(  869): Killing 5982:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,D/audio_hw_primary(  292): adev_set_parameters: enter: screen_state=off
,V/voice   (  292): voice_set_parameters: enter: screen_state=off
D/TP/MmsProvider( 1468): Query uri=content://mms, match=0, calling pid = 7478
V/voice   (  292): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  292): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
,D/DisplayPowerState(  869): !@ ColorFade entry
,D/DisplayPowerController(  869): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  869): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  869): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  869): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  869): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController(  869): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  869): unregisterListener ::   
,E/Sensors (  869): Acc old sensor_state 1, new sensor_state : 0 en : 0
,I/SecExternalDisplayIntents_Java(  869): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  869): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  869): Bridge Server is not available
,D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1181): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/SensorManager(  869): unregisterListener ::   
,D/PersonaManagerService(  869): ACTION_SCREEN_OFF onReceive
,D/TimaKeyStoreProvider( 7564): TimaSignature is unavailable
,D/ActivityThread( 7564): Added TimaKeyStore provider
,D/NfcService( 1462): call the applyRotuiing
,D/DisplayPowerController(  869): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  869): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6a62000
,D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  869): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  869): Display changed displayId=0
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager( 7549): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7564): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/STATUSBAR-PhoneStatusBar( 1181):      ACTION_SCREEN_OFF is finished!!!! 
,D/PersonaManagerServiceHandler(  869): MSG_ACTION_SCREEN_OFF called
,D/[CarModeFW]( 7478): RecommendHandler-selection = type = '3'
,E/StatusBar( 1181): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1181): dismissHelpPopup 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/art     ( 7416): Background sticky concurrent mark sweep GC freed 59770(5MB) AllocSpace objects, 1(1611KB) LOS objects, 20% free, 27MB/34MB, paused 7.268ms total 53.775ms
W/ContextImpl( 7564): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
D/ResourcesManager( 7564): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/MessageDataHandler( 7478):  getInboxList mmsCursor : 277
I/MessageDataHandler( 7478): getUnreadMessageCount :0
D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 489
D/UserAnalysis.PlaceProvider( 7549): PlaceProvider onCreate()
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7580): MountEmulatedStorage()
E/Zygote  ( 7580): v2
I/libpersona( 7580): KNOX_SDCARD checking this for 10111
I/libpersona( 7580): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7580 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/FilterInstaller( 7564): There is no requred permission
I/SELinux ( 7580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
D/accuweather( 2075): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  275): 
W/ActivityManager(  869): Activity pause timeout for ActivityRecord{22e6e7d5 u0 com.test.thalitest/.MainActivity t3}
D/accuweather( 2075): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2075): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
D/[CarModeFW]( 7478): PushMessageService-onCreate
I/art     (  869): Explicit concurrent mark sweep GC freed 225926(15MB) AllocSpace objects, 2(4MB) LOS objects, 30% free, 35MB/51MB, paused 5.906ms total 183.662ms
I/ActivityManager(  869): Killing 6227:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
I/ActivityManager(  869): Killing 5889:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
I/ActivityManager(  869): Killing 6730:com.google.android.gms:car/u0a11 (adj 15): bgCount ##42
I/ActivityManager(  869): Killing 5550:com.google.android.apps.plus/u0a134 (adj 15): bgCount ##43
D/UserAnalysis.SecureDbManager( 7549): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7549): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7549): Create SecureDbHelper
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  869): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService(  869): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  869): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  869): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  869): Got set_interactive hint
D/MessageDataHandler( 7478):  getInboxList mms,sms cursor join : 129
I/PowerManagerService(  869): [PWL] Off : 0s ago
I/PowerManagerService(  869): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  869): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  869): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=869, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=1284)
I/PowerManagerService(  869): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=674)
I/PowerManagerService(  869): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=673)
I/PowerManagerService(  869): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=869, ws=null) (elapsedTime=590)
I/PowerManagerService(  869): [PWL]       PARTIAL_WAKE_LOCK              'GCoreFlp' (uid=10011, pid=2216, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=51)
I/PowerManagerService(  869): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  869): [PWL]     mDisplayReady : false
I/PowerManagerService(  869): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/DisplayPowerController(  869): getFinalBrightness : 0 -> 0
D/PowerManagerService(  869): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  869): [PWL] sb release: PowerManagerService.Display
W/jxcore-log( 7416): Initializing JXcore engine
W/jxcore-log( 7416): JXcore engine is ready
D/TP/MmsSmsProvider( 1468): query,matched:0, calling pid = 7478
V/TP/MmsSmsProvider( 1468): getSimpleConversations entered.
D/TimaKeyStoreProvider( 7580): TimaSignature is unavailable
D/ActivityThread( 7580): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1468): match 0:Elapsed time : 3.224 ms
D/IntelligenceServiceApplication( 7549): onCreate()
W/jxcore-log( 7416): Starting JXcore engine
D/ResourcesManager( 7580): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
I/SQLiteSecureOpenHelper( 7549): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7549): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7549): Open Place.db in secure mode
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  869): failed to open /acct/uid_10113/pid_5982/cgroup.procs: No such file or directory
D/PackageIntentReceiver( 7580): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7580): Not GearManger package! 
D/[CarModeFW]( 7478): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7478): PushMessageService-registerPushMessageServiceListener
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1468): query,matched:13, calling pid = 7478
D/TP/MmsSmsProvider( 1468): match 13:Elapsed time : 0.995 ms
I/SQLiteSecureOpenHelper( 7549): ...getDatabaseLocked(b,b,pwd)
I/libpersona( 7598): KNOX_SDCARD checking this for 10117
D/SQLiteSecureOpenHelper( 7549): ...getDatabaseLocked(b,b,pwd)
I/libpersona( 7598): KNOX_SDCARD not a persona
E/Zygote  ( 7598): MountEmulatedStorage()
E/Zygote  ( 7598): v2
D/SSRM:m  (  869): SIOP:: AP = 380, PST = 366, CUR = 450
E/auditd  ( 2117): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  869): Got Modify Event and sending Denial Intent foraudit.log
I/ActivityManager(  869): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7598 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  869): Killing 5913:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  869): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
I/SELinux ( 7598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7598): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/[CarModeFW]( 7478): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7478): MyPlaceProvider-=============
D/[CarModeFW]( 7478): MyPlaceProvider-=============
D/[CarModeFW]( 7478): MyPlaceProvider-=============
D/[CarModeFW]( 7478): MyPlaceProvider-=============
D/[CarModeFW]( 7478): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7478): MyPlaceProvider-==============
D/[CarModeFW]( 7478): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7478): MyPlaceProvider-==============
D/[CarModeFW]( 7478): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7478): MyPlaceProvider-==============
D/[CarModeFW]( 7478): MyPlaceProvider-latitude is not valid
W/ActivityManager(  869): getTasks: caller 10085 does not hold GET_TASKS; limiting output
W/ActivityManager(  869): getTasks: caller 10085 does not hold GET_TASKS; limiting output
D/PowerManagerService(  869): [PWL] sb release: PowerManagerService.Broadcasts
D/MessageDataHandler( 7478):  getInboxList address cursor : 111
D/TimaKeyStoreProvider( 7598): TimaSignature is unavailable
D/ActivityThread( 7598): Added TimaKeyStore provider
D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 796
I/[CarModeFW]( 7478): -[snowdeer] Rec : Missed Call : 821
W/jxcore-log( 7416): Platform android
W/jxcore-log( 7416): 
W/jxcore-log( 7416): Process ARCH arm
W/jxcore-log( 7416): 
D/[CarMode]( 7478): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@79050c94, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@d106b6fa] LOCATIONS
D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 831
D/TP/MmsSmsProvider( 1468): query,matched:0, calling pid = 7478
V/TP/MmsSmsProvider( 1468): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1468): match 0:Elapsed time : 0.928 ms
D/MessageDataHandler( 7478):  getInboxList thread cursor : 28
I/[CarModeFW]( 7478): -[snowdeer] Rec : Favorite : 14
D/MessageDataHandler( 7478):  thread, addr result: 1
I/[CarModeFW]( 7478): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 814
I/[CarModeFW]( 7478): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 814
D/ResourcesManager( 7598): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
I/[CarModeFW]( 7478): -[snowdeer] Rec : CallLog : 5
W/ResourcesManager( 7598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/[CarModeFW]( 7478): -[snowdeer] Rec : Schedule : 12
I/[CarModeFW]( 7478): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7478): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7478): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 840
I/[CarModeFW]( 7478): -[snowdeer] Rec : During DL app : 8
I/[CarModeFW]( 7478): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7478): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7478): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7478): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7478): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7478): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7478): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 872
E/SMD     (  285): DCD ON
D/MagazineService Version( 7598): Magazine-Administrator: 11
D/MagazineService Version( 7598): Magazine-Provider: 14
D/MagazineService Version( 7598): Magazine-Channel: 14
D/HeadlinesChannelApplication( 7598): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 7598): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
I/MagazineService::MagazineService( 7598): [onHandleIntent] ACTION_PACKAGE_INSTALLED
E/Zygote  ( 7615): MountEmulatedStorage()
E/Zygote  ( 7615): v2
I/libpersona( 7615): KNOX_SDCARD checking this for 1000
I/libpersona( 7615): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7615 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/MagazineService::MagazineService( 7598): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/SELinux ( 7615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  869): Killing 5964:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
I/SELinux ( 7615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7615): TimaSignature is unavailable
D/ActivityThread( 7615): Added TimaKeyStore provider
W/libprocessgroup(  869): failed to open /acct/uid_10093/pid_5889/cgroup.procs: No such file or directory
W/libprocessgroup(  869): failed to open /acct/uid_10011/pid_6730/cgroup.procs: No such file or directory
W/libprocessgroup(  869): failed to open /acct/uid_10134/pid_5550/cgroup.procs: No such file or directory
D/ResourcesManager( 7615): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
W/libprocessgroup(  869): failed to open /acct/uid_10102/pid_5913/cgroup.procs: No such file or directory
W/libprocessgroup(  869): failed to open /acct/uid_10125/pid_6227/cgroup.procs: No such file or directory
E/Zygote  ( 7630): MountEmulatedStorage()
E/Zygote  ( 7630): v2
I/libpersona( 7630): KNOX_SDCARD checking this for 1000
I/libpersona( 7630): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7630 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  869): Killing 5750:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
I/art     (  318): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 270us total 13.459ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.977ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.913ms
I/System.out( 7498): INFO:Resource not found:/Common.properties Using default values
I/SELinux ( 7630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  869): failed to open /acct/uid_10153/pid_5964/cgroup.procs: No such file or directory
I/SELinux ( 7630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7630): TimaSignature is unavailable
D/ActivityThread( 7630): Added TimaKeyStore provider
D/ResourcesManager( 7630): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
W/libprocessgroup(  869): failed to open /acct/uid_10157/pid_5750/cgroup.procs: No such file or directory
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
D/AcmsPackageEventListener( 7630): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl( 7630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/Zygote  ( 7647): MountEmulatedStorage()
E/Zygote  ( 7647): v2
I/libpersona( 7647): KNOX_SDCARD checking this for 10134
I/libpersona( 7647): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7647 uid=10134 gids={50134, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  869): Killing 6572:com.android.vending/u0a29 (adj 15): bgCount ##41
I/SELinux ( 7647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AcmsService( 7630): Enter Oncreate
D/AcmsServiceMonitor( 7630): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7630): creating AcmsCore
D/AcmsCore( 7630): AcmsCore.getAcmsCore() - Enter
E/SELinux ( 7647): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AcmsCore( 7630): AcmsCore
D/AcmsCore( 7630): init
D/AcmsCore( 7630): Looper handler is not null
D/AcmsCore( 7630): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7630): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7630): Incrementing - Counter value: 1
D/AcmsCore( 7630): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7630): onStartCommand
D/AcmsService( 7630): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7630): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7630): Incrementing - Counter value: 2
D/AcmsService( 7630): Incremented Counter Value : onStartCommand
D/ActivityThread( 7630): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsCertificateMngr( 7630): AcmsCertificateMngr
D/AcmsRevocationMngr( 7630): AcmsRevocationMngr
D/TimaKeyStoreProvider( 7647): TimaSignature is unavailable
D/ActivityThread( 7647): Added TimaKeyStore provider
W/libprocessgroup(  869): failed to open /acct/uid_10029/pid_6572/cgroup.procs: No such file or directory
D/ResourcesManager( 7647): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/ResourcesManager( 7647): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AcmsService( 7630): Inside handle Intent
D/AcmsService( 7630): App added - package name: com.test.thalitest
D/AcmsCore( 7630): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7630): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7630): Incrementing - Counter value: 3
D/AcmsCore( 7630): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7630): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7630): Decrementing - Counter value: 2
I/jxcore-log( 7416): JXcore Cordova bridge is ready!
I/jxcore-log( 7416): 
W/jxcore-log( 7416): JXcore engine is started
D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AlarmManager(  869): waitForAlarm result :8
V/GLSActivity( 2216): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2216): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7678): MountEmulatedStorage()
E/Zygote  ( 7678): v2
I/libpersona( 7678): KNOX_SDCARD checking this for 10165
I/libpersona( 7678): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7678 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7678): TimaSignature is unavailable
D/ActivityThread( 7678): Added TimaKeyStore provider
D/ResourcesManager( 7678): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
W/ResourcesManager( 7678): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/KidsPlatformStub( 7678): Package not found : com.sec.android.app.kidshome
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7695): MountEmulatedStorage()
E/Zygote  ( 7695): v2
I/libpersona( 7695): KNOX_SDCARD checking this for 10169
I/libpersona( 7695): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7695 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 7695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7695): TimaSignature is unavailable
D/ActivityThread( 7695): Added TimaKeyStore provider
D/ResourcesManager( 7695): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
E/SQLiteLog( 7695): (284) automatic index on shooting_modes(title_id)
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7712): MountEmulatedStorage()
E/Zygote  ( 7712): v2
I/libpersona( 7712): KNOX_SDCARD checking this for 10029
I/libpersona( 7712): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7712 uid=10029 gids={50029, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  869): Killing 6910:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
I/SELinux ( 7712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7712): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7712): TimaSignature is unavailable
D/ActivityThread( 7712): Added TimaKeyStore provider
D/ResourcesManager( 7712): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/libprocessgroup(  869): failed to open /acct/uid_10010/pid_6910/cgroup.procs: No such file or directory
,D/Finsky  ( 7712): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7712): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7712): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7712): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7712): Skipping gmscore version check
,D/Finsky  ( 7712): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7712): [1] Libraries$2.run: Finished loading 1 libraries.
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2493): Loading module APK com.google.android.play.games
,D/Finsky  ( 7712): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 2493): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ResourcesManager( 2493): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/Finsky  ( 7712): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 7712): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  869): Killing 6928:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
,W/libprocessgroup(  869): failed to open /acct/uid_10018/pid_6928/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2493): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2493): Submit a task: k
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2493): Processing package: com.test.thalitest
,D/GassUtils( 2493): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2493): Found info for package com.test.thalitest in db.
,I/jxcore-log( 7416): Toggling radios to true
I/jxcore-log( 7416): 
,D/BluetoothAdapter( 7416): enable()
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapter( 7416): enable(): BT is already enabled..!
,D/WifiService(  869): New client listening to asynchronous messages
,I/WifiManager( 7416): packageName : com.test.thalitest
I/libpersona( 7764): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7764): MountEmulatedStorage()
I/libpersona( 7764): KNOX_SDCARD not a persona
E/Zygote  ( 7764): v2
D/SecContentProvider(  869): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  869): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  869): mCursor = null
,D/WifiService(  869): setWifiEnabled: true pid=7416, uid=10356
E/WifiService(  869): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  869): Permission Denial: getCurrentUser() from pid=7416, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  869): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7764 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/WifiService(  869): Failed getting userId using ActivityManagerNative
W/WifiService(  869): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7416, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  869): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  869): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  869): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  869): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  869): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  869): name = wifi_on
,I/SELinux ( 7764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7764): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/WifiService(  869): disconnect: pid=7416, uid=10356
,I/jxcore-log( 7416): Radios toggled
I/jxcore-log( 7416): 
,I/wpa_supplicant( 1270): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1270): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1270): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1270): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1270): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/jxcore-log( 7416): Got Device Bluetooth address: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7416): 
,E/WifiStateMachine(  869): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1270): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1270): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1270): Disconnected - do not scan
I/wpa_supplicant( 1270): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/jxcore-log( 7416): Perf Test app loaded loaded
I/jxcore-log( 7416): 
,E/WifiStateMachine(  869): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  869): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  869): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  869): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 7764): TimaSignature is unavailable
,D/ActivityThread( 7764): Added TimaKeyStore provider
,I/jxcore-log( 7416): check test folder
I/jxcore-log( 7416): 
,I/art     (  869): Explicit concurrent mark sweep GC freed 21965(1357KB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 35MB/51MB, paused 4.840ms total 108.131ms
,I/jxcore-log( 7416): found test : ./testFindPeers.js
I/jxcore-log( 7416): 
,E/WifiStateMachine(  869): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  869): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  869): do suspend true
,D/WifiP2pService(  869): InactiveState{ what=143375 }
D/WifiP2pService(  869): P2pEnabledState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2216): Read error: ssl=0xaf11b800: I/O error during system call, Connection timed out
,V/NativeCrypto( 2216): SSL shutdown failed: ssl=0xaf11b800: I/O error during system call, Broken pipe
,I/jxcore-log( 7416): found test : ./testSendData.js
I/jxcore-log( 7416): 
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7764): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,E/WifiStateMachine(  869): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiConfigStore(  869): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService(  869): updateNetworkInfo()
D/ConnectivityService(  869): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  869): updateNetworkInfo()
D/ConnectivityService(  869): ignoring duplicate network state non-change
,I/WifiTrafficPoller(  869): evaluateTrafficStatsPolling
D/ConnectivityService(  869): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  869): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): Forcing reevaluation
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/CLocInfoService(  869): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  869): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): Validated
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,I/wpa_supplicant( 1270): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1270): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1270): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1270): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1270): First Scan Start
,I/wpa_supplicant( 1270): Scan requested (ret=0) - scan timeout 30 seconds
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,E/WifiStateMachine(  869): ConnectModeState: Network connection lost 
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/WifiStateMachine(  869): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  869): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  869): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  869): do suspend true
,D/WifiP2pService(  869): InactiveState{ what=143375 }
,D/WifiP2pService(  869): P2pEnabledState{ what=143375 }
,I/PeopleDatabaseHelper( 2493): cleanUpNonGplusAccounts done.
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService(  869): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  869): calling update connectivity
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  869): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  869): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  869): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  869): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): Disconnected - quitting
D/ConnectivityService(  869): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine(  869): updateConfiguredNetworkExpiration - currTime: 1450233121239
D/WifiStateMachine(  869): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/TelephonyNetworkFactory( 1468): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  869): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  869): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/CSLegacyTypeTracker(  869): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/EntConnectivity(  869): Not allowed due to - mEnabled false
D/CSLegacyTypeTracker(  869): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  869): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
,I/WifiTrafficPoller(  869): evaluateTrafficStatsPolling
D/WifiNetworkAgent(  869): NetworkAgent: NetworkAgent channel lost
,I/CLocInfoService(  869): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  869): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  869): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  869): setDetailed state send new extra info"NG700"
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  869): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  869): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  869): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats(  869): updateIfacesLocked()
V/NetworkStats(  869): performPollLocked(flags=0x1)
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  869): UpdateStatsForKnox
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
D/SmartBondingService(  869): getNetworkEnabled : wifi : true mobile : true
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524292
,D/NtpTrustedTime(  869): currentTimeMillis() cache hit
,D/NtpTrustedTime(  869): currentTimeMillis() cache hit
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
,V/NetworkStats(  869): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
,E/ConnectivityService(  869): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  869): performPollLocked() took 12ms
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
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
,D/SecContentProvider2(  869): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  869): mCursor = null
,D/NtpTrustedTime(  869): currentTimeMillis() cache hit
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,D/SecContentProvider2(  869): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  869): mCursor = null
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,I/chromium( 7416): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,W/BaseAppContext( 2493): Using Auth Proxy for data requests.
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7799): MountEmulatedStorage()
E/Zygote  ( 7799): v2
I/libpersona( 7799): KNOX_SDCARD checking this for 10157
I/libpersona( 7799): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7799 uid=10157 gids={50157, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  869): Killing 6943:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
,I/SELinux ( 7799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 7416): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TimaKeyStoreProvider( 7799): TimaSignature is unavailable
,D/ActivityThread( 7799): Added TimaKeyStore provider
,W/libprocessgroup(  869): failed to open /acct/uid_10036/pid_6943/cgroup.procs: No such file or directory
,D/ResourcesManager( 7799): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/TaskCloserActivity( 7799): TaskCloserActivity enter()
,V/TaskCloserActivity( 7799): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/ActivityManager(  869): Killing 6980:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,D/BootupListener( 1468): ACTION_DRIVELINK
D/SettingsProvider(  869): name = drivelink_navigation
D/SettingsProvider(  869): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  869): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  869): selectionArgs: false
D/SettingsProvider(  869): selectionArgs: 1001
,D/SecContentProvider(  869): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  869): ret = -1
D/BootupListener( 1468): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  869): name = internet_call_settings_visibility
D/SettingsProvider(  869): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  869): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  869): selectionArgs: false
D/SettingsProvider(  869): selectionArgs: 1001
D/SecContentProvider(  869): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  869): ret = -1
,D/SecurityLogAgent( 7036):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7036):  SeDenialReceiver : File path = null
,D/AcmsKeyStoreHelper( 7630):  getKeyStoreForApplication Enter
,I/Hs20UtilService( 1314): Starting #6
,I/Hs20UtilService( 1314): Message received 5007
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1314): Starting #7
,I/Hs20UtilService( 1314): Message received 5007
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
W/libprocessgroup(  869): failed to open /acct/uid_10066/pid_6980/cgroup.procs: No such file or directory
V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
,I/AcmsKeyStoreHelper( 7630): Key Store exist
I/AcmsKeyStoreHelper( 7630): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 7630):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7630): getKeyStoreForApplication success 
D/AcmsCore( 7630): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7630): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7630): Decrementing - Counter value: 1
D/AcmsCore( 7630): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7630): This is NOT a valid MirrorLink app
D/AcmsCore( 7630): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7630): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7630): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7630): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7630): getSvcCounter - Counter value: 0
D/AcmsService( 7630): Enter onDestroy
I/AcmsService( 7630): cleanUp(): inside service clean up
D/AcmsCore( 7630): AcmsCore: inside DeInit
D/AcmsCore( 7630): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7630): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7630): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7630): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7630): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7630): getSvcCounter - Counter value: 0
D/AcmsService( 7630): killing acms process
I/Process ( 7630): Sending signal. PID: 7630 SIG: 9
,I/ActivityManager(  869): Process ACMS.Process (pid 7630)(adj 0) has died(79,583)
,D/ConnectivityService(  869): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  869): updateDataUsageMap
,W/art     ( 2493): Suspending all threads took: 63.110ms
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  869): MasterInitialState.processMessage what=3
D/SmartBondingService(  869): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  869): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  869): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/CLocInfoService(  869): CLoinfo wifi false
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/accuweather( 2075): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  869): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  869): No Active Data Connection
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7224): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7224): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7224): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7224): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7224): noConnectivity : true
,I/DBG_DM  ( 3701): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/Zygote  ( 7816): MountEmulatedStorage()
E/Zygote  ( 7816): v2
I/libpersona( 7816): KNOX_SDCARD checking this for 10125
I/libpersona( 7816): KNOX_SDCARD not a persona
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3701): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/ActivityManager(  869): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7816 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7816): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7816): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7816): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/FactoryTest( 6430): Not factory mode
,D/FactoryTest( 6430): Not factory mode. isFactoryMode() returend false
D/TimaKeyStoreProvider( 7816): TimaSignature is unavailable
,D/ActivityThread( 7816): Added TimaKeyStore provider
,D/MTPRx   ( 6430): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6430): still no open session command from host, so toast
,W/ContextImpl( 6430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6430): Timeline: Activity_launch_request id:com.android.settings time:109221
E/PersonaManagerService(  869): inState():  stateMachine is null !!
,W/SQLiteConnectionPool( 2493): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/ApplicationPolicy(  869): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  869): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/art     ( 2493): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 227.550ms
,W/ActivityManager(  869): mDVFSHelper.acquire()
,V/ActivityManager(  869): Display changed displayId=0
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
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager( 7816): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/MTPRx   ( 6430): started activity for popup
,I/SQLiteSecureOpenHelper( 3505): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3505): getDatabaseLocked(b,b,pwd)...
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager( 6430): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6430): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6430): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6430): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6430): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/InputMethodManagerService(  869): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  869): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@e7c9aa4 attribute=android.view.inputmethod.EditorInfo@2104000d, token = android.os.BinderProxy@13e8f4b5
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/MusicStore( 7816): Database version: 104
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6430): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6430): dev.kiessupport is : TRUE
,D/ResourcesManager( 7816): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/Activity( 6430): performCreate Call secproduct feature valuefalse
D/Activity( 6430): performCreate Call debug elastic valuetrue
,W/ResourcesManager( 7816): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7816): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ActivityManager(  869): post active user change for 0
D/KnoxTimeoutHandler(  869): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  869): handleActiveUserChange for user 0
,D/ChimeraCfgMgr( 2493): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2493): Module APK com.google.android.play.games already loaded
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Timeline( 7416): Timeline: Activity_idle id: android.os.BinderProxy@14f769ed time:109448
,V/JNIHelp ( 7816): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,W/ActivityThread( 7816): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7816): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f241a94: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7816): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7816): GMSCore installation verified
,I/ConfigStore( 7816): Config Database version: 1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7816): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7816): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7816): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  869): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/SMD     (  285): DCD ON
,D/WifiDisplayAdapter(  869): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  292): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  869): getStreamVolume 3 index 0
,I/MediaRouter( 7816): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/Icing   ( 2493): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7846): MountEmulatedStorage()
E/Zygote  ( 7846): v2
I/libpersona( 7846): KNOX_SDCARD checking this for 10002
I/libpersona( 7846): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7846 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7846): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7846): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7846): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  869): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7816): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7846): TimaSignature is unavailable
,D/ActivityThread( 7846): Added TimaKeyStore provider
,I/ActivityManager(  869): Killing 6865:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,D/ResourcesManager( 7846): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 1270): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1270): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1270): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1270): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1270): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  869): [1,450,233,122,288 ms] noteScanEnd no scan source
,E/WifiStateMachine(  869): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@11ad8b3a sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  869): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  869): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  869): setDetailed state send new extra info0x
,I/CLocInfoService(  869): External Intent Received android.net.wifi.SCAN_RESULTS
,D/SecContentProvider2(  869): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  869): mCursor = null
,D/ResourcesManager( 2493): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,W/libprocessgroup(  869): failed to open /acct/uid_10070/pid_6865/cgroup.procs: No such file or directory
,I/Icing   ( 2493): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/ActivityManager(  869): Killing 7002:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7865): MountEmulatedStorage()
,E/Zygote  ( 7865): v2
I/libpersona( 7865): KNOX_SDCARD checking this for 1000
I/libpersona( 7865): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7865 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7865): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1270): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1270): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1270): Associated with C0.AA.48
,W/libprocessgroup(  869): failed to open /acct/uid_10090/pid_7002/cgroup.procs: No such file or directory
E/WifiStateMachine(  869): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  869): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  869): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  869): mCursor = null
,D/TimaKeyStoreProvider( 7865): TimaSignature is unavailable
,D/ActivityThread( 7865): Added TimaKeyStore provider
,D/ResourcesManager( 7865): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/wpa_supplicant( 1270): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1270): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  869): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  869): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  869): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  869): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  869): mCursor = null
,I/wpa_supplicant( 1270): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1270): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1270): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1270): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/DIAGMON_AGENT( 7865): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
I/wpa_supplicant( 1270): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1270): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1270): Blacklist: Clear (temp) 
I/wpa_supplicant( 1270): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  869): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  869): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  869): Network connection established
,D/WifiNative-HAL(  869): callSECApiVoid - ID [50]
E/WifiStateMachine(  869): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  869): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  869): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  869): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  869): Got NetworkAgent Messenger
D/ConnectivityService(  869): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  869): updateNetworkInfo()
D/ConnectivityService(  869): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  869): NetworkAgent connected
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  869): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  869): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  869): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/DIAGMON_AGENT( 7865): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine(  869): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  869): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  869): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  869): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine(  869): Start Dhcp Watchdog 2
,D/SecContentProvider2(  869): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  869): mCursor = null
,E/WifiStateMachine(  869): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  869): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  869): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT( 7865): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7865): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7865): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  869): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  869): do suspend false
I/DIAGMON_AGENT( 7865): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/WifiP2pService(  869): InactiveState{ what=143375 }
D/SecContentProvider2(  869): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  869): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  869): mCursor = null
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7885): MountEmulatedStorage()
,E/Zygote  ( 7885): v2
I/libpersona( 7885): KNOX_SDCARD checking this for 10010
I/libpersona( 7885): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7885 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7885): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7885): TimaSignature is unavailable
,D/ActivityThread( 7885): Added TimaKeyStore provider
,D/ResourcesManager( 7885): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  869): Killing 7017:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,I/FOTA_Client( 7885): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7885): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7885): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  869): failed to open /acct/uid_10103/pid_7017/cgroup.procs: No such file or directory
,E/Zygote  ( 7904): MountEmulatedStorage()
,E/Zygote  ( 7904): v2
I/libpersona( 7904): KNOX_SDCARD checking this for 10018
I/libpersona( 7904): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7904 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  869): Killing 5936:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,I/art     (  318): Explicit concurrent mark sweep GC freed 8712(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 266us total 14.265ms
,I/SELinux ( 7904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.001ms
E/SELinux ( 7904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7911): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 8.310ms
,I/dhcpcd  ( 7911): version 5.5.6 starting
,E/dhcpcd  ( 7911): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/GAV2    ( 7394): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 7904): TimaSignature is unavailable
,D/ActivityThread( 7904): Added TimaKeyStore provider
W/libprocessgroup(  869): failed to open /acct/uid_10112/pid_5936/cgroup.procs: No such file or directory
,D/ResourcesManager( 7904): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/dhcpcd  ( 7911): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7911): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 7911): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7911): bssid match
I/dhcpcd  ( 7911): wlan0: rebinding lease of 192.168.1.136
,I/KLMS-2.4.503: ( 7904): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7904): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233122830
,I/KLMS-2.4.503: ( 7904): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7904): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7904): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  869): Killing 5678:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7933): MountEmulatedStorage()
E/Zygote  ( 7933): v2
,I/libpersona( 7933): KNOX_SDCARD checking this for 10036
I/libpersona( 7933): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7933 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7933): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7933): TimaSignature is unavailable
,D/ActivityThread( 7933): Added TimaKeyStore provider
,W/libprocessgroup(  869): failed to open /acct/uid_10148/pid_5678/cgroup.procs: No such file or directory
,D/ResourcesManager( 7933): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7933): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7261): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6959): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6959): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6959): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6959): [SLFUCHKMGR] constructor called
,I/SA      ( 6959): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6959): [OR] == isSIMCardReady false ==
I/SA      ( 6959): [SCU] == networkStateCheck == false
I/SA      ( 6959): [OR] onReceive END
,E/SPPClientService( 7261): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7951): MountEmulatedStorage()
E/Zygote  ( 7951): v2
I/libpersona( 7951): KNOX_SDCARD checking this for 10070
I/libpersona( 7951): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7951 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  869): Killing 4722:com.android.calendar/u0a149 (adj 15): bgCount ##41
E/SELinux ( 7951): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7951): TimaSignature is unavailable
,D/ActivityThread( 7951): Added TimaKeyStore provider
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7951): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7951): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7951): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7951): [KK AccuPhone]>>> ==============================================================================================
,W/libprocessgroup(  869): failed to open /acct/uid_10149/pid_4722/cgroup.procs: No such file or directory
,D/comsamsunglog( 7951): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7951): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7951): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7951): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  869): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  869): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  869): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  869): selectionArgs: false
D/SettingsProvider(  869): selectionArgs: 10070
D/SecContentProvider(  869): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  869): ret = -1
,D/daemonapp( 1339): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7951): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7951): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7951): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7951): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7951): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7951): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1339): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7951): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1339): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7951): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1339): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7951): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7951): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7968): MountEmulatedStorage()
E/Zygote  ( 7968): v2
I/libpersona( 7968): KNOX_SDCARD checking this for 1000
I/libpersona( 7968): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  869): Killing 7052:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/SELinux ( 7968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7968): TimaSignature is unavailable
,D/ActivityThread( 7968): Added TimaKeyStore provider
,W/libprocessgroup(  869): failed to open /acct/uid_10175/pid_7052/cgroup.procs: No such file or directory
,D/ResourcesManager( 7968): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7968): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7968): premStatus:2
,I/KnoxUsageLogPro( 7968): isEulaShown : false
I/KnoxUsageLogPro( 7968): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7983): MountEmulatedStorage()
E/Zygote  ( 7983): v2
I/libpersona( 7983): KNOX_SDCARD checking this for 10087
I/libpersona( 7983): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7983 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  869): Killing 7067:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,I/SELinux ( 7983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7983): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  869): failed to open /acct/uid_1000/pid_7067/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7983): TimaSignature is unavailable
,D/ActivityThread( 7983): Added TimaKeyStore provider
,D/ResourcesManager( 7983): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  869): Killing 6127:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,D/Headlines( 5457): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5457): getCountryCode(): countryCode = PL
,D/Headlines( 5457): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5457): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5457): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5457): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5457): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5457): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5457): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7999): MountEmulatedStorage()
,E/Zygote  ( 7999): v2
I/libpersona( 7999): KNOX_SDCARD checking this for 10127
I/libpersona( 7999): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7999 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7999): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  869): failed to open /acct/uid_10045/pid_6127/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7999): TimaSignature is unavailable
,D/ActivityThread( 7999): Added TimaKeyStore provider
,V/AlarmManager(  869): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/ResourcesManager( 7999): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7999): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7999): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7999): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7999): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7999): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7999): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7999): Loading: webviewchromium
,I/LibraryLoader( 7999): Time to load native libraries: 5 ms (timestamps 1048-1053)
I/LibraryLoader( 7999): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7999): Binding Chromium to main looper Looper (main, tid 1) {28724c00}
,I/LibraryLoader( 7999): Expected native library version number "",actual native library version number ""
,I/chromium( 7999): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7999): Initializing chromium process, renderers=0
,W/art     ( 7999): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7999): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid( 7999): Requires BLUETOOTH permission
,I/chromium( 7999): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7999): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7999): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7999): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7999): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7999): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7999): Remote Branch: 
I/Adreno-EGL( 7999): Local Patches: 
I/Adreno-EGL( 7999): Reconstruct Branch: 
,I/NSApplication( 7999): Starting up...
,I/ActivityManager(  869): Killing 7189:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8063): MountEmulatedStorage()
,E/Zygote  ( 8063): v2
I/libpersona( 8063): KNOX_SDCARD checking this for 10137
I/libpersona( 8063): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8063 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 8063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  869): failed to open /acct/uid_10014/pid_7189/cgroup.procs: No such file or directory
,I/SELinux ( 8063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8063): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8063): TimaSignature is unavailable
,D/ActivityThread( 8063): Added TimaKeyStore provider
,D/ResourcesManager( 8063): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8063): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8063): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8063): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 8063): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8063): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8063): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8078): MountEmulatedStorage()
,E/Zygote  ( 8078): v2
I/libpersona( 8078): KNOX_SDCARD checking this for 10162
I/libpersona( 8078): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8078 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  869): Killing 7208:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 8078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7911): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/dhcpcd  ( 7911): wlan0: leased 192.168.1.136 for 86400 seconds
,W/libprocessgroup(  869): failed to open /acct/uid_10015/pid_7208/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8078): TimaSignature is unavailable
,E/WifiStateMachine(  869): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  869): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  869): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ActivityThread( 8078): Added TimaKeyStore provider
,I/PowerManagerService(  869): [PWL] Off : 5s ago
,I/PowerManagerService(  869): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  869): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  869): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=869, ws=null) (elapsedTime=2720)
,D/ResourcesManager( 8078): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8078): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8078): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8078): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8078): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  869): exchangeData() failure , invalid userId
,D/RCPManagerService(  869): exchangeData() failure , invalid userId
,D/RCPManagerService(  869): exchangeData() failure , invalid userId
,D/RCPManagerService(  869): exchangeData() failure , invalid userId
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8126): MountEmulatedStorage()
E/Zygote  ( 8126): v2
,I/libpersona( 8126): KNOX_SDCARD checking this for 10077
I/libpersona( 8126): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8126 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,E/WifiStateMachine(  869): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  869): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  869): do suspend true
I/SELinux ( 8126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8126): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  869): exchangeData() failure , invalid userId
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/WifiP2pService(  869): InactiveState{ what=143375 }
,D/WifiP2pService(  869): P2pEnabledState{ what=143375 }
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
E/WifiStateMachine(  869): WifiStateMachine DHCP successful
E/WifiStateMachine(  869): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  869): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  869): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  869): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  869): Not connected state, yet.
E/WifiStateMachine(  869): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  869): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  869): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  869): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  869): callSECApiInt - ID [210]
,E/WifiStateMachine(  869): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  869): updateNetworkInfo()
,D/RCPManagerService(  869): exchangeData() failure , invalid userId
,I/CLocInfoService(  869): External Intent Received android.net.wifi.STATE_CHANGE
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/WifiWatchdogStateMachine(  869): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  869): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
D/WifiWatchdogStateMachine.DnsResolver(  869): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  869): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  869): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,D/ConnectivityService(  869): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  869): Adding iface wlan0 to network 503
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,D/TimaKeyStoreProvider( 8126): TimaSignature is unavailable
,D/ActivityThread( 8126): Added TimaKeyStore provider
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,E/WifiStateMachine(  869): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  869): Now, connected state.
E/WifiStateMachine(  869): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/SecurityLogAgent( 7036): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7036): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7036): StateMachine : Current State = 1
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
D/SecurityLogAgent( 7036): StateMachine : Changed Current State = 1
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
I/ActivityManager(  869): Killing 6456:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,E/WifiStateMachine(  869): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller(  869): evaluateTrafficStatsPolling
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,I/CLocInfoService(  869): External Intent Received android.net.wifi.STATE_CHANGE
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 8126): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager(  869): Killing 4912:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
I/WifiTrafficPoller(  869): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  869): mBoosterFLAG : 0
I/WifiTrafficPoller(  869): current booster mode : FullMode
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
D/ConnectivityService(  869): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  869): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
D/ConnectivityService(  869): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
D/ConnectivityService(  869): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/WifiStateMachine(  869): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/WifiNative-HAL(  869): callSECApiVoid - ID [212]
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
I/CLocInfoService(  869): External Intent Received android.net.wifi.STATE_CHANGE
E/ConnectivityService(  869): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  869): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  869): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  280): QcRouteController
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
I/WifiStateMachine(  869): REQUEST_POWER_SAVE_ON
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/        (  280): QcRouteController
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
D/BadgeProvider( 8126): onCreate
D/BadgeProvider( 8126): DatabaseHelper
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/        (  280): QcRouteController
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
V/        (  280): QcRouteController
,E/Zygote  ( 8153): MountEmulatedStorage()
I/libpersona( 8153): KNOX_SDCARD checking this for 10177
E/Zygote  ( 8153): v2
I/libpersona( 8153): KNOX_SDCARD not a persona
,I/ActivityManager(  869): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8153 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/        (  280): QcRouteController
,I/SELinux ( 8153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/BadgeProvider( 8126): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
E/SELinux ( 8153): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,D/Launcher.Model( 1474): reloadBadges entered.
D/BadgeProvider( 8126): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8126): sendNotify, [notify] : null
D/BadgeProvider( 8126): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8126): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8126): update, [UpdateCount] : 1
,V/BitmapFactory( 8078): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,V/        (  280): QcRouteController
,D/TimaKeyStoreProvider( 8153): TimaSignature is unavailable
D/ActivityThread( 8153): Added TimaKeyStore provider
,D/ConnectivityService(  869): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  869): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  869): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  869): updateNetworkInfo()
D/ConnectivityService(  869): calling update connectivity
E/ConnectivityService(  869): updateNetworkInfo()
D/ConnectivityService(  869): ignoring duplicate network state non-change
D/ConnectivityService(  869): ignoring duplicate network state non-change
D/ConnectivityService(  869): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  869): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  869): calling update connectivity
D/ConnectivityService(  869): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  869):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  869):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  869):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  869): Validated
,D/ConnectivityService(  869): currentScore = 0, newScore = 60
D/ConnectivityService(  869):    accepting network in place of null
D/ConnectivityService(  869): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1468): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  869): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  869): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  869): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ResourcesManager( 8153): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ConnectivityService(  869): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  869): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  869): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  869): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
,D/EntConnectivity(  869): Not allowed due to - mEnabled false
D/ConnectivityService(  869): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  869): calling update connectivity
,D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  869): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  869): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
D/ConnectivityService(  869): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  869): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  869):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  869):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  869):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  869): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  869): calling update connectivity
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  869): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
D/ConnectivityService(  869): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/NetworkStats(  869): updateIfacesLocked()
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
V/NetworkStats(  869): performPollLocked(flags=0x1)
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
V/NetworkStats(  869): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NetworkStatsFactory(  869): UpdateStatsForKnox
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524290
,V/NetworkStats(  869): performPollLocked() took 3ms
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  869): currentTimeMillis() cache hit
D/NtpTrustedTime(  869): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,W/libprocessgroup(  869): failed to open /acct/uid_10033/pid_6456/cgroup.procs: No such file or directory
D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,W/libprocessgroup(  869): failed to open /acct/uid_10034/pid_4912/cgroup.procs: No such file or directory
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ActivityManager(  869): Killing 7278:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7764): notifyNetworkActivated
,W/ContextImpl( 7764): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  869): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  869): failed to open /acct/uid_10041/pid_7278/cgroup.procs: No such file or directory
,I/art     (  869): Explicit concurrent mark sweep GC freed 59532(3MB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 35MB/51MB, paused 1.360ms total 77.860ms
,W/ActivityManager(  869): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 7764): AutoUpdateManager:IDLE:execute
I/Hs20UtilService( 1314): Starting #8
,I/Hs20UtilService( 1314): Message received 5007
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 7764): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7764): exit::IDLE
D/InitializeManagerStateMachine( 7764): entry::NETWORK_CHECK
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7764): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7764): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7764): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7764): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7764): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7764): entry::SUCCESS
D/hcjo    ( 7764): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/hcjo    ( 7764): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7764): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/InitializeManagerStateMachine( 7764): exit::SUCCESS
D/InitializeManagerStateMachine( 7764): entry::IDLE
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
,I/Hs20UtilService( 1314): Starting #9
,I/Hs20UtilService( 1314): Message received 5007
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1314): Starting #10
,I/Hs20UtilService( 1314): Message received 5007
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1314): Starting #11
,I/Hs20UtilService( 1314): Message received 5007
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  869): callSECApi what=220
,D/WifiStateMachine(  869): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  869): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=869
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  869): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  869): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  869): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  869): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  869): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
,D/Tethering(  869): MasterInitialState.processMessage what=3
,I/CLocInfoService(  869): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  869): CLocinfo wifi true 
D/SmartBondingService(  869): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2193): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/accuweather( 2075): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3701): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  869): mDVFSHelper.release()
,I/PCWCLIENTTRACE_PushUtil( 7224): SPPPushClient is installed : true
,I/DBG_DM  ( 3701): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/PCWCLIENTTRACE_PushUtil( 7224): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7224): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7224): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7816): type=WIFI subType= reason=null isConnected=true
,D/SecContentProvider2(  869): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  869): mCursor = null
,I/GAV2    ( 7647): Thread[GAThread,5,main]: No campaign data found.
,I/DIAGMON_AGENT( 7865): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7865): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7885): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7885): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7885): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7904): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7904): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233125029
,I/KLMS-2.4.503: ( 7904): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7904): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7904): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7904): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7904): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  869): Killing 5845:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,V/GLSActivity( 2216): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SO_AGENT( 7933): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/VacuumService( 2216): Vacuum at: now=1450233125069 tag=VacuumService
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  869): failed to open /acct/uid_10047/pid_5845/cgroup.procs: No such file or directory
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7261): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6959): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6959): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6959): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6959): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6959): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6959): [SCU] == networkStateCheck == true
,I/SA      ( 6959): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6959): isChinaCountryCode : false
I/SA      ( 6959): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6959): [OR] == networkStateCheck true ==
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6959): [OR] GetMyCountryZoneTask
,I/SA      ( 6959): [OR] onReceive END
,I/SA      ( 6959): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6959): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6959): [SSP] query invoked
,D/accuweather( 7951): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7951): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6959): [TPMU] GetMccFromDB : null
,I/SA      ( 6959): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6959): [TPM] isNoProxy(default) : true
I/KnoxUsageLogPro( 7968): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7968): premStatus:2
,I/KnoxUsageLogPro( 7968): isEulaShown : false
I/KnoxUsageLogPro( 7968): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6959): fail readDirectory() errno=2
,D/Headlines( 5457): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5457): getCountryCode(): countryCode = PL
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Headlines( 5457): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5457): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5457): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5457): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5457): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5457): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5457): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8063): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8063): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 8063): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  869): exchangeData() failure , invalid userId
D/RCPManagerService(  869): exchangeData() failure , invalid userId
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7036): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7036): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7036): StateMachine : Current State = 1
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7036): StateMachine : Changed Current State = 1
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7764): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7764): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7764): exit::IDLE
D/InitializeManagerStateMachine( 7764): entry::NETWORK_CHECK
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7764): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7764): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7764): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7764): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7764): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7764): entry::SUCCESS
D/hcjo    ( 7764): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 7764): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7764): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7764): exit::SUCCESS
D/InitializeManagerStateMachine( 7764): entry::IDLE
,D/ConnectivityService(  869): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/SA      ( 6959): [RC New] Execute method=[GET] start
,I/SA      ( 6959): [RC New] Security=[true]
,I/System.out( 6959): Thread-1080(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6959): Thread-1080(ApacheHTTPLog):isShipBuild true
,I/System.out( 6959): Thread-1080(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ProcessCpuTracker(  869): Skipping unknown process pid 8219
,I/jxcore-log( 7416): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7416): 
,D/PackageManager(  869): [MSG] MCS_UNBIND
,I/ActivityManager(  869): Killing 5765:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/CountryDetector(  869): No listener is left
,W/libprocessgroup(  869): failed to open /acct/uid_10049/pid_5765/cgroup.procs: No such file or directory
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/SA      ( 6959): [RC New] [v2liruge] api execute + 704
I/SA      ( 6959): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6959): AsyncTask #1 calls detatch()
,I/SA      ( 6959): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6959): [OCP] update openData : PL
,I/SA      ( 6959): [TPMU] getNetworkMcc : 
,I/SA      ( 6959): [SCU] saveMccToPreferece Start
I/SA      ( 6959): [SCU] RegionMCC : 260
,I/SA      ( 6959): [SSP] query invoked
,I/SA      ( 6959): [TPMU] GetMccFromDB : null
I/SA      ( 6959): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6959): [SCU] saveMccToPreferece End
,I/SA      ( 6959): [RC New] executeRequest [v2liruge] end. 754
I/SA      ( 6959): [RC New] Execute end
I/SA      ( 6959): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6959): [OR] GetMyCountryZoneTask Success
,V/AlarmManager(  869): waitForAlarm result :8
,E/WifiStateMachine(  869): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  869): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  869): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  869): identical MTU - not setting
D/ConnectivityService(  869): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  869): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  280): QcRouteController
,E/WifiStateMachine(  869): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/dhcpcd  ( 7911): wlan0: sending IPv6 Router Solicitation
,D/SmartBondingService(  869): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  869): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  869): getSBEnabled() enabled =false
,D/SmartBondingService(  869): getSBEnabled() enabled =false
D/SmartBondingService(  869): getSBEnabled() enabled =false
,V/        (  280): QcRouteController
,W/NetworkManagementService(  869): route cmd failed: 
W/NetworkManagementService(  869): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  869): '
W/NetworkManagementService(  869): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  869): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  869): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  869): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  869): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  869): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  869): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  869): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  869): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  869): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  869): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  869): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  869): calling update connectivity
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  869): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
,D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  869): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524295
,D/ConnectivityService(  869): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  869): calling update connectivity
,D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  869): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
,D/ConnectivityService(  869):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  869): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2493): CM callback handler got msg 524295
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/WearableService( 2216): callingUid 10011, callindPid: 2216
,D/ResourcesManager( 7816): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7816): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7816): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7816): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7816): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7816): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7816): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 7816): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7816): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7816): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7816): Conditions not met for autocaching.
I/MusicLeanback( 7816): Stop autocaching.
,E/ActivityThread( 7816): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@9f09d3e that was originally bound here
E/ActivityThread( 7816): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@9f09d3e that was originally bound here
E/ActivityThread( 7816): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7816): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7816): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7816): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7816): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7816): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7816): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7816): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7816): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7816): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7816): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7816): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7816): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7816): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7816): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7816): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7816): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7816): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7816): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7816): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7816): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine(  869): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  869): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  869): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 869) eventTime = 115565
,D/PowerManagerService(  869): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=869 (0x0)
,D/PowerManagerService(  869): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=869, ws=WorkSource{10058}) (elapsedTime=3525)
,E/SMD     (  285): DCD ON
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/GAV4    ( 7999): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:m  (  869): SIOP:: AP = 400, PST = 362, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7224): mConnectivityHandler : connected
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7224): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7224): [GetString-S]
,I/ReactiveServiceManager( 7224): Supported : 1
,D/QSEECOMAPI: (  869): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  869): App is not loaded in QSEE
,D/QSEECOMAPI: (  869): Loaded image: APP id = 3
,D/QSEECOMAPI: (  869): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  869): QSEECom_shutdown_app, app_id = 3
,E/terrier (  869): handleString: Failed to handle string(-4)
E/terrier (  869): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 7224): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7224): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7224): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7224): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7224): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7224): [ensureRegistration] - No Samsung account
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,I/dhcpcd  ( 7911): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 15s ago
,E/SMD     (  285): DCD ON
,D/PreloadUpdateManagerStateMachine( 7764): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7764): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7764): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7764): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7764): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7764): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7764): entry::IDLE
,I/dhcpcd  ( 7911): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7911): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7764): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7764): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7764): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7764): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7764): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7764): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7764): entry::IDLE
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  869): waitForAlarm result :4
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
D/BatteryService(  869): stay LED for fully charged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 2216): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2216): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7712): [1255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7712): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  869): SIOP:: AP = 330, PST = 352, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON,
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  869): !@Sync 4
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 30s ago
,V/AlarmManager(  869): waitForAlarm result :4
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  869): stay LED for fully charged
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 310, PST = 343, CUR = 450
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/SSRM:m  (  869): SIOP:: AP = 310, PST = 339, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 50s ago
,D/SSRM:m  (  869): SIOP:: AP = 300, PST = 336, CUR = 450
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  869): !@Sync 5
,E/SMD     (  285): DCD ON
,V/AlarmManager(  869): waitForAlarm result :4
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  869): stay LED for fully charged
D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2216): Scheduling Phenotype for one-off execution 5568 seconds from now (1450233178199)
,D/GetConfigurationSnapshotOperation( 2216): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2216): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2216): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  869): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 2216): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 2216): (HTTPLog)-Static: isShipBuild true
I/System.out( 2216): (HTTPLog)-Thread-304-983244134: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2216): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 2216, getuid(): 10011
,I/qtaguid ( 2216): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 2216, getuid(): 10011
,D/LocationManagerService(  869): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2216): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 2216, getuid(): 10011
,D/LocationManagerService(  869): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2216): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 2216, getuid(): 10011
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  869): SIOP:: AP = 290, PST = 332, CUR = 450
,V/AlarmManager(  869): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 290, PST = 328, CUR = 450
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 75s ago
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  869): SIOP:: AP = 290, PST = 324, CUR = 450
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  869): !@Sync 6
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 2216): disconnect managed GoogleApiClient
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 290, PST = 319, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 290, PST = 310, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  869): [PWL] Off : 105s ago
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 270, PST = 297, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/Watchdog(  869): !@Sync 7
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,V/AlarmManager(  869): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/EventLogService( 2493): Aggregate from 1450231439105 (log), 1450231439105 (data)
,D/SSRM:m  (  869): SIOP:: AP = 270, PST = 291, CUR = 450
,V/AlarmManager(  869): waitForAlarm result :8
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 270, PST = 287, CUR = 450
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 140s ago
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 282, CUR = 450
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/jxcore-log( 7416): Connected to the server!
I/jxcore-log( 7416): 
,I/chromium( 7416): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  869): !@Sync 8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 278, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 275, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 272, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 9
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 180s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 269, CUR = 450
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 266, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 263, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  869): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  869): TimaServiceHandler.handleMessage what =1
,D/TimaService(  869): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  869): initializing...
,I/TLC_TIMA_PKM_initialize(  869): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  869): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  869): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  869): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  869): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  869): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  869): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  869): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  869): App is not loaded in QSEE
,D/QSEECOMAPI: (  869): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  869): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  869): Trustlet response is completed
,E/Watchdog(  869): !@Sync 10
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  869): stay LED for fully charged
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 262, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  285): DCD ON
,V/AlarmManager(  869): waitForAlarm result :4
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0,
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): stay LED for fully charged
,E/Zygote  ( 8407): MountEmulatedStorage()
,I/ActivityManager(  869): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8407 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8407): v2
,I/libpersona( 8407): KNOX_SDCARD checking this for 10080
,I/libpersona( 8407): KNOX_SDCARD not a persona
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
I/MotionRecognitionService(  869): setPowerConnected  = true
,I/SELinux ( 8407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,E/SELinux ( 8407): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/TimaKeyStoreProvider( 8407): TimaSignature is unavailable
,D/ActivityThread( 8407): Added TimaKeyStore provider
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 8407): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  869): Killing 7311:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/libprocessgroup(  869): failed to open /acct/uid_10050/pid_7311/cgroup.procs: No such file or directory
,I/PowerManagerService(  869): [PWL] Off : 225s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  869): !@Sync 11
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  869): waitForAlarm result :8
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 12
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  869): [PWL] Off : 275s ago
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 13
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 14
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 330s ago
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  869): !@Sync 15
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  869): stay LED for fully charged
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/bootchecker(  321): bootchecker wake up!!
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,D/BatteryService(  869): stay LED for fully charged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 16
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 390s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,E/Watchdog(  869): !@Sync 17
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  869): waitForAlarm result :8
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  869): !@Sync 18
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 455s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  869): stay LED for fully charged
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/Atfwd_Daemon(  325): Stop the daemon....
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 19
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,D/BatteryService(  869): stay LED for fully charged
I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  869): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  869): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  869): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  869): !@Sync 20
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  869): [PWL] Off : 525s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager(  869): Killing 7329:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,W/libprocessgroup(  869): failed to open /acct/uid_10057/pid_7329/cgroup.procs: No such file or directory
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 21
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 22
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 23
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 600s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 24
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 25
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 680s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 26
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,D/BatteryService(  869): stay LED for fully charged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  285): DCD ON
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 27
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  869): !@Sync 28
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,D/BatteryService(  869): stay LED for fully charged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  869): [PWL] Off : 765s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 29
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/TimaService(  869): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  869): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  869): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  869): !@Sync 30
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 31
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3244): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  869): [PWL] Off : 855s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 32
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 33
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 34
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,D/BatteryService(  869): stay LED for fully charged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 950s ago
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/Watchdog(  869): !@Sync 35
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 36
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 37
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  869): !@Sync 38
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 1050s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 39
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
E/SMD     (  285): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,D/TimaService(  869): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  869): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  869): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  869): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  869): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  869): Updating Usage Statistics in DB @ 1450234224246
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
,W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  869): ::getAppControlDB: Exception to create DB
W/System.err(  869): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  869): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  869): Done Updating Usage Statistics in DB @ 1450234224392
,E/Watchdog(  869): !@Sync 40
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 41
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  869): [PWL] Off : 1155s ago
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 42
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 43
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,I/art     (  869): Background sticky concurrent mark sweep GC freed 97918(9MB) AllocSpace objects, 366(5MB) LOS objects, 18% free, 36MB/44MB, paused 2.361ms total 133.511ms
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 44
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 45
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 1265s ago
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 46
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 47
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  869): !@Sync 48
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): stay LED for fully charged
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 49
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 1380s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  869): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  869): TimaServiceHandler.handleMessage what =1
,D/TimaService(  869): TIMA: checkEvent, operation: 50000 subject: 10000
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 50
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 51
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 52
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,E/SMD     (  285): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 53
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 1500s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 54
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 55
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 56
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  869): !@Sync 57
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  869): [PWL] Off : 1625s ago
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  869): !@Sync 58
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  869): stay LED for fully charged
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 59
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/NetworkStatsFactory(  869): UpdateStatsForKnox
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  869): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  869): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  869): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  869): !@Sync 60
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  869): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  869): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 61
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  869): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  869): [PWL] Off : 1755s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 62
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  869): Plugged
,I/MotionRecognitionService(  869): setPowerConnected  = true
,D/BatteryService(  869): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  869): !@Sync 63
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  869): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  285): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  285): DCD ON
E/SMD     (  285): DCD ON
D/AndroidRuntime( 8512): 
D/AndroidRuntime( 8512): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8512): CheckJNI is OFF
D/AndroidRuntime( 8512): setted country_code = Poland
D/AndroidRuntime( 8512): setted countryiso_code = PL
D/AndroidRuntime( 8512): setted sales_code = XEO
D/AndroidRuntime( 8512): readGMSProperty: start
D/AndroidRuntime( 8512): readGMSProperty: already setted!!
D/AndroidRuntime( 8512): readGMSProperty: end
D/AndroidRuntime( 8512): addProductProperty: start
E/AffinityControl( 8512): AffinityControl: registerfunction enter
D/AndroidRuntime( 8512): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  869): START PACKAGE DELETE: observer{1032976412}
D/PackageManager(  869): pkg{<packageName>}
D/PackageManager(  869): user{0}
D/PackageManager(  869): caller{2000}
D/PackageManager(  869): flags{3}
D/PersonaManagerService(  869): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  869): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  869): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  869): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  869): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  869): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  869): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  869): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  869): getApplicationUninstallationEnabled
D/ApplicationPolicy(  869): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  869): !@killApplicatoin: 10356, uninstall pkg
I/ActivityManager(  869): Force stopping com.test.thalitest appid=10356 user=-1: uninstall pkg
I/ActivityManager(  869): Killing 7416:com.test.thalitest/u0a356 (adj 0): stop com.test.thalitest
I/ActivityManager(  869): Killing 8063:com.samsung.android.sconnect/u0a137 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7647:com.google.android.apps.plus/u0a134 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7999:com.google.android.apps.magazines/u0a127 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7983:com.android.chrome/u0a87 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7368:com.sec.chaton/u0a85 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7968:com.sec.knox.bridge/1000 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7951:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 6959:com.osp.app.signin/u0a44 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7239:com.policydm/1000 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7933:com.sec.android.soagent/u0a36 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7904:com.samsung.klmsagent/u0a18 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7885:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7865:com.sec.android.diagmonagent/1000 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7846:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 7224:com.sec.pcw.device/1000 (adj 15): empty for 1810s
I/ActivityManager(  869): Killing 8126:com.sec.android.provider.badge/u0a77 (adj 15): empty for 1811s
I/ActivityManager(  869): Killing 7799:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): empty for 1813s
I/ActivityManager(  869): Killing 7695:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): empty for 1815s
I/ActivityManager(  869): Killing 7678:com.sec.kidsplat.installer/u0a165 (adj 15): empty for 1815s
I/ActivityManager(  869): Killing 7615:com.samsung.helphub/1000 (adj 15): empty for 1816s
I/ActivityManager(  869): Killing 7598:com.samsung.android.magazine.service/u0a117 (adj 15): empty for 1816s
I/ActivityManager(  869): Killing 7580:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): empty for 1816s
I/ActivityManager(  869): Killing 7564:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1816s
I/ActivityManager(  869): Killing 7549:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1816s
I/ActivityManager(  869): Killing 7534:com.sec.android.provider.logsprovider/u0a19 (adj 15): empty for 1816s
I/ActivityManager(  869): Killing 7478:com.sec.android.automotive.drivelink/u0a98 (adj 15): empty for 1817s
I/ActivityManager(  869): Killing 7498:com.vlingo.midas/u0a32 (adj 15): empty for 1817s
I/ActivityManager(  869): Killing 7394:com.google.android.apps.docs/u0a97 (adj 15): empty for 1817s
I/ActivityManager(  869): Killing 7350:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1819s
I/ActivityManager(  869):   Force finishing activity ActivityRecord{22e6e7d5 u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  869): Set to : 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/ProcessStatsService(  869): Prepared write state in 10ms
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/PackageSettings(  869): Skipping PackageSetting{1ef6d3e1 com.example.hello/10357} due to missing metadata
I/ActivityManager(  869): Force stopping com.test.thalitest appid=10356 user=0: pkg removed
D/ConnectivityService(  869): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
I/art     ( 1564): Explicit concurrent mark sweep GC freed 10157(690KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 686us total 26.380ms
I/art     ( 6300): Explicit concurrent mark sweep GC freed 34189(1826KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 358us total 28.665ms
I/art     ( 2493): Explicit concurrent mark sweep GC freed 27220(1675KB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 21MB/28MB, paused 685us total 46.385ms
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  869): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 1474): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/SamsungIME( 1869): mOCRHelper is null
D/ResourcesManager( 1474): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1474): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/GeofencerStateMachine( 2216): Ignoring removeGeofence because network location is disabled.
E/JavaBinder(  869): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  869): Exception when sending broadcast to ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.MainReciver}
W/BroadcastQueue(  869): android.os.TransactionTooLargeException
W/BroadcastQueue(  869): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  869): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  869): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:924)
W/BroadcastQueue(  869): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:276)
W/BroadcastQueue(  869): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1124)
W/BroadcastQueue(  869): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:180)
W/BroadcastQueue(  869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  869): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue(  869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  869): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8542): MountEmulatedStorage()
E/Zygote  ( 8542): v2
I/libpersona( 8542): KNOX_SDCARD checking this for 10018
I/libpersona( 8542): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8542 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
I/art     (  318): Explicit concurrent mark sweep GC freed 8715(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 287us total 17.928ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.846ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 8.152ms
I/art     (  869): Explicit concurrent mark sweep GC freed 45742(4MB) AllocSpace objects, 187(3MB) LOS objects, 30% free, 35MB/51MB, paused 1.882ms total 121.120ms
D/ResourcesManager(  869): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  869): WaitForGcToComplete blocked for 46.311ms for cause Explicit
I/SELinux ( 8542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/WifiService(  869): Client connection lost with reason: 4
D/TimaKeyStoreProvider( 8542): TimaSignature is unavailable
D/ActivityThread( 8542): Added TimaKeyStore provider
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Books/Books.apk
D/SecContentProvider2(  869): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  869): mCursor = null
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/SurfaceWidgetView( 1474): destroyHardwareResources():349554730
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  869): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  869): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/Launcher( 1474): onRestart, Launcher: 772222828
D/Launcher( 1474): onStart, Launcher: 772222828
D/Launcher.HomeView( 1474): onStart
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2075): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2075): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 8542): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBarManagerService(  869): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/StatusBarManagerService(  869): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/RegisteredServicesCache( 1462): empty dynamic service
D/InputMethodManagerService(  869): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/KLMS-2.4.503: ( 8542): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/ContextImpl(  869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  869): Got RemoteException sending setActive(false) notification to pid 7416 uid 10356
I/KLMS-2.4.503: ( 8542): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450234935972
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/KLMS-2.4.503: ( 8542): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8542): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService(  869): PackageReceiver onReceive()
I/HarmonyEASService(  869): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  869): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  869): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  869): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  869): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  869): uID is 10356
V/EnterpriseBillingPolicy(  869): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  869): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  869): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  869): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  869): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  869): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  869): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  869): removeObsoleteFile: deleting file=3_task.xml
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
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/BatteryService(  869): level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  869): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  869): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  869): stay LED for fully charged
D/MotionRecognitionService(  869):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  869): Plugged
I/MotionRecognitionService(  869): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/Timeline(  869): Timeline: Activity_windows_visible id: ActivityRecord{148b8e55 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1923427
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3244): Disconnected process message: 10
I/art     (  869): Explicit concurrent mark sweep GC freed 16222(867KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 35MB/51MB, paused 9.025ms total 267.912ms
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8562): MountEmulatedStorage()
E/Zygote  ( 8562): v2
I/libpersona( 8562): KNOX_SDCARD checking this for 10103
I/libpersona( 8562): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8562 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  869): Killing 8078:com.android.email/u0a162 (adj 15): empty for 1810s
I/SELinux ( 8562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8562): TimaSignature is unavailable
D/ActivityThread( 8562): Added TimaKeyStore provider
D/ResourcesManager( 8562): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/PackageManager(  869): delete codoeFile: 
D/PackageManager(  869): result of delete: 1{1032976412}
D/AndroidRuntime( 8512): Shutting down VM
D/elm:14451( 8562): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8562): ELMEngine.ELMEngine( context ).
D/elm:14451( 8562): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8562): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8562): ElmAgentService : onCreate()
D/elm:14451( 8562): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8562): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8562): MDMBridge.getInstance()
D/elm:14451( 8562): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8578): MountEmulatedStorage()
E/Zygote  ( 8578): v2
I/libpersona( 8578): KNOX_SDCARD checking this for 10016
I/libpersona( 8578): KNOX_SDCARD not a persona
D/elm:14451( 8562): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager(  869): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8578 uid=10016 gids={50016, 9997} abi=armeabi-v7a
I/SELinux ( 8578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 8562): ElmAgentService : onDestroy().
I/ActivityManager(  869): Killing 7036:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1811s
D/TimaKeyStoreProvider( 8578): TimaSignature is unavailable
D/ActivityThread( 8578): Added TimaKeyStore provider
D/ResourcesManager( 8578): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8578): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8578): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8578): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8594): MountEmulatedStorage()
E/Zygote  ( 8594): v2
I/libpersona( 8594): KNOX_SDCARD checking this for 1000
I/libpersona( 8594): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8594 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  869): Killing 8153:com.samsung.android.service.travel/u0a177 (adj 15): empty for 1811s
I/SELinux ( 8594): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8594): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8594): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8594): TimaSignature is unavailable
D/ActivityThread( 8594): Added TimaKeyStore provider
D/ResourcesManager( 8594): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8594): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8594): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8594): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 8594): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8594): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8594): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8594): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  869): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8609): MountEmulatedStorage()
E/Zygote  ( 8609): v2
I/libpersona( 8609): KNOX_SDCARD checking this for 10033
I/libpersona( 8609): KNOX_SDCARD not a persona
I/ActivityManager(  869): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8609 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  869): Killing 7128:com.android.defcontainer/u0a5 (adj 15): empty for 1810s
I/SELinux ( 8609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8609): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8609): TimaSignature is unavailable
D/ActivityThread( 8609): Added TimaKeyStore provider
D/ResourcesManager( 8609): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/ProcessStatsService(  869): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-16-40.bin
D/ResourcesManager(  869): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/FeatureConfig( 8609): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 8609): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 8609): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8609): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager(  869): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/ResourcesManager( 8609): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.

```
