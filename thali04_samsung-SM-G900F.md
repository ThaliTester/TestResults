#### Test 5635717154d1b6f_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
I/SA      ( 7142): [DM] init START
I/SA      ( 7142): [DM] This device is not a Vodafone
W/ResourceType( 7142): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7142): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7142): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7142): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7142): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7142): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7142): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 7142): [SCU] isHaveSA() - false
I/SA      ( 7142): support phone number id : false
I/SA      ( 7142): [DM] Supports Ref Jpn : true
I/SA      ( 7142): [DM] init END
I/SA      ( 7142): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
I/SA      ( 7142): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10191 extra.user_handle.:0 ]
--------- beginning of system
I/ActivityManager(  903): Killing 6112:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/Mms/FreeMessageReceiver( 5546): onReceive, action : android.intent.action.PACKAGE_ADDED
W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6112/cgroup.procs: No such file or directory
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7169): MountEmulatedStorage()
E/Zygote  ( 7169): v2
I/libpersona( 7169): KNOX_SDCARD checking this for 10050
I/libpersona( 7169): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7169 uid=10050 gids={50050, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/Mms/FreeMessageReceiverService( 5546): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5546): onHandleIntent: ACTION_PACKAGE_ADDED
I/SELinux ( 7169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7169): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7169): TimaSignature is unavailable
D/ActivityThread( 7169): Added TimaKeyStore provider
D/ResourcesManager( 7169): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 7169): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7169): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/MyFiles ( 7169): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
E/installd(  299): system dir 0 : /system/app/
E/installd(  299): system dir 1 : /system/priv-app/
E/installd(  299): system dir 2 : /vendor/app/
E/installd(  299): system dir 3 : /oem/app/
I/TactileAssist(  903): enable value -1
I/TactileAssist(  903): internal enable value -1
I/TactileAssist(  903): intensity value -1
I/TactileAssist(  903): saveAppList value true
I/TactileAssist(  903): List of disabled apps :
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
I/Icing   ( 2480): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
E/Zygote  ( 7187): MountEmulatedStorage()
E/Zygote  ( 7187): v2
I/libpersona( 7187): KNOX_SDCARD checking this for 10057
I/libpersona( 7187): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7187 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
I/SELinux ( 7187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7187): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/Icing   ( 2480): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
D/PackageManager(  903): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/TimaKeyStoreProvider( 7187): TimaSignature is unavailable
D/ActivityThread( 7187): Added TimaKeyStore provider
D/ResourcesManager( 7187): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7187): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7187): onReceive() it will make start service
D/Compatibility( 7187): onHandleIntent()
D/Compatibility( 7187): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
D/Compatibility( 7187): found: 2
I/UpdateIcingCorporaServi( 1575): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7187): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7187): skipping ResolveInfo{26622ca8 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7187): considering ResolveInfo{335863c1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/AndroidRuntime( 7184): 
D/AndroidRuntime( 7184): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Compatibility( 7187): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7187): enabling receiver ResolveInfo{334d7766 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/AndroidRuntime( 7184): CheckJNI is OFF
D/AndroidRuntime( 7184): setted country_code = Poland
D/AndroidRuntime( 7184): setted countryiso_code = PL
D/Compatibility( 7187): enabling receiver ResolveInfo{31411aa7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/AndroidRuntime( 7184): setted sales_code = XEO
D/AndroidRuntime( 7184): readGMSProperty: start
D/AndroidRuntime( 7184): readGMSProperty: already setted!!
D/AndroidRuntime( 7184): readGMSProperty: end
D/AndroidRuntime( 7184): addProductProperty: start
W/ContextImpl( 6011): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 7187): enabling receiver ResolveInfo{13016b54 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7187): enabling receiver ResolveInfo{1d467afd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7187): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ResourcesManager( 1575): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
I/UpdateIcingCorporaServi( 1575): UpdateCorporaTask done [took 69 ms] updated apps [took 69 ms] 
E/Zygote  ( 7220): MountEmulatedStorage()
E/Zygote  ( 7220): v2
I/libpersona( 7220): KNOX_SDCARD checking this for 10097
I/libpersona( 7220): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7220 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  903): Killing 6084:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##41
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
E/AffinityControl( 7184): AffinityControl: registerfunction enter
I/SELinux ( 7220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7220): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7184): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 7220): TimaSignature is unavailable
D/ActivityThread( 7220): Added TimaKeyStore provider
E/PersonaManagerService(  903): inState():  stateMachine is null !!
V/ApplicationPolicy(  903): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ResourcesManager( 7220): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/libprocessgroup(  903): failed to open /acct/uid_10035/pid_6084/cgroup.procs: No such file or directory
D/CustomFrequencyManagerService(  903): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  903): mDVFSHelper.acquire()
D/FocusedStackFrame(  903): Set to : 0
D/Launcher.HomeView( 1492): onPause
D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7184): Shutting down VM
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7237): MountEmulatedStorage()
E/Zygote  ( 7237): v2
I/libpersona( 7237): KNOX_SDCARD checking this for 10191
I/libpersona( 7237): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7237 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SELinux ( 7237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/SELinux ( 7237): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/SMD     (  291): DCD ON
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/TimaKeyStoreProvider( 7237): TimaSignature is unavailable
D/ActivityThread( 7237): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  903): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  903): Display changed displayId=0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/Launcher.HomeView( 1492): onStop
I/MicrophoneInputStream( 1575): mic_close gfk@1821a282
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2079): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2079): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2079): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2079): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2079): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 2079): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2079): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/AudioPolicyManager(  296): stopInput() input 29
D/ResourcesManager( 7237): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DocsApplication( 7220): Installing DEX configuration.
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
V/AudioPolicyManager(  296): releaseInput() 29
V/AudioPolicyManager(  296): closeInput(29)
I/HotwordRecognitionRnr( 1575): Hotword detection finished
V/audio_hw_primary(  296): in_standby: enter
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/HotwordRecognitionRnr( 1575): Stopping hotword detection.
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/SurfaceWidgetView( 1492): destroyHardwareResources():317283661
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
D/DexInstaller( 7220): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/Launcher( 1492): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1492): destroyHardwareResources():317283661
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/PackageInfoHelper( 7220): Provided clientMode=RELEASE, packageInfo=PackageInfo{35997ccb com.google.android.apps.docs}
V/audio_hw_primary(  296): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  296): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  296): disable_audio_route: reset mixer path: audio-record
D/audio_route(  296): ++++ audio_route_update_mixer ==============
D/audio_route(  296): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  296): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/audio_route(  296): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  296): disable_audio_route: exit
V/audio_hw_primary(  296): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  296): ++++ audio_route_update_mixer ==============
D/audio_route(  296): Setting mixer control: DEC2 Volume
D/audio_route(  296): Setting mixer control: value: 0
D/audio_route(  296): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  296): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  296): Setting mixer control: value: 0
D/TAG     ( 7220): onCreate()
D/audio_route(  296): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  296): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  296): stop_input_stream: exit: status(0)
V/audio_hw_primary(  296): in_standby: exit:  status(0)
V/audio_hw_primary(  296): adev_close_input_stream
V/audio_hw_primary(  296): in_standby: enter
V/audio_hw_primary(  296): in_standby: exit:  status(0)
E/audio_hw_primary(  296): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  296): releaseInput() exit
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/CrossAppStateProvider( 7220): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/WebViewFactory( 7237): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7237): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/LibraryLoader( 7237): Loading: webviewchromium
,I/LibraryLoader( 7237): Time to load native libraries: 1 ms (timestamps 6851-6852)
,I/LibraryLoader( 7237): Expected native library version number "",actual native library version number ""
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,V/WebViewChromiumFactoryProvider( 7237): Binding Chromium to main looper Looper (main, tid 1) {13016b54}
,I/LibraryLoader( 7237): Expected native library version number "",actual native library version number ""
I/chromium( 7237): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7237): Initializing chromium process, renderers=0
,W/art     ( 7237): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,W/chromium( 7237): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
I/chromium( 7237): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/chromium( 7237): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7237): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7237): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7237): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7237): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7237): Remote Branch: 
I/Adreno-EGL( 7237): Local Patches: 
I/Adreno-EGL( 7237): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,W/chromium( 7237): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7237): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,W/art     ( 7237): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7237): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SystemWebViewEngine( 7237): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/art     ( 7237): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7237): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/Activity( 7237): performCreate Call secproduct feature valuefalse
D/Activity( 7237): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
D/OpenGLRenderer( 7237): Render dirty regions requested: true
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ActivityManager(  903): post active user change for 0
D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/OpenGLRenderer( 7237): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/OpenGLRenderer( 7237): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/OpenGLRenderer( 7237): Enabling debug mode 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +596ms
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/Timeline( 7237): Timeline: Activity_idle id: android.os.BinderProxy@2cffb97 time:107214
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
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
D/JsMessageQueue( 7237): Set native->JS mode to OnlineEventsBridgeMode
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
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  257): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  257): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/CustomFrequencyManagerService(  903): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  903): mDVFSHelper.release()
I/Timeline(  903): Timeline: Activity_windows_visible id: ActivityRecord{39154b8a u0 com.test.thalitest/.MainActivity t9} time:107461
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/CustomFrequencyManagerService(  903): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  pkgName : ACTIVITY_RESUME_BOOSTER@10
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
E/Adreno-ES20( 7237): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7237): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/chromium( 7237): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7237): 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/jxcore_app_log( 7237): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259431936
D/JX-Cordova( 7237): jxcore cordova android initializing
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
D/CustomFrequencyManagerService(  903): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  tag : ACTIVITY_RESUME_BOOSTER@10
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 7220): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 7300): MountEmulatedStorage()
E/Zygote  ( 7300): v2
I/libpersona( 7300): KNOX_SDCARD checking this for 10098
I/libpersona( 7300): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7300 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/SELinux ( 7300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7300): TimaSignature is unavailable
D/ActivityThread( 7300): Added TimaKeyStore provider
D/ResourcesManager( 7300): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager( 7300): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
E/[CarMode]( 7300): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7300): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7300): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7320): MountEmulatedStorage()
E/Zygote  ( 7320): v2
I/libpersona( 7320): KNOX_SDCARD checking this for 10032
I/libpersona( 7320): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7320 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7320): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
D/TimaKeyStoreProvider( 7320): TimaSignature is unavailable
D/ActivityThread( 7320): Added TimaKeyStore provider
D/ResourcesManager( 7320): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7320): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/GAV2    ( 7220): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  903): Killing 6131:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
I/System.out( 7320): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7320): Inside WakeupProvider
E/DatabaseUtils( 7320): Writing exception to parcel
E/DatabaseUtils( 7320): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7320): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7320): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7320): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7320): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7320): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7320): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7320): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7320): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7320): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7320): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7300): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/libprocessgroup(  903): failed to open /acct/uid_10037/pid_6131/cgroup.procs: No such file or directory
I/VlingoApplication( 7320): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7300): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7300): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7300): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7300): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7300): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7300): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7300): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7300): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7300): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7300): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7300): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7300): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7300): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7300): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7300): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7300): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7300): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7300): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7300): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7300): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7300): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7300): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7300): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7300): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7300): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7300): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils( 7320): Writing exception to parcel
E/DatabaseUtils( 7320): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7320): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7320): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7320): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7320): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7320): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7320): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7320): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7320): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7320): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7320): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7300): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7300): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7300): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7300): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7300): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7300): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7300): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7300): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7300): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7300): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7300): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7300): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7300): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7300): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7300): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7300): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7300): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7300): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7300): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7300): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7300): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7300): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7300): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7300): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7300): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/VlingoAndroidCore( 7320): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
E/[CarMode]( 7300): [DLApplication]-Init Called!:false
E/[CarMode]( 7300): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7300): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7300): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7300): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7300): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7300): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7300): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7300): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7300): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7300): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7300): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7300): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7300): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7300): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7300): ### com.android.internal.os.ZygoteInit::main(1194)
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
I/MessageDataHandler( 7300): initialize
D/[CarModeFW]( 7300): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7300): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7300): CDH-buildContactCacheWireFrame : cur len =0
D/VlingoApplication( 7320): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/[CarModeFW]( 7300): CDH-ContactDataHandler initiazlieCaches time : 17
D/[CarModeFW]( 7300): DrivingManager-initialize...
D/[CarModeFW]( 7300): CDH-initiazlieCaches : end sync
D/VlingoApplication( 7320): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/SensorService(  903): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  903): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  903): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
I/MediaPlayer( 7300): Need to enable context aware info
V/MediaPlayer-JNI( 7300): native_setup
V/MediaPlayer( 7300): constructor
V/MediaPlayer( 7300): setListener
E/MediaPlayer-JNI( 7300): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7300): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7300): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7300): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarMode]( 7300): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1453132611677
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1453132611678
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1453132611678
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1453132611678
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1453132611678
I/[CarMode]( 7300): [LogNotNull]-Package name is: com.google.android.apps.maps
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1453132611686
D/TP/SmsProvider( 1478): query,matched:2, calling pid = 7300
D/TP/SmsProvider( 1478): query,matched:2, calling pid = 7300
D/TP/SmsProvider( 1478): match 2:Elapsed time : 1.026 ms
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1478): match 2:Elapsed time : 1.908 ms
E/Zygote  ( 7353): MountEmulatedStorage()
I/libpersona( 7353): KNOX_SDCARD checking this for 10003
E/Zygote  ( 7353): v2
I/libpersona( 7353): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7353 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/[CarMode]( 7300): [DLApplication]-Init End!:true
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
I/SELinux ( 7353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[CarModeFW]( 7300): CDH-buildContactCacheWireFrame : cur len =0
D/MessageDataHandler( 7300):  getInboxList smsCursor : 93
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7369): MountEmulatedStorage()
E/Zygote  ( 7369): v2
I/libpersona( 7369): KNOX_SDCARD checking this for 10019
I/libpersona( 7369): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 7353): TimaSignature is unavailable
D/ActivityThread( 7353): Added TimaKeyStore provider
I/ActivityManager(  903): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7369 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/art     (  321): Explicit concurrent mark sweep GC freed 8737(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 332us total 12.355ms
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 8.492ms
I/WifiStateMachine(  903): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  903): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  903): CMD_RSSI_POLL : out!
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 8.350ms
I/SELinux ( 7369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarMode]( 7300): [DLApplication]-GooglePlayServices SUCCESS.
E/SELinux ( 7369): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/[CarModeFW]( 7300): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsProvider( 1478): Query uri=content://mms, match=0, calling pid = 7300
,D/TP/MmsProvider( 1478): Query uri=content://mms/inbox, match=2, calling pid = 7300
,D/[CarModeFW]( 7300): RecommendHandler-selection = type = '3'
,E/[CarMode]( 7300): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/MessageDataHandler( 7300):  getInboxList mmsCursor : 79
,I/MessageDataHandler( 7300): getUnreadMessageCount :0
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 176
D/[CarModeFW]( 7300): CDH-buildContactCacheWireFrame : cur len =0
I/UpdateManagerReceiver( 7300): Intent : android.intent.action.PACKAGE_ADDEDMon Jan 18 16:56:51 GMT+01:00 2016
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/MessageDataHandler( 7300):  getInboxList mms,sms cursor join : 12
D/ResourcesManager( 7353): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/TimaKeyStoreProvider( 7369): TimaSignature is unavailable
D/ActivityThread( 7369): Added TimaKeyStore provider
E/Zygote  ( 7384): MountEmulatedStorage()
I/libpersona( 7384): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7384): v2
I/libpersona( 7384): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7384 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/[CarModeFW]( 7300): RecommendHandler-selection = type = '3'
,I/SELinux ( 7384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7384): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Killing 6150:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##41
,D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 7300
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 1.893 ms
,D/[CarModeFW]( 7300): PushMessageService-onCreate
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/ActivityManager(  903): Killing 4678:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,I/ActivityManager(  903): Killing 6507:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##42
,I/ActivityManager(  903): Killing 6028:com.google.android.talk/u0a116 (adj 15): bgCount ##43
,D/TimaKeyStoreProvider( 7384): TimaSignature is unavailable
D/ActivityThread( 7384): Added TimaKeyStore provider
,D/ResourcesManager( 7369): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/UserAnalysis.PlaceProvider( 7353): PlaceProvider onCreate()
,D/TP/MmsSmsProvider( 1478): query,matched:13, calling pid = 7300
,D/TP/MmsSmsProvider( 1478): match 13:Elapsed time : 1.500 ms
,D/[CarModeFW]( 7300): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7300): PushMessageService-registerPushMessageServiceListener
,D/MessageDataHandler( 7300):  getInboxList address cursor : 16
,D/ResourcesManager( 7384): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 7300
,V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 1.200 ms
,D/MessageDataHandler( 7300):  getInboxList thread cursor : 8
,D/MessageDataHandler( 7300):  thread, addr result: 1
,I/[CarModeFW]( 7300): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 315
I/[CarModeFW]( 7300): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 317
,W/ContextImpl( 7384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7399): MountEmulatedStorage()
E/Zygote  ( 7399): v2
I/libpersona( 7399): KNOX_SDCARD checking this for 10111
I/libpersona( 7399): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7399 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecureDbManager( 7353): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7353): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7353): Create SecureDbHelper
,I/SELinux ( 7399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7384): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/TimaKeyStoreProvider( 7399): TimaSignature is unavailable
,D/ActivityThread( 7399): Added TimaKeyStore provider
,E/FilterInstaller( 7384): There is no requred permission
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/ActivityManager(  903): Killing 5771:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,I/art     (  903): Explicit concurrent mark sweep GC freed 247454(16MB) AllocSpace objects, 3(4MB) LOS objects, 30% free, 35MB/51MB, paused 1.392ms total 111.177ms
,D/IntelligenceServiceApplication( 7353): onCreate()
,D/ResourcesManager( 7399): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/SQLiteSecureOpenHelper( 7353): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7353): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7353): Open Place.db in secure mode
,I/[CarModeFW]( 7300): -[snowdeer] Rec : Missed Call : 332
,D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 542
,I/[CarModeFW]( 7300): -[snowdeer] Rec : Favorite : 10
,I/SQLiteSecureOpenHelper( 7353): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7353): ...getDatabaseLocked(b,b,pwd)
,I/[CarModeFW]( 7300): -[snowdeer] Rec : CallLog : 8
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/PackageIntentReceiver( 7399): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7399): Not GearManger package! 
,E/Zygote  ( 7416): MountEmulatedStorage()
E/Zygote  ( 7416): v2
I/libpersona( 7416): KNOX_SDCARD checking this for 10045
I/libpersona( 7416): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7416 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7422): MountEmulatedStorage()
E/Zygote  ( 7422): v2
I/libpersona( 7422): KNOX_SDCARD checking this for 10117
I/libpersona( 7422): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7422 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 5993:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,I/SELinux ( 7416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarModeFW]( 7300): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7300): MyPlaceProvider-=============
E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/[CarModeFW]( 7300): MyPlaceProvider-=============
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/[CarModeFW]( 7300): MyPlaceProvider-=============
D/[CarModeFW]( 7300): MyPlaceProvider-=============
D/[CarModeFW]( 7300): MyPlaceProvider----End print all data in content provider---
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
D/[CarModeFW]( 7300): MyPlaceProvider-==============
D/[CarModeFW]( 7300): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7300): MyPlaceProvider-==============
D/[CarModeFW]( 7300): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7300): MyPlaceProvider-==============
D/[CarModeFW]( 7300): MyPlaceProvider-latitude is not valid
,I/SELinux ( 7422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/SELinux ( 7416): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SELinux ( 7422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 647
E/SELinux ( 7422): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  903): failed to open /acct/uid_10037/pid_6150/cgroup.procs: No such file or directory
,D/[CarMode]( 7300): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@259ce5aa, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ced6d958] LOCATIONS
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6507/cgroup.procs: No such file or directory
,W/libprocessgroup(  903): failed to open /acct/uid_10045/pid_4678/cgroup.procs: No such file or directory
,W/libprocessgroup(  903): failed to open /acct/uid_10116/pid_6028/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7422): TimaSignature is unavailable
D/TimaKeyStoreProvider( 7416): TimaSignature is unavailable
,D/ActivityThread( 7416): Added TimaKeyStore provider
D/ActivityThread( 7422): Added TimaKeyStore provider
,I/ActivityManager(  903): Killing 5954:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,D/ResourcesManager( 7416): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_5771/cgroup.procs: No such file or directory
,D/ResourcesManager( 7422): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
W/ResourcesManager( 7416): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 7422): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MagazineService Version( 7422): Magazine-Administrator: 11
,D/MagazineService Version( 7422): Magazine-Provider: 14
,D/MagazineService Version( 7422): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7422): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7422): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2( 7416): CalendarProvider2.onCreate() called
,I/MagazineService::MagazineService( 7422): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,W/libprocessgroup(  903): failed to open /acct/uid_10167/pid_5993/cgroup.procs: No such file or directory
,E/Zygote  ( 7447): MountEmulatedStorage()
E/Zygote  ( 7447): v2
I/libpersona( 7447): KNOX_SDCARD checking this for 1000
I/libpersona( 7447): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7447 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 7237): Initializing JXcore engine
,W/jxcore-log( 7237): JXcore engine is ready
,D/MagazineService::MagazineService( 7422): [onHandleIntent] Send broadcast to (com.test.thalitest).
,W/jxcore-log( 7237): Starting JXcore engine
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/SELinux ( 7447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  903): failed to open /acct/uid_10113/pid_5954/cgroup.procs: No such file or directory
,I/SELinux ( 7447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Killing 6201:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7447): TimaSignature is unavailable
D/ActivityThread( 7447): Added TimaKeyStore provider
,D/ResourcesManager( 7447): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/auditd  ( 2174): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  903): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  903): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/libprocessgroup(  903): failed to open /acct/uid_10004/pid_6201/cgroup.procs: No such file or directory
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7463): MountEmulatedStorage()
E/Zygote  ( 7463): v2
I/libpersona( 7463): KNOX_SDCARD checking this for 1000
I/libpersona( 7463): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7463 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6263:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,W/jxcore-log( 7237): Platform android
W/jxcore-log( 7237): 
,W/jxcore-log( 7237): Process ARCH arm
W/jxcore-log( 7237): 
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/SELinux ( 7463): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7463): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7463): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7463): TimaSignature is unavailable
,D/ActivityThread( 7463): Added TimaKeyStore provider
,I/System.out( 7320): INFO:Resource not found:/Common.properties Using default values
,D/ResourcesManager( 7463): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10043/pid_6263/cgroup.procs: No such file or directory
,I/[CarModeFW]( 7300): -[snowdeer] Rec : Schedule : 488
,I/[CarModeFW]( 7300): -[snowdeer] Rec : During DL app : 2
,I/[CarModeFW]( 7300): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7300): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7300): -[snowdeer] Rec : getContactListFromHashMap - core : 1
I/[CarModeFW]( 7300): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7300): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7300): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 1048
,I/[CarModeFW]( 7300): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7300): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7300): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7300): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 1048
,D/AcmsPackageEventListener( 7463): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7463): Enter Oncreate
,D/AcmsServiceMonitor( 7463): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7463): creating AcmsCore
D/AcmsCore( 7463): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7463): AcmsCore
,D/AcmsCore( 7463): init
D/AcmsCore( 7463): Looper handler is not null
D/AcmsCore( 7463): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7463): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7463): Incrementing - Counter value: 1
D/AcmsCore( 7463): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 7463): onStartCommand
,D/AcmsCertificateMngr( 7463): AcmsCertificateMngr
D/AcmsRevocationMngr( 7463): AcmsRevocationMngr
,D/AcmsService( 7463): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7463): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7463): Incrementing - Counter value: 2
D/AcmsService( 7463): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7463): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7463): Inside handle Intent
D/AcmsService( 7463): App added - package name: com.test.thalitest
D/AcmsCore( 7463): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7463): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7463): Incrementing - Counter value: 3
D/AcmsCore( 7463): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7463): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7463): Decrementing - Counter value: 2
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7485): MountEmulatedStorage()
E/Zygote  ( 7485): v2
I/libpersona( 7485): KNOX_SDCARD checking this for 10165
I/libpersona( 7485): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7485 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/SELinux ( 7485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7485): TimaSignature is unavailable
,D/ActivityThread( 7485): Added TimaKeyStore provider
,E/SMD     (  291): DCD ON
,D/ResourcesManager( 7485): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7485): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7485): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7500): MountEmulatedStorage()
E/Zygote  ( 7500): v2
I/libpersona( 7500): KNOX_SDCARD checking this for 10169
I/libpersona( 7500): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7500 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,I/SELinux ( 7500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7500): TimaSignature is unavailable
,D/ActivityThread( 7500): Added TimaKeyStore provider
,D/ResourcesManager( 7500): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7500): (284) automatic index on shooting_modes(title_id)
,D/Finsky  ( 6449): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  903): Killing 6167:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2480): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2480): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2480): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2480): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  903): failed to open /acct/uid_10125/pid_6167/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2480): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2480): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2480): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/jxcore-log( 7237): JXcore Cordova bridge is ready!
I/jxcore-log( 7237): 
,W/jxcore-log( 7237): JXcore engine is started
,I/Choreographer( 7237): Skipped 148 frames!  The application may be doing too much work on its main thread.
,D/AsyncTaskServiceImpl( 2480): Submit a task: k
,D/ChimeraCfgMgr( 2480): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2480): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2480): Processing package: com.test.thalitest
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/GassUtils( 2480): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
,E/Zygote  ( 7525): MountEmulatedStorage()
I/libpersona( 7525): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7525): v2
I/libpersona( 7525): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7525 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/k       ( 2480): Found info for package com.test.thalitest in db.
,I/SELinux ( 7525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7525): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7525): TimaSignature is unavailable
,D/ActivityThread( 7525): Added TimaKeyStore provider
,W/BaseAppContext( 2480): Using Auth Proxy for data requests.
W/BaseAppContext( 2480): Using Auth Proxy for data requests.
,D/ResourcesManager( 7525): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/jxcore-log( 7237): Toggling radios to true
I/jxcore-log( 7237): 
,D/BluetoothAdapter( 7237): enable()
,D/BluetoothAdapter( 7237): enable(): BT is already enabled..!
,D/WifiService(  903): New client listening to asynchronous messages
,I/WifiManager( 7237): packageName : com.test.thalitest
,D/SecContentProvider(  903): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  903): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  903): mCursor = null
,D/WifiService(  903): setWifiEnabled: true pid=7237, uid=10191
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  903): Permission Denial: getCurrentUser() from pid=7237, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/BaseAppContext( 2480): Using Auth Proxy for data requests.
,W/WifiService(  903): Failed getting userId using ActivityManagerNative
W/WifiService(  903): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7237, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  903): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  903): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  903): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  903): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  903): name = wifi_on
,I/WifiService(  903): disconnect: pid=7237, uid=10191
,I/wpa_supplicant( 1284): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7237): Radios toggled
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): My device name is: samsung-SM-G900F
I/jxcore-log( 7237): 
,W/BaseAppContext( 2480): Using Auth Proxy for data requests.
,W/BaseAppContext( 2480): Using Auth Proxy for data requests.
I/wpa_supplicant( 1284): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,W/BaseAppContext( 2480): Using Auth Proxy for data requests.
,I/wpa_supplicant( 1284): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1284): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  903): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1284): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1284): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1284): Disconnected - do not scan
I/wpa_supplicant( 1284): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
,D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,E/WifiStateMachine(  903): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  903): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  903): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/BaseAppContext( 2480): Using Auth Proxy for data requests.
,E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  903): InactiveState{ what=143375 }
D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,D/CommandListener(  286): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2251): Read error: ssl=0xb4e64a00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  903): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  903): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1284): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1284): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1284): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1284): First Scan Start
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
V/NativeCrypto( 2251): SSL shutdown failed: ssl=0xb4e64a00: I/O error during system call, Broken pipe
E/WifiStateMachine(  903): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1284): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  903): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/WifiP2pService(  903): InactiveState{ what=143375 }
D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Validated
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  286): Clearing all IP addresses on wlan0
,D/ConnectivityService(  903): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  903): calling update connectivity
D/EntConnectivity(  903): Not allowed due to - mEnabled false
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  903): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/ActivityManager(  903): Killing 6717:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524292
,D/ConnectivityService(  903): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  903): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Disconnected - quitting
D/ConnectivityService(  903): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2480): CM callback handler got msg 524292
,D/ConnectivityService(  903): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  903): updateConfiguredNetworkExpiration - currTime: 1453132613667
,D/TelephonyNetworkFactory( 1478): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  903): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/CSLegacyTypeTracker(  903): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/CSLegacyTypeTracker(  903): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine(  903): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  903): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  903): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  903): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  903): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  903): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,V/NetworkStats(  903): updateIfacesLocked()
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  903): UpdateStatsForKnox
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  903): setDetailed state send new extra info"NG700"
,E/ConnectivityService(  903): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  903): performPollLocked() took 5ms
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
E/ConnectivityService(  903): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,V/TaskCloserActivity( 5788): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/CalendarProvider2( 7416): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  903): Killing 5885:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/BootupListener( 1478): ACTION_DRIVELINK
,D/SettingsProvider(  903): name = drivelink_navigation
D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 1001
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  903): ret = -1
,D/BootupListener( 1478): NAVI : com.google.android.apps.maps
D/SettingsProvider(  903): name = internet_call_settings_visibility
D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 1001
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  903): ret = -1
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,E/Zygote  ( 7553): MountEmulatedStorage()
E/Zygote  ( 7553): v2
I/libpersona( 7553): KNOX_SDCARD checking this for 1000
I/libpersona( 7553): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,I/SELinux ( 7553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
E/SELinux ( 7553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
W/libprocessgroup(  903): failed to open /acct/uid_10011/pid_6717/cgroup.procs: No such file or directory
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/TimaKeyStoreProvider( 7553): TimaSignature is unavailable
,D/ActivityThread( 7553): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10093/pid_5885/cgroup.procs: No such file or directory
,D/ResourcesManager( 7553): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,D/SecurityLogAgent( 7553):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7553):  SeDenialReceiver : File path = null
,I/ActivityManager(  903): Killing 5904:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
,I/Hs20UtilService( 1315): Starting #6
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1315): Starting #7
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7576): MountEmulatedStorage()
I/libpersona( 7576): KNOX_SDCARD checking this for 10148
E/Zygote  ( 7576): v2
I/libpersona( 7576): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7576 uid=10148 gids={50148, 9997} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 291us total 13.268ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.778ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 268us total 8.208ms
,I/SELinux ( 7576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7576): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  903): failed to open /acct/uid_10102/pid_5904/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7576): TimaSignature is unavailable
,D/ActivityThread( 7576): Added TimaKeyStore provider
,D/ResourcesManager( 7576): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7576): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7576): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 1 -> 1
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7591): MountEmulatedStorage()
E/Zygote  ( 7591): v2
I/libpersona( 7591): KNOX_SDCARD checking this for 10149
I/libpersona( 7591): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7591 uid=10149 gids={50149, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 5645:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,D/PowerManagerService(  903): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  903): Nap time (uid 1000)...
I/PowerManagerService(  903): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  903): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  903): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/InputManager-JNI(  903): setDeviceInteractive: 0
D/PowerManagerService(  903): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  903): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  903): handleSandman : startDream()
,E/PowerManagerService(  903): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  903): Sleeping (uid 1000)...
D/PowerManagerService(  903): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  903): [input device light] setInputDeviceLightOn is called : 0
D/InputManager-JNI(  903): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  903): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  903): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/InputManager-JNI(  903): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  903): 	.unregisterCallback : 1, client=
D/SContextService(  903): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3fc606e7, Service = Auto Rotation, used = 1
,W/CAE     (  903): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  903): stop(ContextProvider.java:149)
,V/CAE     (  903): clear(AutoRotationRunner.java:182)
V/CAE     (  903): disable(AutoRotationRunner.java:171)
,I/CAE     (  903): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  903): SendSensorHubData: send data = -78, 7, 0, 0
,W/art     ( 2480): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 153.776ms
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/SELinux ( 7591): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7591): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7591): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SurfaceFlinger(  257): id=16 createSurf (1080x1920),2 flag=404, ColorFade
,D/Sensorhubs(  305): sendContextData: -78, 7, 0, 0
,D/CAE     (  903): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  903): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/TimaKeyStoreProvider( 7591): TimaSignature is unavailable
,D/ActivityThread( 7591): Added TimaKeyStore provider
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/FactoryTest( 6529): Not factory mode
D/FactoryTest( 6529): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6529): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6529): still no open session command from host, so toast
,W/ContextImpl( 6529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6529): Timeline: Activity_launch_request id:com.android.settings time:110998
,E/PersonaManagerService(  903): inState():  stateMachine is null !!
,V/ApplicationPolicy(  903): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/libprocessgroup(  903): failed to open /acct/uid_10112/pid_5645/cgroup.procs: No such file or directory
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/CAE     (  903): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  903): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  903): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  903): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  903): removeSContextService() : service = Auto Rotation
D/SContextService(  903): ===== SContext Service List =====
D/SContextManager(  903):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@305343c1, service=Auto Rotation
,D/CustomFrequencyManagerService(  903): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  903): mDVFSHelper.acquire()
,D/KeyguardViewMediator( 1184): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1184): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1184): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1184): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/KeyguardViewMediator( 1184): timeout : 5000
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager( 7591): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/MTPRx   ( 6529): started activity for popup
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/KeyguardViewMediator( 1184): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1184): handleNotifyScreenOff
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  903): MasterInitialState.processMessage what=3
,I/CLocInfoService(  903): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  903): CLoinfo wifi false
,D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,I/ApplicationPolicy(  903): updateDataUsageMap
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,D/DisplayPowerController(  903): ColorFade: onAnimationStart
D/DisplayPowerController(  903): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  903): getFinalBrightness : 8 -> 0
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/accuweather( 2079): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  903): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 903) 
,D/LightsService(  903): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  903): [SvcLED]  onSensorChanged::light value = 0
,D/DisplayPowerController(  903): getFinalBrightness : 8 -> 0
,D/lights  (  903): lcd : 0 +
I/DBG_DM  ( 3669): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/SensorManager(  903): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  903): turn on LED for fully charged
D/SensorManager(  903): unregisterListener ::   
,D/lights  (  903): lcd : 0 -
,D/lights  (  903): led_pattern : 5 +
,I/CAE     (  903): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  903): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  903): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  903): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  305): sendContextData: -76, 13, -46, 0
,I/CAE     (  903): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 15, 56, 54,
D/SensorHubManager(  903): SendSensorHubData: send data = -63, 14, 15, 56, 54
,D/Sensorhubs(  305): sendContextData: -63, 14, 15, 56, 54
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/lights  (  903): led_pattern : 5 -
,D/LightsService(  903): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  903):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  903): backgroundScan enabled=false startBackgroundScanIfNeeded:true
,E/WifiStateMachine(  903): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  903): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  903): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  903): do suspend true
,D/NotificationService(  903): ACTION_SCREEN_OFF
D/LightsService(  903): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 903) 
D/LightsService(  903): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService(  903): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  903): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  903): unregisterListener ::   
D/LightsService(  903): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 3669): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=off
V/voice   (  296): voice_set_parameters: enter: screen_state=off
V/voice   (  296): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  296): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  296): adev_set_parameters: exit
,I/SQLiteSecureOpenHelper( 3467): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3467): getDatabaseLocked(b,b,pwd)...
,W/ResourcesManager( 7591): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7591): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/SLocation(  903): No Active Data Connection
,W/ResourcesManager( 7591): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SecExternalDisplayIntents_Java(  903): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  903): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  903): Bridge Server is not available
,D/VolumePanel( 1184): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1184): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1184): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1184): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  903): ACTION_SCREEN_OFF onReceive
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PersonaManagerServiceHandler(  903): MSG_ACTION_SCREEN_OFF called
,E/LightSensor(  903): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
D/DisplayPowerController(  903): getFinalBrightness : 8 -> 0
,I/Icing   ( 2480): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,D/NfcService( 1472): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1184):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1184): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1184): dismissHelpPopup 
,D/accuweather( 2079): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2079): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2079): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  903): !@ ColorFade entry
,D/DisplayPowerController(  903): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  903): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  903): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  903): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  903): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  903): Light old sensor_state 513, new sensor_state : 1 en : 0
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SensorManager(  903): unregisterListener ::   
E/Sensors (  903): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/SensorManager(  903): unregisterListener ::   
,D/DisplayPowerController(  903): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  903): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  903): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/ActivityManager(  903): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
,V/ActivityManager(  903): Display changed displayId=0
,W/ActivityManager(  903): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  903): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  903): SIOP:: AP = 400, PST = 362, CUR = 450
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/StatusBar.NetworkController( 1184): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/PCWCLIENTTRACE_PushUtil( 7076): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7076): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7076): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7076): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7076): noConnectivity : true
,E/Zygote  ( 7617): MountEmulatedStorage()
E/Zygote  ( 7617): v2
I/libpersona( 7617): KNOX_SDCARD checking this for 10125
I/libpersona( 7617): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7617 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 2480): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/wpa_supplicant( 1284): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1284): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1284): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1284): wlan0: State: SCANNING -> ASSOCIATING
I/rmt_storage(  282): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  282): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  282): wakelock acquired: 1, error no: 42
I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  903): [1,453,132,614,720 ms] noteScanEnd no scan source
,E/WifiStateMachine(  903): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2ecc18f3 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  903): setDetailed state send new extra info0x
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,I/Icing   ( 2480): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/SELinux ( 7617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7617): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  282): 
,I/rmt_storage(  282): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/CLocInfoService(  903): External Intent Received android.net.wifi.SCAN_RESULTS
,I/wpa_supplicant( 1284): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1284): Associated with C0.AA.48
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{39154b8a u0 com.test.thalitest/.MainActivity t9}
,V/ActivityManager(  903): Display changed displayId=0
,I/wpa_supplicant( 1284): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  903): setDetailed state send new extra info"NG700"
,D/TimaKeyStoreProvider( 7617): TimaSignature is unavailable
,D/ActivityThread( 7617): Added TimaKeyStore provider
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,I/wpa_supplicant( 1284): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1284): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1284): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1284): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1284): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1284): Blacklist: Clear (temp) 
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/SurfaceControl(  903): Excessive delay in setPowerMode(): 275ms
D/PowerManagerService(  903): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  903): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  903): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  903): Got set_interactive hint
,I/PowerManagerService(  903): [PWL] Off : 0s ago
I/PowerManagerService(  903): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  903): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  903): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=2480, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=1530)
I/PowerManagerService(  903): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=903, ws=null) (elapsedTime=1168)
I/PowerManagerService(  903): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=903, ws=null) (elapsedTime=561)
I/PowerManagerService(  903): [PWL]       PARTIAL_WAKE_LOCK              'StartingAlertService' (uid=10149, pid=7591, ws=null) (elapsedTime=208)
I/PowerManagerService(  903): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  903): [PWL]     mDisplayReady : false
D/DisplayPowerController(  903): getFinalBrightness : 0 -> 0
D/PowerManagerService(  903): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  903): [PWL] sb release: PowerManagerService.Display
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SQLiteSecureOpenHelper( 3467): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3467): getDatabaseLocked(b,b,pwd)...
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  903): Network connection established
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiNative-HAL(  903): callSECApiVoid - ID [50]
,E/WifiStateMachine(  903): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  903): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  903): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  903): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  903): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  903): Got NetworkAgent Messenger
D/ConnectivityService(  903): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  903): NetworkAgent connected
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7617): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/WifiStateMachine(  903): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  903): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  903): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  286): Setting iface cfg
E/WifiStateMachine(  903): Start Dhcp Watchdog 2
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,D/ResourcesManager( 6529): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/ResourcesManager( 6529): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6529): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6529): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6529): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/ResourcesManager( 6529): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6529): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6529): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/art     ( 2480): Verification of boolean com.google.android.gms.games.broker.VideoAgent.handleMessage(android.os.Message) took 137.260ms
,E/SettingsReceiverActivity( 6529): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,I/ActivityManager(  903): Killing 5924:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  903): do suspend false
V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  903): InactiveState{ what=143375 }
D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/SecContentProvider2(  903): mCursor = null
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6529): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6529): dev.kiessupport is : TRUE
,D/Activity( 6529): performCreate Call secproduct feature valuefalse
D/Activity( 6529): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,W/libprocessgroup(  903): failed to open /acct/uid_10153/pid_5924/cgroup.procs: No such file or directory
,W/art     ( 2480): Verification of int com.google.android.gms.games.broker.VideoAgent.launchGameForRecording(com.google.android.gms.games.broker.GamesClientContext, java.lang.String, com.google.android.gms.games.video.VideoConfiguration, com.google.android.gms.games.Game, boolean) took 215.205ms
,W/SQLiteConnectionPool( 2480): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ChimeraCfgMgr( 2480): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2480): Module APK com.google.android.play.games already loaded
,I/MusicStore( 7617): Database version: 104
,D/ResourcesManager( 7617): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7617): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7617): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/dhcpcd  ( 7646): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7646): version 5.5.6 starting
,E/dhcpcd  ( 7646): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,V/JNIHelp ( 7617): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dhcpcd  ( 7646): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7646): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7646): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7646): bssid match
,I/dhcpcd  ( 7646): wlan0: rebinding lease of 192.168.1.136
,W/ActivityThread( 7617): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7617): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@167bfa26: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7617): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7617): GMSCore installation verified
,I/ConfigStore( 7617): Config Database version: 1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7617): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7617): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7617): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  296): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  903): getStreamVolume 3 index 0
,I/MediaRouter( 7617): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7656): MountEmulatedStorage()
E/Zygote  ( 7656): v2
I/libpersona( 7656): KNOX_SDCARD checking this for 10002
I/libpersona( 7656): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7656 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7617): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7656): TimaSignature is unavailable
,D/ActivityThread( 7656): Added TimaKeyStore provider
,I/ActivityManager(  903): Killing 6898:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{39154b8a u0 com.test.thalitest/.MainActivity t9}
,D/ResourcesManager( 7656): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  903): Killing 6957:com.sec.enterprise.knox.cloudmdm.smdms/u0a178 (adj 15): bgCount ##41
,W/libprocessgroup(  903): failed to open /acct/uid_10070/pid_6898/cgroup.procs: No such file or directory
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7674): MountEmulatedStorage()
E/Zygote  ( 7674): v2
I/libpersona( 7674): KNOX_SDCARD checking this for 1000
I/libpersona( 7674): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7674 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  903): Explicit concurrent mark sweep GC freed 57802(3MB) AllocSpace objects, 5(2MB) LOS objects, 30% free, 35MB/51MB, paused 1.578ms total 95.353ms
,I/SELinux ( 7674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AcmsKeyStoreHelper( 7463):  getKeyStoreForApplication Enter
,D/TimaKeyStoreProvider( 7674): TimaSignature is unavailable
,D/ActivityThread( 7674): Added TimaKeyStore provider
,D/ResourcesManager( 7674): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10178/pid_6957/cgroup.procs: No such file or directory
I/AcmsKeyStoreHelper( 7463): Key Store exist
I/AcmsKeyStoreHelper( 7463): Hence loading the keystore file
,I/DIAGMON_AGENT( 7674): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7674): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/AcmsKeyStoreHelper( 7463):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 7463): getKeyStoreForApplication success 
D/AcmsCore( 7463): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7463): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7463): Decrementing - Counter value: 1
,D/AcmsCore( 7463): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 7463): This is NOT a valid MirrorLink app
D/AcmsCore( 7463): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
,D/AcmsServiceMonitor( 7463): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7463): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7463): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7463): getSvcCounter - Counter value: 0
,D/AcmsService( 7463): Enter onDestroy
I/AcmsService( 7463): cleanUp(): inside service clean up
D/AcmsCore( 7463): AcmsCore: inside DeInit
D/AcmsCore( 7463): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7463): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 7463): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7463): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7463): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7463): getSvcCounter - Counter value: 0
,D/AcmsService( 7463): killing acms process
I/Process ( 7463): Sending signal. PID: 7463 SIG: 9
,I/ActivityManager(  903): Process ACMS.Process (pid 7463)(adj 0) has died(59,576)
,I/DIAGMON_AGENT( 7674): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 7674): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7674): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7674): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/SMD     (  291): DCD ON
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7698): MountEmulatedStorage()
E/Zygote  ( 7698): v2
I/libpersona( 7698): KNOX_SDCARD checking this for 10010
I/libpersona( 7698): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7698 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7698): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7698): TimaSignature is unavailable
,D/ActivityThread( 7698): Added TimaKeyStore provider
,D/ResourcesManager( 7698): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/GAV2    ( 7220): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  903): Killing 6346:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/FOTA_Client( 7698): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7715): MountEmulatedStorage()
E/Zygote  ( 7715): v2
I/libpersona( 7715): KNOX_SDCARD checking this for 10018
I/libpersona( 7715): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7715 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6365:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,I/SELinux ( 7715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  903): failed to open /acct/uid_10074/pid_6346/cgroup.procs: No such file or directory
,I/SELinux ( 7715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7715): TimaSignature is unavailable
,D/ActivityThread( 7715): Added TimaKeyStore provider
,D/ResourcesManager( 7715): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7715): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7715): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453132616165
,I/KLMS-2.4.503: ( 7715): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7715): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7715): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  903): Killing 6407:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6365/cgroup.procs: No such file or directory
,E/Zygote  ( 7730): MountEmulatedStorage()
I/libpersona( 7730): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7730): v2
I/libpersona( 7730): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7730 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7730): TimaSignature is unavailable
,D/ActivityThread( 7730): Added TimaKeyStore provider
,D/ResourcesManager( 7730): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7730): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6407/cgroup.procs: No such file or directory
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5174): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7142): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7142): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7142): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7142): [SLFUCHKMGR] constructor called
,I/SA      ( 7142): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7142): [OR] == isSIMCardReady false ==
I/SA      ( 7142): [SCU] == networkStateCheck == false
,I/SA      ( 7142): [OR] onReceive END
,E/SPPClientService( 5174): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7747): MountEmulatedStorage()
E/Zygote  ( 7747): v2
I/libpersona( 7747): KNOX_SDCARD checking this for 10070
I/libpersona( 7747): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7747 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  903): Killing 7040:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/SELinux ( 7747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7747): TimaSignature is unavailable
,D/ActivityThread( 7747): Added TimaKeyStore provider
,D/ResourcesManager( 7747): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7747): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7747): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7747): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7747): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7747): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7747): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7747): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7747): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7747): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7747): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7747): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  903): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 10070
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  903): ret = -1
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/dhcpcd  ( 7646): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,D/accuweather( 7747): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7747): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7747): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7747): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7747): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7747): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  903): failed to open /acct/uid_10014/pid_7040/cgroup.procs: No such file or directory
,D/accuweather( 7747): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7747): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7747): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7747): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7764): MountEmulatedStorage()
I/libpersona( 7764): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7764): v2
I/libpersona( 7764): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7764 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 7059:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/dhcpcd  ( 7646): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7764): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7764): TimaSignature is unavailable
,D/ActivityThread( 7764): Added TimaKeyStore provider
,D/ResourcesManager( 7764): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7764): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7764): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7764): premStatus:2
,W/libprocessgroup(  903): failed to open /acct/uid_10015/pid_7059/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7764): isEulaShown : false
,I/KnoxUsageLogPro( 7764): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7789): MountEmulatedStorage()
,E/Zygote  ( 7789): v2
I/libpersona( 7789): KNOX_SDCARD checking this for 10087
I/libpersona( 7789): KNOX_SDCARD not a persona
,I/jxcore-log( 7237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7237): 
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7789 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6319:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7789): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7789): TimaSignature is unavailable
,D/ActivityThread( 7789): Added TimaKeyStore provider
,D/ResourcesManager( 7789): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10033/pid_6319/cgroup.procs: No such file or directory
,I/ActivityManager(  903): Killing 4726:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,D/Headlines( 5369): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5369): getCountryCode(): countryCode = PL
,D/Headlines( 5369): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5369): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5369): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5369): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5369): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5369): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5369): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7816): MountEmulatedStorage()
E/Zygote  ( 7816): v2
I/libpersona( 7816): KNOX_SDCARD checking this for 10127
I/libpersona( 7816): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7816 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 8715(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 296us total 14.152ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.928ms
,I/SELinux ( 7816): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.576ms
,I/SELinux ( 7816): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7816): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7816): TimaSignature is unavailable
,D/ActivityThread( 7816): Added TimaKeyStore provider
,D/ResourcesManager( 7816): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  903): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  903): do suspend true
,D/WifiP2pService(  903): InactiveState{ what=143375 }
D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  903): WifiStateMachine DHCP successful
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  903): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  903): Not connected state, yet.
E/WifiStateMachine(  903): VerifyingLinkState enter
,D/WifiStateMachine(  903): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  903): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  903): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  903): callSECApiInt - ID [210]
,E/WifiStateMachine(  903): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  903): updateNetworkInfo()
,D/ConnectivityService(  903): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  903): Adding iface wlan0 to network 503
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  903): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/libprocessgroup(  903): failed to open /acct/uid_10034/pid_4726/cgroup.procs: No such file or directory
,D/ConnectivityService(  903): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  903): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  903): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  903): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  903): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  903): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  286): QcRouteController
,E/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  903): Now, connected state.
E/WifiStateMachine(  903): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,V/        (  286): QcRouteController
E/WifiStateMachine(  903): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  903): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  903): mBoosterFLAG : 0
I/WifiTrafficPoller(  903): current booster mode : FullMode
,D/WifiNative-HAL(  903): callSECApiVoid - ID [212]
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        (  286): QcRouteController
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/WifiStateMachine(  903): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine(  903): REQUEST_POWER_SAVE_ON
,V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,D/ConnectivityService(  903): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  903): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903): ignoring duplicate network state non-change
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): ignoring duplicate network state non-change
E/ConnectivityService(  903): updateNetworkInfo()
,D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Validated
D/ConnectivityService(  903):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): currentScore = 0, newScore = 60
,D/ConnectivityService(  903):    accepting network in place of null
D/ConnectivityService(  903): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1478): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  903): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  903): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/ConnectivityService(  903): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats(  903): updateIfacesLocked()
V/NetworkStats(  903): performPollLocked(flags=0x1)
D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/NetworkStatsFactory(  903): UpdateStatsForKnox
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/EntConnectivity(  903): Not allowed due to - mEnabled false
D/ConnectivityService(  903): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
D/ConnectivityService(  903): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  903): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkStats(  903): performPollLocked() took 6ms
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2480): CM callback handler got msg 524290
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 2480): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/jxcore-log( 7237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7237): 
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7816): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7816): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7816): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7816): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 7237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7237): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7237): 
,I/WebViewFactory( 7816): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7816): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7816): Loading: webviewchromium
,I/LibraryLoader( 7816): Time to load native libraries: 4 ms (timestamps 3911-3915)
I/LibraryLoader( 7816): Expected native library version number "",actual native library version number ""
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  903): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  903): identical MTU - not setting
D/ConnectivityService(  903): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  903): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  286): QcRouteController
E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
V/WebViewChromiumFactoryProvider( 7816): Binding Chromium to main looper Looper (main, tid 1) {d605580}
I/LibraryLoader( 7816): Expected native library version number "",actual native library version number ""
,I/chromium( 7816): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,V/        (  286): QcRouteController
,W/NetworkManagementService(  903): route cmd failed: 
W/NetworkManagementService(  903): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  903): '
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  903): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  903): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  903): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 2480): CM callback handler got msg 524295
D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2480): CM callback handler got msg 524295
,I/BrowserStartupController( 7816): Initializing chromium process, renderers=0
,W/art     ( 7816): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7816): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid( 7816): Requires BLUETOOTH permission
I/chromium( 7816): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7816): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7816): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7816): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7816): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7816): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7816): Remote Branch: 
I/Adreno-EGL( 7816): Local Patches: 
I/Adreno-EGL( 7816): Reconstruct Branch: 
,D/CustomFrequencyManagerService(  903): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  903): mDVFSHelper.release()
,I/NSApplication( 7816): Starting up...
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7889): MountEmulatedStorage()
E/Zygote  ( 7889): v2
I/libpersona( 7889): KNOX_SDCARD checking this for 10137
I/libpersona( 7889): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7889 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 7113:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,I/SELinux ( 7889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7889): TimaSignature is unavailable
,D/ActivityThread( 7889): Added TimaKeyStore provider
,D/ResourcesManager( 7889): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7889): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7889): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  903): failed to open /acct/uid_10041/pid_7113/cgroup.procs: No such file or directory
,D/QuickConnect( 7889): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7889): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7889): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 7905): MountEmulatedStorage()
I/libpersona( 7905): KNOX_SDCARD checking this for 10162
E/Zygote  ( 7905): v2
I/libpersona( 7905): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7905 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 5842:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  903): MasterInitialState.processMessage what=3
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  903): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  903): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,I/CLocInfoService(  903): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  903): CLocinfo wifi true 
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,I/SELinux ( 7905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 7905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2079): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2226): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2226): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7237): Test app app.js loaded
I/jxcore-log( 7237): 
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7617): type=WIFI subType= reason=null isConnected=true
,I/chromium( 7237): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3669): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3669): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/Choreographer( 7237): Skipped 250 frames!  The application may be doing too much work on its main thread.
,D/TimaKeyStoreProvider( 7905): TimaSignature is unavailable
,D/ActivityThread( 7905): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10047/pid_5842/cgroup.procs: No such file or directory
,D/ResourcesManager( 7905): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  903): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@6539b1 attribute=android.view.inputmethod.EditorInfo@1293ae96, token = android.os.BinderProxy@129956ea
D/ActivityManager(  903): post active user change for 0
D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
,W/ResourcesManager( 7905): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7905): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7905): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7905): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/ActivityManager(  903): Activity reported stop, but no longer stopping: ActivityRecord{39154b8a u0 com.test.thalitest/.MainActivity t9}
,I/Timeline( 7237): Timeline: Activity_idle id: android.os.BinderProxy@2cffb97 time:114381
,D/SecContentProvider2(  903): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  903): mCursor = null
,I/chromium( 7237): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,V/GLSActivity( 2251): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2251): Vacuum at: now=1453132617720 tag=VacuumService
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,E/Zygote  ( 7935): MountEmulatedStorage()
E/Zygote  ( 7935): v2
I/libpersona( 7935): KNOX_SDCARD checking this for 10077
I/libpersona( 7935): KNOX_SDCARD not a persona
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  903): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7935 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,I/SELinux ( 7935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7935): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7553): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7553): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7553): StateMachine : Current State = 1
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,D/SecurityLogAgent( 7553): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  903): Killing 5546:com.android.mms/u0a49 (adj 15): bgCount ##41
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/TimaKeyStoreProvider( 7935): TimaSignature is unavailable
,D/ActivityThread( 7935): Added TimaKeyStore provider
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,I/ActivityManager(  903): Killing 7169:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
D/ResourcesManager( 7935): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,E/Zygote  ( 7951): MountEmulatedStorage()
I/libpersona( 7951): KNOX_SDCARD checking this for 10177
E/Zygote  ( 7951): v2
I/libpersona( 7951): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7951 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7905): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 7951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/CountryDetector(  903): No listener is left
,E/SELinux ( 7951): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7935): onCreate
,D/BadgeProvider( 7935): DatabaseHelper
,D/BadgeProvider( 7935): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7951): TimaSignature is unavailable
,D/ActivityThread( 7951): Added TimaKeyStore provider
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7935): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1492): reloadBadges entered.
,D/BadgeProvider( 7935): sendNotify, [notify] : null
D/BadgeProvider( 7935): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7935): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7935): update, [UpdateCount] : 1
,W/libprocessgroup(  903): failed to open /acct/uid_10049/pid_5546/cgroup.procs: No such file or directory
,W/libprocessgroup(  903): failed to open /acct/uid_10050/pid_7169/cgroup.procs: No such file or directory
,I/ActivityManager(  903): Killing 7187:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7525): notifyNetworkActivated
,W/libprocessgroup(  903): failed to open /acct/uid_10057/pid_7187/cgroup.procs: No such file or directory
,W/ContextImpl( 7525): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  903): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/hcjo    ( 7525): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7525): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7525): exit::IDLE
D/InitializeManagerStateMachine( 7525): entry::NETWORK_CHECK
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7525): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7525): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7525): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7525): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7525): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7525): entry::SUCCESS
D/hcjo    ( 7525): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1315): Starting #8
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7525): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7525): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7525): exit::SUCCESS
D/InitializeManagerStateMachine( 7525): entry::IDLE
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1315): Starting #9
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1315): Starting #10
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1315): Starting #11
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  903): callSECApi what=220
D/WifiStateMachine(  903): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7076): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7076): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7076): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7076): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7674): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7674): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/PowerManagerService(  903): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=903
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/FOTA_Client( 7698): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7715): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7715): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453132618289
,I/KLMS-2.4.503: ( 7715): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7715): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7715): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7715): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/KLMS-2.4.503: ( 7715): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7730): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5174): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7142): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7142): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7142): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7142): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7142): [OR] == isSIMCardReady false ==
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7142): [SCU] == networkStateCheck == true
I/SA      ( 7142): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 7142): isChinaCountryCode : false
I/SA      ( 7142): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7142): [OR] == networkStateCheck true ==
,I/SA      ( 7142): [OR] GetMyCountryZoneTask
,I/SA      ( 7142): [OR] onReceive END
,I/SA      ( 7142): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7142): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7142): [SSP] query invoked
,D/accuweather( 7747): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7747): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7764): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7764): premStatus:2
,I/SA      ( 7142): [TPMU] GetMccFromDB : null
,I/KnoxUsageLogPro( 7764): isEulaShown : false
I/KnoxUsageLogPro( 7764): KnoxUsageReceiver onReceive : not Processible, just return
I/SA      ( 7142): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7142): [TPM] isNoProxy(default) : true
,D/Headlines( 5369): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5369): getCountryCode(): countryCode = PL
,D/Headlines( 5369): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadlinesCardManager( 5369): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5369): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5369): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5369): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5369): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5369): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7142): fail readDirectory() errno=2
,D/QuickConnect( 7889): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7889): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7889): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7553): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7553): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7553): StateMachine : Current State = 1
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7553): StateMachine : Changed Current State = 1
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7525): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7525): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7525): exit::IDLE
D/InitializeManagerStateMachine( 7525): entry::NETWORK_CHECK
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7525): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7525): exit::NETWORK_CHECK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7237): setDiscoveryMode: Mode set to BLE
D/InitializeManagerStateMachine( 7525): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7525): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7525): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7525): entry::SUCCESS
D/hcjo    ( 7525): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/jxcore-log( 7237): BLE advertisement is supported
I/jxcore-log( 7237): 
,D/hcjo    ( 7525): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7525): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7525): exit::SUCCESS
D/InitializeManagerStateMachine( 7525): entry::IDLE
,E/SMD     (  291): DCD ON
,I/SA      ( 7142): [RC New] Execute method=[GET] start
,I/SA      ( 7142): [RC New] Security=[true]
,I/System.out( 7142): Thread-1125(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7142): Thread-1125(ApacheHTTPLog):isShipBuild true
,I/System.out( 7142): Thread-1125(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  903): waitForAlarm result :4
,D/KeyguardViewMediator( 1184): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1184): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/KeyguardViewMediator( 1184): doKeyguard: not showing because lockscreen is off
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  903): stay LED for fully charged
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  ( 7646): wlan0: sending IPv6 Router Solicitation
,D/PackageManager(  903): [MSG] MCS_UNBIND
,I/ActivityManager(  903): Killing 6011:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6011/cgroup.procs: No such file or directory
,I/PowerManagerService(  903): [PWL] Off : 5s ago
,I/SA      ( 7142): [RC New] [v2liruge] api execute + 1023
,I/SA      ( 7142): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,V/AlarmManager(  903): waitForAlarm result :8
,I/System.out( 7142): AsyncTask #1 calls detatch()
,V/AlarmManager(  903): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,I/SA      ( 7142): [ODM] saveOpenData( GEO_IP, PL )
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SA      ( 7142): [OCP] update openData : PL
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SA      ( 7142): [TPMU] getNetworkMcc : 
,I/SA      ( 7142): [SCU] saveMccToPreferece Start
I/SA      ( 7142): [SCU] RegionMCC : 260
I/SA      ( 7142): [SSP] query invoked
,I/SA      ( 7142): [TPMU] GetMccFromDB : null
I/SA      ( 7142): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7142): [SCU] saveMccToPreferece End
,I/SA      ( 7142): [RC New] executeRequest [v2liruge] end. 1192
I/SA      ( 7142): [RC New] Execute end
I/SA      ( 7142): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7142): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  903): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  903): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 2251): callingUid 10011, callindPid: 2251
,D/ResourcesManager( 7617): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7617): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7617): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7617): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7617): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7617): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7617): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7617): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7617): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7617): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     (  903): Explicit concurrent mark sweep GC freed 53477(3MB) AllocSpace objects, 3(48KB) LOS objects, 31% free, 35MB/51MB, paused 4.245ms total 83.271ms
,I/MusicLeanback( 7617): Conditions not met for autocaching.
I/MusicLeanback( 7617): Stop autocaching.
,E/ActivityThread( 7617): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@29a78240 that was originally bound here
E/ActivityThread( 7617): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@29a78240 that was originally bound here
E/ActivityThread( 7617): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7617): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7617): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7617): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7617): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7617): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7617): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7617): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7617): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7617): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7617): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7617): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7617): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7617): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7617): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7617): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7617): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7617): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7617): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7617): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7617): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7617): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7617): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7617): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/PowerManagerService(  903): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 903) eventTime = 118461
,D/PowerManagerService(  903): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=903 (0x0)
D/PowerManagerService(  903): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=903, ws=WorkSource{10058}) (elapsedTime=3489)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/SMD     (  291): DCD ON
,I/GAV4    ( 7816): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7076): mConnectivityHandler : connected
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7076): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7076): [GetString-S]
,I/ReactiveServiceManager( 7076): Supported : 1
,D/QSEECOMAPI: (  903): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  903): App is not loaded in QSEE
,D/QSEECOMAPI: (  903): Loaded image: APP id = 2
,D/QSEECOMAPI: (  903): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  903): QSEECom_shutdown_app, app_id = 2
,E/terrier (  903): handleString: Failed to handle string(-4)
E/terrier (  903): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 7076): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7076): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7076): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7076): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7076): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 7076): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7646): wlan0: sending IPv6 Router Solicitation
,D/SSRM:m  (  903): SIOP:: AP = 370, PST = 356, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7646): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7646): wlan0: no IPv6 Routers available
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  903): waitForAlarm result :4
,D/PreloadUpdateManagerStateMachine( 7525): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7525): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7525): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7525): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7525): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7525): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7525): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7525): entry::IDLE
,D/Finsky  ( 6449): [1075] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6449): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PreloadUpdateManagerStateMachine( 7525): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7525): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7525): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 7525): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7525): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7525): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7525): entry::IDLE
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  903): [PWL] Off : 15s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{3946f121 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  903): SIOP:: AP = 320, PST = 348, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 4
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  903): waitForAlarm result :4
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  903): SIOP:: AP = 310, PST = 340, CUR = 450
,I/PowerManagerService(  903): [PWL] Off : 30s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  903): stay LED for fully charged
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true,
,D/SSRM:m  (  903): SIOP:: AP = 300, PST = 331, CUR = 450
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  903): SIOP:: AP = 290, PST = 326, CUR = 450
,I/PowerManagerService(  903): [PWL] Off : 50s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 5
,V/AlarmManager(  903): waitForAlarm result :4
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2251): Scheduling Phenotype for one-off execution 1701 seconds from now (1453132669793)
,D/GetConfigurationSnapshotOperation( 2251): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2251): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2251): Using platform SSLCertificateSocketFactory
,E/SMD     (  291): DCD ON
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 2251): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2251): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2251): (HTTPLog)-Thread-304-934698271: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2251): Tagging socket 73 with tag 1000120100000000{268440065,0} uid -1, pid: 2251, getuid(): 10011
,I/qtaguid ( 2251): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 2251, getuid(): 10011
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2251): Tagging socket 73 with tag 1000120100000000{268440065,0} uid -1, pid: 2251, getuid(): 10011
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  903): SIOP:: AP = 290, PST = 323, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,V/AlarmManager(  903): waitForAlarm result :8
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,D/BatteryService(  903): stay LED for fully charged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:m  (  903): SIOP:: AP = 290, PST = 321, CUR = 450
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  903): [PWL] Off : 75s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/BatteryService(  903): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  903): SIOP:: AP = 270, PST = 317, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 6
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/BatteryService(  903): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,I/ClearcutLoggerApiImpl( 2251): disconnect managed GoogleApiClient
,D/SSRM:m  (  903): SIOP:: AP = 270, PST = 311, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/BatteryService(  903): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/SSRM:m  (  903): SIOP:: AP = 260, PST = 297, CUR = 450
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 105s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:m  (  903): SIOP:: AP = 260, PST = 286, CUR = 450
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 7
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  903): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  903): stay LED for fully charged
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  903): SIOP:: AP = 260, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  903): waitForAlarm result :8
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/BatteryService(  903): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:m  (  903): SIOP:: AP = 260, PST = 275, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,I/jxcore-log( 7237): --= Surplus to requirements =--
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ****TEST TOOK:  ms ****
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7237): 
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 8152): 
D/AndroidRuntime( 8152): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8152): CheckJNI is OFF
,D/AndroidRuntime( 8152): setted country_code = Poland
,D/AndroidRuntime( 8152): setted countryiso_code = PL
,D/AndroidRuntime( 8152): setted sales_code = XEO
,D/AndroidRuntime( 8152): readGMSProperty: start
,D/AndroidRuntime( 8152): readGMSProperty: already setted!!
D/AndroidRuntime( 8152): readGMSProperty: end
D/AndroidRuntime( 8152): addProductProperty: start
,E/AffinityControl( 8152): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8152): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  903): START PACKAGE DELETE: observer{774986085}
D/PackageManager(  903): pkg{<packageName>}
D/PackageManager(  903): user{0}
D/PackageManager(  903): caller{2000}
D/PackageManager(  903): flags{3}
,D/PersonaManagerService(  903): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  903): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  903): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  903): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  903): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  903): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  903): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  903): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  903): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  903): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  903): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  903): Killing 7237:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  903):   Force finishing activity ActivityRecord{39154b8a u0 com.test.thalitest/.MainActivity t9}
,D/FocusedStackFrame(  903): Set to : 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/WifiService(  903): Client connection lost with reason: 4
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,I/art     ( 1575): Explicit concurrent mark sweep GC freed 3827(393KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 411us total 19.107ms
,I/art     ( 2480): Explicit concurrent mark sweep GC freed 11192(592KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 21MB/35MB, paused 536us total 47.955ms
,I/art     ( 6241): Explicit concurrent mark sweep GC freed 30373(1674KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 361us total 43.450ms
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  903): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SamsungIME( 1877): mOCRHelper is null
,D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 2251): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7715): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7715): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453132751934
,I/KLMS-2.4.503: ( 7715): MainReciver(): PACKAGE_REMOVED
,I/art     (  903): Explicit concurrent mark sweep GC freed 30753(2MB) AllocSpace objects, 44(704KB) LOS objects, 31% free, 35MB/51MB, paused 3.142ms total 118.525ms
,I/art     (  903): WaitForGcToComplete blocked for 50.540ms for cause Explicit
,I/KLMS-2.4.503: ( 7715): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/SecContentProvider2(  903): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  903): mCursor = null
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/RegisteredServicesCache( 1472): empty dynamic service
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/EnterpriseDeviceManagerService(  903): Package has changed for user 0
D/EnterpriseDeviceManagerService(  903): Admin package name: com.google.android.gms
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,E/Zygote  ( 8178): MountEmulatedStorage()
E/Zygote  ( 8178): v2
I/libpersona( 8178): KNOX_SDCARD checking this for 10103
I/libpersona( 8178): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8178 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8178): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  903): PackageReceiver onReceive()
I/HarmonyEASService(  903): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  903): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  903): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/JobSchedulerService(  903): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  903): uID is 10191
V/EnterpriseBillingPolicy(  903): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  903): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  903): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  903): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  903): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  903): removeObsoleteFile: deleting file=9_task.xml
,D/TaskPersister(  903): removeObsoleteFile: deleting file=9_task_thumbnail.png
,D/TimaKeyStoreProvider( 8178): TimaSignature is unavailable
,D/ActivityThread( 8178): Added TimaKeyStore provider
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/art     (  903): Explicit concurrent mark sweep GC freed 10320(508KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 35MB/51MB, paused 3.858ms total 217.058ms
,D/ResourcesManager( 8178): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/SurfaceWidgetView( 1492): destroyHardwareResources():317283661
,V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  903): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/Launcher( 1492): onRestart, Launcher: 841616702
,D/Launcher( 1492): onStart, Launcher: 841616702
D/Launcher.HomeView( 1492): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2079): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2079): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/elm:14451( 8178): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/elm:14451( 8178): ELMEngine.ELMEngine( context ).
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/elm:14451( 8178): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8178): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 8178): ElmAgentService : onCreate()
,D/elm:14451( 8178): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8178): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8178): MDMBridge.getInstance()
D/elm:14451( 8178): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 8199): MountEmulatedStorage()
E/Zygote  ( 8199): v2
I/libpersona( 8199): KNOX_SDCARD checking this for 10016
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
I/libpersona( 8199): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1184): value : false
,I/ActivityManager(  903): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8199 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/SELinux ( 8199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/elm:14451( 8178): MDMBridge.getAllLicenseInfoFromSDK()
E/SELinux ( 8199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 7237 uid 10191
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/elm:14451( 8178): ElmAgentService : onDestroy().
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  903): Killing 7220:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 8199): TimaSignature is unavailable
,D/ActivityThread( 8199): Added TimaKeyStore provider
,D/ResourcesManager( 8199): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8199): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8199): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8199): onReceive() : package name is not s health. Return !!!
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/Timeline(  903): Timeline: Activity_windows_visible id: ActivityRecord{1bdef063 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:249083
I/PCWCLIENTTRACE_PushUtil( 7076): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7076): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7076): getPushTypeList : [SPP, GCM]
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/PCWCLIENTTRACE_SYSTEMReceiver( 7076): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(  903): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  903): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  903): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10097/pid_7220/cgroup.procs: No such file or directory
E/Zygote  ( 8219): MountEmulatedStorage()
I/libpersona( 8219): KNOX_SDCARD checking this for 10033
E/Zygote  ( 8219): v2
,I/libpersona( 8219): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8219 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 7320:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,D/PackageManager(  903): delete codoeFile: 
,D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/PackageManager(  903): result of delete: 1{774986085}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux ( 8219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  903): clearDefaults: com.test.thalitest
,D/AndroidRuntime( 8152): Shutting down VM
,I/CrashAnrDetector(  903): onPackageRemoved : com.test.thalitest
,D/TimaKeyStoreProvider( 8219): TimaSignature is unavailable
,D/ActivityThread( 8219): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10032/pid_7320/cgroup.procs: No such file or directory
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 8219): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8219): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8219): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8219): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8236): MountEmulatedStorage()
E/Zygote  ( 8236): v2
,I/libpersona( 8236): KNOX_SDCARD checking this for 10034
I/libpersona( 8236): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8236 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 7300:com.sec.android.automotive.drivelink/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 8236): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8236): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8236): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8236): TimaSignature is unavailable
,D/ActivityThread( 8236): Added TimaKeyStore provider
,D/ResourcesManager( 8236): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10098/pid_7300/cgroup.procs: No such file or directory
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8236): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8236): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8236): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/SQLiteDatabase( 8236): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase( 8236): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8236): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8236): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase( 8236): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase( 8236): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:123)
E/SQLiteDatabase( 8236): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:85)
E/SQLiteDatabase( 8236): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:30)
E/SQLiteDatabase( 8236): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 8236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8236): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 8236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8236): 	at java.lang.Thread.run(Thread.java:818)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8236): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 8236): checkState() : APP TYPE = Full
,F/libc    ( 8236): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7870d8b6 in tid 8236 (oid.app.shealth)
,E/audit_log( 2174): File locking failed. error= Bad file number
,E/audit_log( 2174): File locking failed. error= Bad file number
,I/EventHub(  903): Removing device '/dev/input/event4' due to inotify event
,I/ActivityManager(  903): Process com.sec.android.app.shealth (pid 8236)(adj 0) has died(257,545)
,I/EventHub(  903): Removing device '/dev/input/event5' due to inotify event
,F/libc    ( 5174): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7764ea00 in tid 5174 (om.sec.spp.push)
F/libc    ( 5174): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2174): File locking failed. error= Bad file number
,I/Zygote  (  321): Process 8236 exited due to signal (7)
,I/EventHub(  903): Removing device '/dev/input/event6' due to inotify event
,I/ActivityManager(  903): Process com.sec.spp.push (pid 5174)(adj 0) has died(262,546)
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8261): MountEmulatedStorage()
I/libpersona( 8261): KNOX_SDCARD checking this for 10037
E/Zygote  ( 8261): v2
I/libpersona( 8261): KNOX_SDCARD not a persona
I/EventHub(  903): Removing device '/dev/input/event7' due to inotify event
I/ActivityManager(  903): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8261 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Zygote  (  321): Process 5174 exited due to signal (7)
,I/EventHub(  903): Removing device '/dev/input/event8' due to inotify event
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/SELinux ( 8261): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
E/SELinux ( 8261): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  903): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  903): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider( 8261): TimaSignature is unavailable
,D/ActivityThread( 8261): Added TimaKeyStore provider
,I/EventHub(  903): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager( 8261): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/        ( 8261): Zip: read 65557 failed: I/O error
,W/zipro   ( 8261): Error opening archive /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk: I/O Error
D/asset   ( 8261): failed to open Zip archive '/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk'
,W/ContextImpl( 8261): Unable to create files subdir /data/data/com.sec.spp.push/cache
,E/ActivityThread( 8261): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8261): Zip: read 65557 failed: I/O error
,F/libc    ( 8261): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb500f000 in tid 8261 (moteNotiProcess)
,F/libc    ( 8261): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2174): File locking failed. error= Bad file number
,I/ActivityManager(  903): Process com.sec.spp.push:RemoteNotiProcess (pid 8261)(adj 0) has died(262,546)
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8281): MountEmulatedStorage()
E/Zygote  ( 8281): v2
I/libpersona( 8281): KNOX_SDCARD checking this for 10041
I/libpersona( 8281): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8281 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/Zygote  (  321): Process 8261 exited due to signal (7)
,I/SELinux ( 8281): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8281): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/TimaKeyStoreProvider( 8281): TimaSignature is unavailable
,D/ActivityThread( 8281): Added TimaKeyStore provider
,D/ResourcesManager( 8281): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8281): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8281): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 8281): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 8281): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8281): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73706aae in tid 8281 (sdk.samsunglink)
,F/libc    ( 8281): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2174): File locking failed. error= Bad file number
,I/ActivityManager(  903): Process com.samsung.android.sdk.samsunglink (pid 8281)(adj 0) has died(261,546)

```
