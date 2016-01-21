#### Test 564496600f5d794_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/MyFiles ( 7135): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
E/installd(  303): system dir 0 : /system/app/
E/installd(  303): system dir 1 : /system/priv-app/
E/installd(  303): system dir 2 : /vendor/app/
E/installd(  303): system dir 3 : /oem/app/
I/TactileAssist(  889): enable value -1
I/TactileAssist(  889): internal enable value -1
I/TactileAssist(  889): intensity value -1
I/TactileAssist(  889): saveAppList value true
I/TactileAssist(  889): List of disabled apps :
--------- beginning of system
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
D/PackageManager(  889): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 7154): MountEmulatedStorage()
E/Zygote  ( 7154): v2
I/libpersona( 7154): KNOX_SDCARD checking this for 10057
I/libpersona( 7154): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7154 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7154): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7154): TimaSignature is unavailable
D/ActivityThread( 7154): Added TimaKeyStore provider
,D/ResourcesManager( 7154): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7154): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7154): onReceive() it will make start service
D/Compatibility( 7154): onHandleIntent()
D/Compatibility( 7154): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
D/Compatibility( 7154): found: 2
D/Compatibility( 7154): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7154): skipping ResolveInfo{27072131 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7154): considering ResolveInfo{270c4016 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7154): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/UpdateIcingCorporaServi( 1584): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7154): enabling receiver ResolveInfo{2c22d97 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7154): enabling receiver ResolveInfo{305b9b84 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 7174): MountEmulatedStorage()
E/Zygote  ( 7174): v2
I/libpersona( 7174): KNOX_SDCARD checking this for 1000
I/libpersona( 7174): KNOX_SDCARD not a persona
D/Compatibility( 7154): enabling receiver ResolveInfo{c7b9f6d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/ActivityManager(  889): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7174 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7174): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 7154): enabling receiver ResolveInfo{368447a2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7154): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager(  889): Killing 6390:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 7174): TimaSignature is unavailable
D/ActivityThread( 7174): Added TimaKeyStore provider
D/ResourcesManager( 7174): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/ResourcesManager( 1584): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/UpdateIcingCorporaServi( 1584): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
W/libprocessgroup(  889): failed to open /acct/uid_1000/pid_6390/cgroup.procs: No such file or directory
W/ContextImpl( 7174): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7192): MountEmulatedStorage()
E/Zygote  ( 7192): v2
I/libpersona( 7192): KNOX_SDCARD checking this for 10085
I/libpersona( 7192): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=7192 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  889): Killing 5531:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
I/SELinux ( 7192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7192): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7192): TimaSignature is unavailable
D/ActivityThread( 7192): Added TimaKeyStore provider
D/AndroidRuntime( 7180): 
D/AndroidRuntime( 7180): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/ResourcesManager( 7192): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/AndroidRuntime( 7180): CheckJNI is OFF
W/ResourcesManager( 7192): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 7180): setted country_code = Poland
D/AndroidRuntime( 7180): setted countryiso_code = PL
D/AndroidRuntime( 7180): setted sales_code = XEO
D/AndroidRuntime( 7180): readGMSProperty: start
D/AndroidRuntime( 7180): readGMSProperty: already setted!!
D/AndroidRuntime( 7180): readGMSProperty: end
D/AndroidRuntime( 7180): addProductProperty: start
W/libprocessgroup(  889): failed to open /acct/uid_10039/pid_5531/cgroup.procs: No such file or directory
D/PushModule( 7192): [PushClientApplication] (main) PushClientApplication.onCreate()
I/PushModule( 7192): [PushClientApplication] (main) PushModule version: 0.9.01.12
D/PushModule( 7192): [PushClientApplication] (main) Discovered public push client. disable in app push client.
D/ChatON  ( 7192): [1][isApplicationInstalled] com.android.mms was installed
W/ContextImpl( 7192): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
W/ActivityManager(  889): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
D/ChatON  ( 7192): [1][a] ChatONV isn't installed.
D/ChatON  ( 7192): [1][a] ChatONVPlugIn.isAvailable()
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 7180): AffinityControl: registerfunction enter
E/Zygote  ( 7218): MountEmulatedStorage()
E/Zygote  ( 7218): v2
I/libpersona( 7218): KNOX_SDCARD checking this for 10097
I/libpersona( 7218): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7218 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  889): Killing 5721:com.google.android.gm/u0a113 (adj 15): bgCount ##41
D/AndroidRuntime( 7180): Calling main entry com.android.commands.am.Am
I/SELinux ( 7218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7218): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/PersonaManagerService(  889): inState():  stateMachine is null !!
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  889): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  889): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  889): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  889): mDVFSHelper.acquire()
D/TimaKeyStoreProvider( 7218): TimaSignature is unavailable
D/FocusedStackFrame(  889): Set to : 0
D/ActivityThread( 7218): Added TimaKeyStore provider
D/Launcher.HomeView( 1493): onPause
D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/AndroidRuntime( 7180): Shutting down VM
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/Zygote  ( 7239): MountEmulatedStorage()
E/Zygote  ( 7239): v2
I/libpersona( 7239): KNOX_SDCARD checking this for 10191
I/libpersona( 7239): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7239 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SELinux ( 7239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/SELinux ( 7239): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  889): failed to open /acct/uid_10113/pid_5721/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager( 7218): creating new AssetManager and set to /system/app/Drive/Drive.apk
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
D/TimaKeyStoreProvider( 7239): TimaSignature is unavailable
D/ActivityThread( 7239): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  889): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  889): Display changed displayId=0
D/Launcher.HomeView( 1493): onStop
D/Launcher( 1493): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2266): [237392/6] Surface widget pause on instance = 1
I/MicrophoneInputStream( 1584): mic_close gfk@2f498aa0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2266): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 2266): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2266): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2266): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/ActivityThread( 1493): Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1493): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1493): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 1493): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 1493): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1493): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 1493): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1493): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 1493): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 1493): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1493): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1493): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 1493): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/SurfaceWidgetView( 1493): destroyHardwareResources():361828825
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBarManagerService(  889): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/AudioPolicyManager(  299): stopInput() input 29
D/accuweather( 2266): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2266): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/audio_hw_primary(  299): in_standby: enter
D/ResourcesManager( 7239): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/HotwordRecognitionRnr( 1584): Hotword detection finished
I/HotwordRecognitionRnr( 1584): Stopping hotword detection.
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
I/ActivityManager(  889): Activity reported stop, but no longer stopping: ActivityRecord{2c134089 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7}
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SurfaceWidgetView( 1493): destroyHardwareResources():361828825
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/audio_hw_primary(  299): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  299): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  299): disable_audio_route: reset mixer path: audio-record
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  299): Setting mixer control: value: 0
D/audio_route(  299): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  299): disable_audio_route: exit
V/audio_hw_primary(  299): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: DEC2 Volume
D/audio_route(  299): Setting mixer control: value: 0
D/audio_route(  299): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  299): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  299): Setting mixer control: value: 0
D/audio_route(  299): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  299): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  299): stop_input_stream: exit: status(0)
V/audio_hw_primary(  299): in_standby: exit:  status(0)
V/AudioPolicyManager(  299): releaseInput() 29
V/AudioPolicyManager(  299): closeInput(29)
V/audio_hw_primary(  299): adev_close_input_stream
V/audio_hw_primary(  299): in_standby: enter
V/audio_hw_primary(  299): in_standby: exit:  status(0)
E/audio_hw_primary(  299): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  299): releaseInput() exit
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/DocsApplication( 7218): Installing DEX configuration.
E/Watchdog(  889): !@Sync 3
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/DexInstaller( 7218): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7218): Provided clientMode=RELEASE, packageInfo=PackageInfo{3828b9d8 com.google.android.apps.docs}
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/TAG     ( 7218): onCreate()
D/CrossAppStateProvider( 7218): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/WebViewFactory( 7239): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7239): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7239): Loading: webviewchromium
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/LibraryLoader( 7239): Time to load native libraries: 2 ms (timestamps 3432-3434)
I/LibraryLoader( 7239): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
V/WebViewChromiumFactoryProvider( 7239): Binding Chromium to main looper Looper (main, tid 1) {c7b9f6d}
I/LibraryLoader( 7239): Expected native library version number "",actual native library version number ""
I/chromium( 7239): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7239): Initializing chromium process, renderers=0
W/art     ( 7239): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7239): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/chromium( 7239): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7239): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7239): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7239): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7239): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7239): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7239): Remote Branch: 
I/Adreno-EGL( 7239): Local Patches: 
I/Adreno-EGL( 7239): Reconstruct Branch: 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/chromium( 7239): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7239): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7239): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7239): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SystemWebViewEngine( 7239): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/art     ( 7239): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7239): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/SMD     (  294): DCD ON
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/Activity( 7239): performCreate Call secproduct feature valuefalse
D/Activity( 7239): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/OpenGLRenderer( 7239): Render dirty regions requested: true
D/ActivityManager(  889): post active user change for 0
D/KnoxTimeoutHandler(  889): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  889): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  258): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
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
I/OpenGLRenderer( 7239): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/OpenGLRenderer( 7239): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7239): Enabling debug mode 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  258): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  258): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/InputMethodManagerService(  889): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/ActivityManager(  889): Displayed com.test.thalitest/.MainActivity: +619ms
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/Timeline( 7239): Timeline: Activity_idle id: android.os.BinderProxy@251eedb4 time:103815
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
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/JsMessageQueue( 7239): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/chromium( 7239): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7239): 
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
D/CustomFrequencyManagerService(  889): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  889): mDVFSHelper.release()
I/Timeline(  889): Timeline: Activity_windows_visible id: ActivityRecord{20287f3f u0 com.test.thalitest/.MainActivity t9} time:104018
D/CustomFrequencyManagerService(  889): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  258): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  258): id=14 Removed Starting com.test.thalitest (-2/8)
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
E/Adreno-ES20( 7239): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7239): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/jxcore_app_log( 7239): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358602496
,I/chromium( 7239): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/CustomFrequencyManagerService(  889): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  tag : ACTIVITY_RESUME_BOOSTER@10
,V/AlarmManager(  889): waitForAlarm result :4
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7299): MountEmulatedStorage()
,E/Zygote  ( 7299): v2
I/libpersona( 7299): KNOX_SDCARD checking this for 10098
I/libpersona( 7299): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7299 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6108:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,I/art     (  321): Explicit concurrent mark sweep GC freed 8765(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 291us total 11.018ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 259us total 8.197ms
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 7.606ms
,I/SELinux ( 7299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 7218): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 7299): TimaSignature is unavailable
,D/ActivityThread( 7299): Added TimaKeyStore provider
,D/ResourcesManager( 7299): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10004/pid_6108/cgroup.procs: No such file or directory
,W/ResourcesManager( 7299): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 7299): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7299): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7299): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7323): MountEmulatedStorage()
E/Zygote  ( 7323): v2
I/libpersona( 7323): KNOX_SDCARD checking this for 10032
I/libpersona( 7323): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7323 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7323): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7323): TimaSignature is unavailable
,D/ActivityThread( 7323): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/PowerManagerService(  889): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  889): Nap time (uid 1000)...
I/PowerManagerService(  889): !@[ps] Screen__Off(2) : 
D/InputManager-JNI(  889): setDeviceInteractive: 0
I/PowerManagerService(  889): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  889): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  889): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  889): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/InputManager-JNI(  889): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  889): handleSandman : startDream()
,E/PowerManagerService(  889): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  889): Sleeping (uid 1000)...
D/PowerManagerService(  889): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  889): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  889): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  258): id=16 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  889): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/ResourcesManager( 7323): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/InputManager-JNI(  889): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/SContextService(  889): 	.unregisterCallback : 1, client=
D/SContextService(  889): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@28b50d46, Service = Auto Rotation, used = 1
,W/CAE     (  889): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  889): stop(ContextProvider.java:149)
V/CAE     (  889): clear(AutoRotationRunner.java:182)
,V/CAE     (  889): disable(AutoRotationRunner.java:171)
,I/CAE     (  889): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  889): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  306): sendContextData: -78, 7, 0, 0
,D/CAE     (  889): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  889): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,W/ResourcesManager( 7323): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 7218): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/CAE     (  889): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  889): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  889): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  889): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  889): removeSContextService() : service = Auto Rotation
D/SContextService(  889): ===== SContext Service List =====
D/SContextManager(  889):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@965e73e, service=Auto Rotation
,D/KeyguardViewMediator( 1184): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1184): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1184): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1184): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/KeyguardViewMediator( 1184): timeout : 5000
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/DisplayPowerController(  889): ColorFade: onAnimationStart
D/DisplayPowerController(  889): getFinalBrightness : 53 -> 0
,I/SQLiteSecureOpenHelper( 3477): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3477): getDatabaseLocked(b,b,pwd)...
,D/lights  (  889): lcd : 8 +
,D/lights  (  889): lcd : 8 -
,D/DisplayPowerController(  889): getFinalBrightness : 53 -> 0
D/lights  (  889): lcd : 0 +
,D/lights  (  889): lcd : 0 -
,I/System.out( 7323): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 7323): Inside WakeupProvider
,D/KeyguardViewMediator( 1184): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1184): handleNotifyScreenOff
,E/DatabaseUtils( 7323): Writing exception to parcel
E/DatabaseUtils( 7323): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7323): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7323): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7323): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7323): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7323): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7323): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7323): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7323): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7323): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7323): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LightsService(  889): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 889) 
,D/LightsService(  889): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  889): [SvcLED]  onSensorChanged::light value = 39
D/SensorManager(  889): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  889): unregisterListener ::   
D/BatteryService(  889): turn on LED for fully charged
D/lights  (  889): led_pattern : 5 +
,I/CAE     (  889): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  889): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  889): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  889): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  306): sendContextData: -76, 13, -46, 0
D/lights  (  889): led_pattern : 5 -
D/LightsService(  889): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  889): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 10, 3, 37,
D/SensorHubManager(  889): SendSensorHubData: send data = -63, 14, 10, 3, 37
,D/Sensorhubs(  306): sendContextData: -63, 14, 10, 3, 37
,W/System.err( 7299): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 7323): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  889):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  889): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  889): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  889): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  889): do suspend true
,D/NotificationService(  889): ACTION_SCREEN_OFF
D/LightsService(  889): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 889) 
D/LightsService(  889): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  889): [SvcLED]  onSensorChanged::light value = 39
,D/SensorManager(  889): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  889): unregisterListener ::   
D/LightsService(  889): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  299): adev_set_parameters: enter: screen_state=off
V/voice   (  299): voice_set_parameters: enter: screen_state=off
V/voice   (  299): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  299): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  299): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  299): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  299): adev_set_parameters: exit
,W/System.err( 7299): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 7299): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7299): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
,W/System.err( 7299): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
,W/System.err( 7299): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7299): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7299): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7299): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7299): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
,W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7299): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
,W/System.err( 7299): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7299): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
I/SecExternalDisplayIntents_Java(  889): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
W/System.err( 7299): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7299): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7299): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
,W/System.err( 7299): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7299): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7299): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7299): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7299): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7299): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 7299): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7299): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7299): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7299): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7299): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/IpRemoteDisplayController(  889): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  889): Bridge Server is not available
,D/VolumePanel( 1184): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1184): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1184): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1184): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  889): ACTION_SCREEN_OFF onReceive
,E/DatabaseUtils( 7323): Writing exception to parcel
E/DatabaseUtils( 7323): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7323): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7323): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7323): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7323): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7323): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7323): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7323): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7323): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7323): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7323): 	at android.os.Binder.execTransact(Binder.java:446)
,D/PersonaManagerServiceHandler(  889): MSG_ACTION_SCREEN_OFF called
,D/DisplayPowerState(  889): !@ ColorFade entry
,D/DisplayPowerController(  889): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  889): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  889): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  889): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  889): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  889): Light old sensor_state 513, new sensor_state : 1 en : 0
,W/System.err( 7299): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7299): 	at android.os.Parcel.readException(Parcel.java:1546)
,D/SensorManager(  889): unregisterListener ::   
W/System.err( 7299): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7299): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7299): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
,E/Sensors (  889): Acc old sensor_state 1, new sensor_state : 0 en : 0
,W/System.err( 7299): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7299): 	at android.content.ContentResolver.query(ContentResolver.java:428)
,W/System.err( 7299): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7299): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7299): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7299): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7299): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7299): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7299): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
,W/System.err( 7299): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7299): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7299): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7299): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7299): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7299): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7299): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
,W/System.err( 7299): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7299): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7299): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7299): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 7299): [DLApplication]-Init Called!:false
,E/[CarMode]( 7299): [DLApplication]-Init Started!:true
,D/SensorManager(  889): unregisterListener ::   
,I/[CarModeFW]( 7299): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7299): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7299): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7299): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7299): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7299): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7299): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7299): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7299): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7299): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7299): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7299): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7299): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7299): ### com.android.internal.os.ZygoteInit::main(1194)
,D/DisplayPowerController(  889): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  889): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  889): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  889): Display changed displayId=0
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  258): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/StatusBar.NetworkController( 1184): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-PhoneStatusBar( 1184):      ACTION_SCREEN_OFF is finished!!!! 
,D/NfcService( 1475): call the applyRotuiing
,I/MessageDataHandler( 7299): initialize
,D/[CarModeFW]( 7299): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7299): CDH-initiazlieCaches : after sync
,I/VlingoAndroidCore( 7323): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,E/StatusBar( 1184): onReceive : Intent.ACTION_SCREEN_OFF
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/Recents_AlternateRecentsComponent( 1184): dismissHelpPopup 
,D/accuweather( 2266): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2266): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2266): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/[CarModeFW]( 7299): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7299): CDH-ContactDataHandler initiazlieCaches time : 47
,D/[CarModeFW]( 7299): CDH-initiazlieCaches : end sync
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/rmt_storage(  282): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  282): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  282): wakelock acquired: 1, error no: 42
I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/[CarModeFW]( 7299): DrivingManager-initialize...
,D/SSRM:m  (  889): SIOP:: AP = 380, PST = 364, CUR = 450
,I/SensorService(  889): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  889): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  889): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  282): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  282): 
,I/rmt_storage(  282): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,W/ActivityManager(  889): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,W/ActivityManager(  889): getTasks: caller 10085 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  889): [PWL] sb release: PowerManagerService.Broadcasts
,D/VlingoApplication( 7323): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 7323): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 7299): Need to enable context aware info
V/MediaPlayer-JNI( 7299): native_setup
V/MediaPlayer( 7299): constructor
,V/MediaPlayer( 7299): setListener
,E/MediaPlayer-JNI( 7299): QCMediaPlayer mediaplayer NOT present
,D/qdhwcomposer(  258): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/SurfaceControl(  889): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService(  889): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  889): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL(  889): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  889): Got set_interactive hint
I/PowerManagerService(  889): [PWL] Off : 0s ago
,I/PowerManagerService(  889): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  889): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  889): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=889, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=1093)
I/PowerManagerService(  889): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=7)
,I/PowerManagerService(  889): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=6)
I/PowerManagerService(  889): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  889): [PWL]     mDisplayReady : false
D/DisplayPowerController(  889): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  889): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  889): [PWL] sb release: PowerManagerService.Display
,D/[CarModeFW]( 7299): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 7299): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 7299): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarMode]( 7299): [DLServiceManager]-requestRecommendedLocationList
,I/[CarMode]( 7299): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1453370617913
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1453370617914
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1453370617913
,D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1453370617914
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1453370617914
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1453370617914
,E/[CarMode]( 7299): [DLApplication]-Init End!:true
,D/TP/SmsProvider( 1487): query,matched:2, calling pid = 7299
,D/TP/SmsProvider( 1487): query,matched:2, calling pid = 7299
,D/[CarModeFW]( 7299): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/SmsProvider( 1487): match 2:Elapsed time : 2.032 ms
D/TP/SmsProvider( 1487): match 2:Elapsed time : 2.047 ms
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7363): MountEmulatedStorage()
I/libpersona( 7363): KNOX_SDCARD checking this for 10003
E/Zygote  ( 7363): v2
I/libpersona( 7363): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7363 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 7363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MessageDataHandler( 7299):  getInboxList smsCursor : 81
,I/SELinux ( 7363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/[CarModeFW]( 7299): RecommendHandler-selection = type = '3'
,E/SELinux ( 7363): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsProvider( 1487): Query uri=content://mms, match=0, calling pid = 7299
,D/TP/MmsProvider( 1487): Query uri=content://mms/inbox, match=2, calling pid = 7299
,D/MessageDataHandler( 7299):  getInboxList mmsCursor : 6
,I/MessageDataHandler( 7299): getUnreadMessageCount :0
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 89
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,D/[CarMode]( 7299): [DLApplication]-GooglePlayServices SUCCESS.
,I/ActivityManager(  889): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7372 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/Zygote  ( 7372): MountEmulatedStorage()
E/Zygote  ( 7372): v2
I/libpersona( 7372): KNOX_SDCARD checking this for 10019
D/[CarModeFW]( 7299): CDH-buildContactCacheWireFrame : cur len =0
I/libpersona( 7372): KNOX_SDCARD not a persona
,I/SELinux ( 7372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7372): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7363): TimaSignature is unavailable
D/ActivityThread( 7363): Added TimaKeyStore provider
,D/MessageDataHandler( 7299):  getInboxList mms,sms cursor join : 98
,E/[CarMode]( 7299): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/[CarModeFW]( 7299): RecommendHandler-selection = type = '3'
,D/[CarModeFW]( 7299): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7299
,V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.371 ms
,D/TP/MmsSmsProvider( 1487): query,matched:13, calling pid = 7299
,D/TP/MmsSmsProvider( 1487): match 13:Elapsed time : 1.373 ms
,I/UpdateManagerReceiver( 7299): Intent : android.intent.action.PACKAGE_ADDEDThu Jan 21 11:03:38 GMT+01:00 2016
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7393): MountEmulatedStorage()
I/libpersona( 7393): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7393): v2
I/libpersona( 7393): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7393 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7372): TimaSignature is unavailable
D/ActivityThread( 7372): Added TimaKeyStore provider
,I/ActivityManager(  889): Killing 6174:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,D/ResourcesManager( 7363): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/MessageDataHandler( 7299):  getInboxList address cursor : 90
,D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7299
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.146 ms
,D/MessageDataHandler( 7299):  getInboxList thread cursor : 9
,D/MessageDataHandler( 7299):  thread, addr result: 2
,I/[CarModeFW]( 7299): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 315
I/[CarModeFW]( 7299): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 316
,D/[CarModeFW]( 7299): PushMessageService-onCreate
D/ResourcesManager( 7372): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,I/ActivityManager(  889): Killing 6554:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,I/ActivityManager(  889): Killing 5474:com.google.android.apps.plus/u0a134 (adj 15): bgCount ##42
,I/ActivityManager(  889): Killing 6077:com.google.android.music:main/u0a125 (adj 15): bgCount ##43
,D/TimaKeyStoreProvider( 7393): TimaSignature is unavailable
,D/ActivityThread( 7393): Added TimaKeyStore provider
,D/[CarModeFW]( 7299): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7299): PushMessageService-registerPushMessageServiceListener
,D/ResourcesManager( 7393): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/UserAnalysis.PlaceProvider( 7363): PlaceProvider onCreate()
,W/ContextImpl( 7393): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,D/ResourcesManager( 7393): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/UserAnalysis.SecureDbManager( 7363): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7363): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7363): Create SecureDbHelper
,E/FilterInstaller( 7393): There is no requred permission
,I/art     (  889): Explicit concurrent mark sweep GC freed 250697(17MB) AllocSpace objects, 4(4MB) LOS objects, 30% free, 35MB/51MB, paused 1.427ms total 109.720ms
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,D/IntelligenceServiceApplication( 7363): onCreate()
,E/Zygote  ( 7409): MountEmulatedStorage()
E/Zygote  ( 7409): v2
I/libpersona( 7409): KNOX_SDCARD checking this for 10111
I/libpersona( 7409): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7409 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SQLiteSecureOpenHelper( 7363): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 7363): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7363): Open Place.db in secure mode
,I/SELinux ( 7409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  889): Killing 5820:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
E/SELinux ( 7409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SQLiteSecureOpenHelper( 7363): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 7363): ...getDatabaseLocked(b,b,pwd)
,D/[CarModeFW]( 7299): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7299): MyPlaceProvider-=============
D/[CarModeFW]( 7299): MyPlaceProvider-=============
D/[CarModeFW]( 7299): MyPlaceProvider-=============
,D/[CarModeFW]( 7299): MyPlaceProvider-=============
D/[CarModeFW]( 7299): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7299): MyPlaceProvider-==============
D/[CarModeFW]( 7299): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7299): MyPlaceProvider-==============
D/[CarModeFW]( 7299): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7299): MyPlaceProvider-==============
D/[CarModeFW]( 7299): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 581
,D/[CarMode]( 7299): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@5fb258ba, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@e167b728] LOCATIONS
,D/TimaKeyStoreProvider( 7409): TimaSignature is unavailable
,D/ActivityThread( 7409): Added TimaKeyStore provider
,W/libprocessgroup(  889): failed to open /acct/uid_10043/pid_6174/cgroup.procs: No such file or directory
W/libprocessgroup(  889): failed to open /acct/uid_10011/pid_6554/cgroup.procs: No such file or directory
,W/libprocessgroup(  889): failed to open /acct/uid_10125/pid_6077/cgroup.procs: No such file or directory
W/libprocessgroup(  889): failed to open /acct/uid_10134/pid_5474/cgroup.procs: No such file or directory
,D/ResourcesManager( 7409): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/[CarModeFW]( 7299): -[snowdeer] Rec : Missed Call : 544
,D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 636
,I/[CarModeFW]( 7299): -[snowdeer] Rec : Favorite : 13
,D/PackageIntentReceiver( 7409): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7409): Not GearManger package! 
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7425): MountEmulatedStorage()
E/Zygote  ( 7425): v2
I/libpersona( 7425): KNOX_SDCARD checking this for 10117
I/libpersona( 7425): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7425 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  889): Killing 5836:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
,W/jxcore-log( 7239): Initializing JXcore engine
W/jxcore-log( 7239): JXcore engine is ready
,I/SELinux ( 7425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7425): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/auditd  ( 2119): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  889): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  889): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/jxcore-log( 7239): Starting JXcore engine
,I/[CarModeFW]( 7299): -[snowdeer] Rec : CallLog : 81
,W/libprocessgroup(  889): failed to open /acct/uid_10093/pid_5820/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7425): TimaSignature is unavailable
,D/ActivityThread( 7425): Added TimaKeyStore provider
,I/[CarModeFW]( 7299): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7299): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7299): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 745
,D/ResourcesManager( 7425): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
I/[CarModeFW]( 7299): -[snowdeer] Rec : Schedule : 25
,I/[CarModeFW]( 7299): -[snowdeer] Rec : During DL app : 1
,I/[CarModeFW]( 7299): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7299): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7299): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7299): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7299): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7299): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 7299): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 749
,W/ResourcesManager( 7425): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  889): failed to open /acct/uid_10102/pid_5836/cgroup.procs: No such file or directory
,D/MagazineService Version( 7425): Magazine-Administrator: 11
,D/MagazineService Version( 7425): Magazine-Provider: 14
,D/MagazineService Version( 7425): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7425): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7425): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,W/jxcore-log( 7239): Platform android
W/jxcore-log( 7239): 
,W/jxcore-log( 7239): Process ARCH arm
W/jxcore-log( 7239): 
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7425): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7441): MountEmulatedStorage()
E/Zygote  ( 7441): v2
I/libpersona( 7441): KNOX_SDCARD checking this for 1000
I/libpersona( 7441): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7441 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7425): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 7441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  889): Killing 5883:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
I/SELinux ( 7441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7441): TimaSignature is unavailable
,D/ActivityThread( 7441): Added TimaKeyStore provider
,D/ResourcesManager( 7441): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10153/pid_5883/cgroup.procs: No such file or directory
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7456): MountEmulatedStorage()
E/Zygote  ( 7456): v2
I/libpersona( 7456): KNOX_SDCARD checking this for 1000
I/libpersona( 7456): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 5627:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
,I/System.out( 7323): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7456): TimaSignature is unavailable
,D/ActivityThread( 7456): Added TimaKeyStore provider
,W/libprocessgroup(  889): failed to open /acct/uid_10157/pid_5627/cgroup.procs: No such file or directory
,D/ResourcesManager( 7456): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/SMD     (  294): DCD ON
,D/AcmsPackageEventListener( 7456): Received: android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 7456): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 7473): MountEmulatedStorage()
E/Zygote  ( 7473): v2
I/libpersona( 7473): KNOX_SDCARD checking this for 10134
I/libpersona( 7473): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7473 uid=10134 gids={50134, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6409:com.android.vending/u0a29 (adj 15): bgCount ##41
,I/SELinux ( 7473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AcmsService( 7456): Enter Oncreate
D/AcmsServiceMonitor( 7456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 7456): creating AcmsCore
D/AcmsCore( 7456): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7456): AcmsCore
E/SELinux ( 7473): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsCore( 7456): init
D/AcmsCore( 7456): Looper handler is not null
D/AcmsCore( 7456): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7456): Incrementing - Counter value: 1
D/AcmsCore( 7456): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7456): onStartCommand
D/AcmsService( 7456): Action: android.intent.action.PACKAGE_ADDED
,D/AcmsServiceMonitor( 7456): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7456): Incrementing - Counter value: 2
D/AcmsService( 7456): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7456): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 7456): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7456): AcmsRevocationMngr
,D/TimaKeyStoreProvider( 7473): TimaSignature is unavailable
,D/ActivityThread( 7473): Added TimaKeyStore provider
,D/AcmsService( 7456): Inside handle Intent
,D/AcmsService( 7456): App added - package name: com.test.thalitest
D/AcmsCore( 7456): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/ResourcesManager( 7473): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/AcmsServiceMonitor( 7456): Incrementing - Counter value: 3
D/AcmsCore( 7456): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7456): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7456): Decrementing - Counter value: 2
W/ResourcesManager( 7473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup(  889): failed to open /acct/uid_10029/pid_6409/cgroup.procs: No such file or directory
,I/jxcore-log( 7239): JXcore Cordova bridge is ready!
I/jxcore-log( 7239): 
,W/jxcore-log( 7239): JXcore engine is started
,I/jxcore-log( 7239): Toggling radios to true
I/jxcore-log( 7239): 
D/BluetoothAdapter( 7239): enable()
D/BluetoothAdapter( 7239): enable(): BT is already enabled..!
D/WifiService(  889): New client listening to asynchronous messages
I/WifiManager( 7239): packageName : com.test.thalitest
D/SecContentProvider(  889): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  889): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  889): mCursor = null
D/WifiService(  889): setWifiEnabled: true pid=7239, uid=10191
E/WifiService(  889): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  889): Permission Denial: getCurrentUser() from pid=7239, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  889): Failed getting userId using ActivityManagerNative
W/WifiService(  889): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7239, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  889): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  889): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  889): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  889): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  889): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  889): name = wifi_on
I/WifiService(  889): disconnect: pid=7239, uid=10191
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/jxcore-log( 7239): Radios toggled
I/jxcore-log( 7239): 
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/jxcore-log( 7239): My device name is: samsung-SM-G900F
I/jxcore-log( 7239): 
I/wpa_supplicant( 1281): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/wpa_supplicant( 1281): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1281): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  889): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1281): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1281): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1281): Disconnected - do not scan
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  889): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  889): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  889): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  889): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  889): do suspend true
D/WifiP2pService(  889): InactiveState{ what=143375 }
D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
D/CommandListener(  286): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/NativeCrypto( 2188): Read error: ssl=0x9b7b2c00: I/O error during system call, Connection timed out
V/NativeCrypto( 2188): SSL shutdown failed: ssl=0x9b7b2c00: I/O error during system call, Broken pipe
E/WifiStateMachine(  889): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  889): updateNetworkInfo()
D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService(  889): updateNetworkInfo()
D/ConnectivityService(  889): ignoring duplicate network state non-change
I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Validated
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  889): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1281): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1281): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1281): First Scan Start
I/wpa_supplicant( 1281): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  889): ConnectModeState: Network connection lost 
E/WifiStateMachine(  889): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  889): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  889): do suspend true
D/WifiP2pService(  889): InactiveState{ what=143375 }
D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/CommandListener(  286): Clearing all IP addresses on wlan0
D/ConnectivityService(  889): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  889): calling update connectivity
D/EntConnectivity(  889): Not allowed due to - mEnabled false
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  889): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  889): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524292
D/WifiStateMachine(  889): updateConfiguredNetworkExpiration - currTime: 1453370619501
D/WifiStateMachine(  889): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService(  889): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1487): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiNetworkAgent(  889): NetworkAgent: NetworkAgent channel lost
I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
D/CSLegacyTypeTracker(  889): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  889): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  889): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
V/NetworkStats(  889): updateIfacesLocked()
V/NetworkStats(  889): performPollLocked(flags=0x1)
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NetworkStatsFactory(  889): UpdateStatsForKnox
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 2511): CM callback handler got msg 524292
E/ConnectivityService(  889): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  889): setDetailed state send new extra info"NG700"
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
V/NetworkStats(  889): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
V/NetworkStats(  889): performPollLocked() took 11ms
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7522): MountEmulatedStorage()
E/Zygote  ( 7522): v2
I/libpersona( 7522): KNOX_SDCARD checking this for 10165
I/libpersona( 7522): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7522 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 2188): Explicit concurrent mark sweep GC freed 32520(2046KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 20MB/33MB, paused 508us total 39.650ms
I/SELinux ( 7522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/GLSActivity( 2188): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2188): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 7522): TimaSignature is unavailable
D/ActivityThread( 7522): Added TimaKeyStore provider
D/ResourcesManager( 7522): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
W/ResourcesManager( 7522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/KidsPlatformStub( 7522): Package not found : com.sec.android.app.kidshome
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7540): MountEmulatedStorage()
E/Zygote  ( 7540): v2
I/libpersona( 7540): KNOX_SDCARD checking this for 10169
I/libpersona( 7540): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7540 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
I/art     (  321): Explicit concurrent mark sweep GC freed 8763(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 282us total 15.375ms
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.735ms
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 8.057ms
D/AcmsKeyStoreHelper( 7456):  getKeyStoreForApplication Enter
I/SELinux ( 7540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7540): TimaSignature is unavailable
D/ActivityThread( 7540): Added TimaKeyStore provider
I/AcmsKeyStoreHelper( 7456): Key Store exist
I/AcmsKeyStoreHelper( 7456): Hence loading the keystore file
D/ResourcesManager( 7540): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
E/SQLiteLog( 7540): (284) automatic index on shooting_modes(title_id)
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7557): MountEmulatedStorage()
E/Zygote  ( 7557): v2
I/libpersona( 7557): KNOX_SDCARD checking this for 10029
I/libpersona( 7557): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7557 uid=10029 gids={50029, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  889): Killing 6761:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
I/SELinux ( 7557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7557): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7557): TimaSignature is unavailable
D/ActivityThread( 7557): Added TimaKeyStore provider
D/AcmsKeyStoreHelper( 7456):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7456): getKeyStoreForApplication success 
D/AcmsCore( 7456): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7456): Decrementing - Counter value: 1
D/AcmsCore( 7456): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 7456): This is NOT a valid MirrorLink app
D/AcmsCore( 7456): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7456): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7456): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor( 7456): getSvcCounter - Counter value: 0
D/AcmsService( 7456): Enter onDestroy
I/AcmsService( 7456): cleanUp(): inside service clean up
D/AcmsCore( 7456): AcmsCore: inside DeInit
D/AcmsCore( 7456): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7456): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7456): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7456): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7456): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7456): getSvcCounter - Counter value: 0
D/AcmsService( 7456): killing acms process
I/Process ( 7456): Sending signal. PID: 7456 SIG: 9
D/ResourcesManager( 7557): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy(  889): updateDataUsageMap
W/libprocessgroup(  889): failed to open /acct/uid_10010/pid_6761/cgroup.procs: No such file or directory
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2266): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  889): MasterInitialState.processMessage what=3
D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
I/ActivityManager(  889): Process ACMS.Process (pid 7456)(adj 0) has died(50,594)
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
I/CLocInfoService(  889): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
I/CLocInfoService(  889): CLoinfo wifi false
I/DBG_DM  ( 3683): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/SLocation(  889): No Active Data Connection
I/DBG_DM  ( 3683): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
D/Finsky  ( 7557): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7557): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7557): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7557): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7557): Skipping gmscore version check
,D/Finsky  ( 7557): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7557): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7557): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 2511): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Finsky  ( 7557): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 7557): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  889): Killing 6778:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
,D/ChimeraCfgMgr( 2511): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2511): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2511): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10018/pid_6778/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2511): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2511): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2511): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/wpa_supplicant( 1281): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1281): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1281): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1281): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/AsyncTaskServiceImpl( 2511): Submit a task: k
,E/WifiStateMachine(  889): [1,453,370,620,549 ms] noteScanEnd no scan source
,E/WifiStateMachine(  889): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1772f6e3 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  889): setDetailed state send new extra info0x
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
,I/CLocInfoService(  889): External Intent Received android.net.wifi.SCAN_RESULTS
,D/ChimeraCfgMgr( 2511): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2511): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2511): Processing package: com.test.thalitest
,D/GassUtils( 2511): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
,D/k       ( 2511): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 2511): Using Auth Proxy for data requests.
,W/BaseAppContext( 2511): Using Auth Proxy for data requests.
,I/wpa_supplicant( 1281): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 1281): Associated with C0.AA.48
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
,W/art     ( 2511): Suspending all threads took: 12.384ms
,I/wpa_supplicant( 1281): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  889): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  889): mCursor = null
,I/wpa_supplicant( 1281): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1281): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1281): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1281): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1281): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1281): Blacklist: Clear (temp) 
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  889): Network connection established
,D/WifiNative-HAL(  889): callSECApiVoid - ID [50]
,E/WifiStateMachine(  889): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  889): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  889): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  889): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  889): Got NetworkAgent Messenger
D/ConnectivityService(  889): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  889): updateNetworkInfo()
D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  889): NetworkAgent connected
,E/WifiStateMachine(  889): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  889): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  889): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  889): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  286): Setting iface cfg
E/WifiStateMachine(  889): Start Dhcp Watchdog 2
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  889): mCursor = null
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/SQLiteConnectionPool( 2511): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7609): MountEmulatedStorage()
E/Zygote  ( 7609): v2
I/libpersona( 7609): KNOX_SDCARD checking this for 10039
I/libpersona( 7609): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7609 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7609): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7609): TimaSignature is unavailable
,I/PeopleDatabaseHelper( 2511): cleanUpNonGplusAccounts done.
D/ActivityThread( 7609): Added TimaKeyStore provider
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  889): do suspend false
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
,D/WifiP2pService(  889): InactiveState{ what=143375 }
D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
,W/BaseAppContext( 2511): Using Auth Proxy for data requests.
,D/FactoryTest( 6273): Not factory mode
D/ResourcesManager( 7609): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
D/FactoryTest( 6273): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6273): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6273): still no open session command from host, so toast
,W/BaseAppContext( 2511): Using Auth Proxy for data requests.
,W/ContextImpl( 6273): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6273): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6273): Timeline: Activity_launch_request id:com.android.settings time:108446
,E/PersonaManagerService(  889): inState():  stateMachine is null !!
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  889): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  889): mDVFSHelper.acquire()
,V/ActivityManager(  889): Display changed displayId=0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/MTPRx   ( 6273): started activity for popup
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SQLiteSecureOpenHelper( 3477): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3477): getDatabaseLocked(b,b,pwd)...
,I/art     (  889): Explicit concurrent mark sweep GC freed 46155(2MB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 35MB/51MB, paused 1.516ms total 111.129ms
,D/ResourcesManager( 6273): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6273): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6273): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6273): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6273): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/BaseAppContext( 2511): Using Auth Proxy for data requests.
,W/BaseAppContext( 2511): Using Auth Proxy for data requests.
,E/SettingsReceiverActivity( 6273): PREF_DONT_ASK_AGAIN : true
,W/BaseAppContext( 2511): Using Auth Proxy for data requests.
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7627): MountEmulatedStorage()
E/Zygote  ( 7627): v2
I/libpersona( 7627): KNOX_SDCARD checking this for 10157
I/libpersona( 7627): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7627 uid=10157 gids={50157, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6793:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
,E/dhcpcd  ( 7632): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7632): version 5.5.6 starting
,E/dhcpcd  ( 7632): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SELinux ( 7627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
E/SELinux ( 7627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService(  889): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  889): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@c4418e attribute=android.view.inputmethod.EditorInfo@215d5daf, token = android.os.BinderProxy@14d6891f
,D/TimaKeyStoreProvider( 7627): TimaSignature is unavailable
,D/ActivityThread( 7627): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/dhcpcd  ( 7632): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7632): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7632): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7632): bssid match
,I/dhcpcd  ( 7632): wlan0: rebinding lease of 192.168.1.136
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/ResourcesManager( 7627): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/TaskCloserActivity( 7627): TaskCloserActivity enter()
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,W/libprocessgroup(  889): failed to open /acct/uid_10036/pid_6793/cgroup.procs: No such file or directory
V/TaskCloserActivity( 7627): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,I/ActivityManager(  889): Killing 6827:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,D/BootupListener( 1487): ACTION_DRIVELINK
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
D/SettingsProvider(  889): name = drivelink_navigation
D/SettingsProvider(  889): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  889): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  889): selectionArgs: false
D/SettingsProvider(  889): selectionArgs: 1001
D/SecContentProvider(  889): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  889): ret = -1
,D/BootupListener( 1487): NAVI : com.google.android.apps.maps
D/SettingsProvider(  889): name = internet_call_settings_visibility
D/SettingsProvider(  889): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  889): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  889): selectionArgs: false
D/SettingsProvider(  889): selectionArgs: 1001
D/SecContentProvider(  889): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  889): ret = -1
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6273): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SecurityLogAgent( 6877):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SettingsReceiverActivity( 6273): dev.kiessupport is : TRUE
,D/SecurityLogAgent( 6877):  SeDenialReceiver : File path = null
,I/Hs20UtilService( 1316): Starting #6
,I/Hs20UtilService( 1316): Message received 5007
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/Activity( 6273): performCreate Call secproduct feature valuefalse
D/Activity( 6273): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/Hs20UtilService( 1316): Starting #7
,I/Hs20UtilService( 1316): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
D/ActivityManager(  889): post active user change for 0
D/KnoxTimeoutHandler(  889): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  889): handleActiveUserChange for user 0
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,I/PCWCLIENTTRACE_PushUtil( 7048): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7048): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7048): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7048): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  889): failed to open /acct/uid_10066/pid_6827/cgroup.procs: No such file or directory
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7048): noConnectivity : true
,E/Zygote  ( 7652): MountEmulatedStorage()
,E/Zygote  ( 7652): v2
I/libpersona( 7652): KNOX_SDCARD checking this for 10125
I/libpersona( 7652): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7652 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Timeline( 7239): Timeline: Activity_idle id: android.os.BinderProxy@251eedb4 time:108830
,I/SELinux ( 7652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SELinux ( 7652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7652): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7652): TimaSignature is unavailable
,D/ActivityThread( 7652): Added TimaKeyStore provider
,D/ResourcesManager( 7652): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore( 7652): Database version: 104
,D/ResourcesManager( 7652): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7652): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7652): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/JNIHelp ( 7652): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7652): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7652): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1aaac957: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7652): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7652): GMSCore installation verified
,W/art     ( 2511): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 187.520ms
,I/ConfigStore( 7652): Config Database version: 1
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7652): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7652): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7652): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  889): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  889): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  299): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  889): getStreamVolume 3 index 0
,I/MediaRouter( 7652): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7678): MountEmulatedStorage()
E/Zygote  ( 7678): v2
I/libpersona( 7678): KNOX_SDCARD checking this for 10002
I/libpersona( 7678): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7678 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 2511): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2511): Module APK com.google.android.play.games already loaded
,I/SELinux ( 7678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  889): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7652): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7678): TimaSignature is unavailable
,D/ActivityThread( 7678): Added TimaKeyStore provider
,I/ActivityManager(  889): Killing 6722:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,D/ResourcesManager( 7678): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/Icing   ( 2511): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,W/libprocessgroup(  889): failed to open /acct/uid_10070/pid_6722/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Killing 6843:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
I/libpersona( 7700): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7700 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GAV2    ( 7218): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/ActivityThread( 7700): Added TimaKeyStore provider
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ResourcesManager( 2511): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10090/pid_6843/cgroup.procs: No such file or directory
,E/SMD     (  294): DCD ON
,I/DIAGMON_AGENT( 7700): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/Icing   ( 2511): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/DIAGMON_AGENT( 7700): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7700): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7700): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7718): MountEmulatedStorage()
,E/Zygote  ( 7718): v2
I/libpersona( 7718): KNOX_SDCARD checking this for 10010
I/libpersona( 7718): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7718 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7718): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7718): TimaSignature is unavailable
,D/ActivityThread( 7718): Added TimaKeyStore provider
,D/ResourcesManager( 7718): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  889): Killing 6858:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,I/FOTA_Client( 7718): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7718): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7718): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7736): MountEmulatedStorage()
E/Zygote  ( 7736): v2
I/libpersona( 7736): KNOX_SDCARD checking this for 10018
I/libpersona( 7736): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7736 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 5857:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,V/AlarmManager(  889): waitForAlarm result :4
,I/SELinux ( 7736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7736): TimaSignature is unavailable
,D/ActivityThread( 7736): Added TimaKeyStore provider
,D/ResourcesManager( 7736): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7736): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7736): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453370622420
,I/KLMS-2.4.503: ( 7736): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7736): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7736): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  889): Killing 5560:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7756): MountEmulatedStorage()
I/libpersona( 7756): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7756): v2
I/libpersona( 7756): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7756 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7756): TimaSignature is unavailable
,D/ActivityThread( 7756): Added TimaKeyStore provider
,D/ResourcesManager( 7756): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10103/pid_6858/cgroup.procs: No such file or directory
,W/libprocessgroup(  889): failed to open /acct/uid_10112/pid_5857/cgroup.procs: No such file or directory
,I/SO_AGENT( 7756): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7085): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6809): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6809): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6809): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6809): [SLFUCHKMGR] constructor called
,W/libprocessgroup(  889): failed to open /acct/uid_10148/pid_5560/cgroup.procs: No such file or directory
,I/SA      ( 6809): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6809): [OR] == isSIMCardReady false ==
,I/SA      ( 6809): [SCU] == networkStateCheck == false
I/SA      ( 6809): [OR] onReceive END
,E/SPPClientService( 7085): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7775): MountEmulatedStorage()
,E/Zygote  ( 7775): v2
I/libpersona( 7775): KNOX_SDCARD checking this for 10070
I/libpersona( 7775): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7775 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  889): Killing 4633:com.android.calendar/u0a149 (adj 15): bgCount ##41
I/SELinux ( 7775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7775): TimaSignature is unavailable
,D/ActivityThread( 7775): Added TimaKeyStore provider
,D/ResourcesManager( 7775): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7775): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7775): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7775): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7775): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7775): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7775): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7775): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7775): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7775): [KK AccuPhone]>>> ==============================================================================================
,W/libprocessgroup(  889): failed to open /acct/uid_10149/pid_4633/cgroup.procs: No such file or directory
,D/SettingsProvider(  889): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  889): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  889): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  889): selectionArgs: false
D/SettingsProvider(  889): selectionArgs: 10070
D/SecContentProvider(  889): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  889): ret = -1
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7775): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7775): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7775): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7775): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7775): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7775): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7775): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7775): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1342): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7775): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7775): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7795): MountEmulatedStorage()
,E/Zygote  ( 7795): v2
I/libpersona( 7795): KNOX_SDCARD checking this for 1000
I/libpersona( 7795): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7795 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  889): Killing 6893:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/art     (  321): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 13.138ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.050ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.660ms
,I/SELinux ( 7795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7795): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7795): TimaSignature is unavailable
,W/libprocessgroup(  889): failed to open /acct/uid_10175/pid_6893/cgroup.procs: No such file or directory
,D/ActivityThread( 7795): Added TimaKeyStore provider
,D/ResourcesManager( 7795): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7795): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7795): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7795): premStatus:2
,I/KnoxUsageLogPro( 7795): isEulaShown : false
,I/KnoxUsageLogPro( 7795): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7810): MountEmulatedStorage()
E/Zygote  ( 7810): v2
I/libpersona( 7810): KNOX_SDCARD checking this for 10087
I/libpersona( 7810): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7810 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6908:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,I/SELinux ( 7810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7810): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/PowerManagerService(  889): [PWL] Off : 5s ago
,I/PowerManagerService(  889): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  889): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  889): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=889, ws=null) (elapsedTime=3383)
I/PowerManagerService(  889): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=889, ws=WorkSource{10058}) (elapsedTime=532)
,D/TimaKeyStoreProvider( 7810): TimaSignature is unavailable
,D/ActivityThread( 7810): Added TimaKeyStore provider
,D/ResourcesManager( 7810): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/libprocessgroup(  889): failed to open /acct/uid_1000/pid_6908/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Killing 5984:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,D/Headlines( 5387): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5387): getCountryCode(): countryCode = PL
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5387): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5387): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5387): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5387): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5387): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5387): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5387): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7826): MountEmulatedStorage()
I/libpersona( 7826): KNOX_SDCARD checking this for 10127
E/Zygote  ( 7826): v2
I/libpersona( 7826): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7826 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7826): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7826): TimaSignature is unavailable
,D/ActivityThread( 7826): Added TimaKeyStore provider
,D/ResourcesManager( 7826): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10045/pid_5984/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7632): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/dhcpcd  ( 7632): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7826): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7826): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7826): Loading: webviewchromium
,I/LibraryLoader( 7826): Time to load native libraries: 7 ms (timestamps 995-1002)
I/LibraryLoader( 7826): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7826): Binding Chromium to main looper Looper (main, tid 1) {2fa8a3f3}
,I/LibraryLoader( 7826): Expected native library version number "",actual native library version number ""
I/chromium( 7826): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  889): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  889): do suspend true
,D/WifiP2pService(  889): InactiveState{ what=143375 }
,D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  889): WifiStateMachine DHCP successful
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/BrowserStartupController( 7826): Initializing chromium process, renderers=0
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  889): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  889): Not connected state, yet.
E/WifiStateMachine(  889): VerifyingLinkState enter
W/art     ( 7826): Attempt to remove local handle scope entry from IRT, ignoring
,D/WifiStateMachine(  889): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  889): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  889): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  889): callSECApiInt - ID [210]
,E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  889): updateNetworkInfo()
,D/ConnectivityService(  889): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  889): Adding iface wlan0 to network 503
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  889): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/chromium( 7826): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7826): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7826): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid( 7826): Requires BLUETOOTH permission
E/WifiStateMachine(  889): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  889): Now, connected state.
E/WifiStateMachine(  889): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/ConnectivityService(  889): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine(  889): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
I/Adreno-EGL( 7826): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7826): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7826): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7826): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7826): Remote Branch: 
I/Adreno-EGL( 7826): Local Patches: 
I/Adreno-EGL( 7826): Reconstruct Branch: 
I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  889): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService(  889): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/ConnectivityService(  889): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  889): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  889): updateSourceRoutes : add src route for:192.168.1.136
V/        (  286): QcRouteController
,I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  889): mBoosterFLAG : 0
I/WifiTrafficPoller(  889): current booster mode : FullMode
D/WifiNative-HAL(  889): callSECApiVoid - ID [212]
E/WifiStateMachine(  889): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/        (  286): QcRouteController
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
E/WifiStateMachine(  889): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiStateMachine(  889): REQUEST_POWER_SAVE_ON
V/        (  286): QcRouteController
V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,V/        (  286): QcRouteController
,I/NSApplication( 7826): Starting up...
,V/        (  286): QcRouteController
,I/ActivityManager(  889): Killing 7015:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/ConnectivityService(  889): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  889): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
,E/ConnectivityService(  889): updateNetworkInfo()
D/ConnectivityService(  889): ignoring duplicate network state non-change
E/ConnectivityService(  889): updateNetworkInfo()
D/ConnectivityService(  889): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Connected
D/ConnectivityService(  889): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  889): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Validated
D/ConnectivityService(  889): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889): currentScore = 0, newScore = 60
,D/ConnectivityService(  889):    accepting network in place of null
D/ConnectivityService(  889): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1487): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  889): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  889): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7925): MountEmulatedStorage()
,E/Zygote  ( 7925): v2
I/libpersona( 7925): KNOX_SDCARD checking this for 10137
I/libpersona( 7925): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7925 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/ConnectivityService(  889): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,W/art     ( 7473): Suspending all threads took: 6.363ms
D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
,D/ConnectivityService(  889): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
V/NetworkStats(  889): updateIfacesLocked()
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
V/NetworkStats(  889): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  889): UpdateStatsForKnox
D/EntConnectivity(  889): Not allowed due to - mEnabled false
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
,D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/NetworkStats(  889): performPollLocked() took 3ms
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/ConnectivityService(  889): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService(  889): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
,D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  889): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 7239): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7239): 
I/SELinux ( 7925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 7925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
V/NetworkStats(  889): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 2511): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/ConnectivityManager.CallbackHandler( 2511): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/TimaKeyStoreProvider( 7925): TimaSignature is unavailable
,D/ActivityThread( 7925): Added TimaKeyStore provider
,D/ResourcesManager( 7925): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10014/pid_7015/cgroup.procs: No such file or directory
,W/ResourcesManager( 7925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7925): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7925): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7925): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7925): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7925): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7941): MountEmulatedStorage()
,E/Zygote  ( 7941): v2
I/libpersona( 7941): KNOX_SDCARD checking this for 10162
I/libpersona( 7941): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7941 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 7033:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7941): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7941): TimaSignature is unavailable
,D/ActivityThread( 7941): Added TimaKeyStore provider
,W/ActivityManager(  889): mDVFSHelper.release()
,D/ResourcesManager( 7941): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7941): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7941): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  889): failed to open /acct/uid_10015/pid_7033/cgroup.procs: No such file or directory
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7963): MountEmulatedStorage()
E/Zygote  ( 7963): v2
I/libpersona( 7963): KNOX_SDCARD checking this for 10077
I/libpersona( 7963): KNOX_SDCARD not a persona
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  889): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7963 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,I/SELinux ( 7963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/RCPManagerService(  889): exchangeData() failure , invalid userId
I/SELinux ( 7963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7963): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/TimaKeyStoreProvider( 7963): TimaSignature is unavailable
,D/ActivityThread( 7963): Added TimaKeyStore provider
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6877): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6877): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6877): StateMachine : Current State = 1
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6877): StateMachine : Changed Current State = 1
,I/ActivityManager(  889): Killing 6299:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  889): Killing 4792:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/BadgeProvider( 7963): onCreate
D/BadgeProvider( 7963): DatabaseHelper
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
I/libpersona( 7979): KNOX_SDCARD checking this for 10177
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
I/libpersona( 7979): KNOX_SDCARD not a persona
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
E/Zygote  ( 7979): MountEmulatedStorage()
E/Zygote  ( 7979): v2
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,I/ActivityManager(  889): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7979 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/Tethering(  889): MasterInitialState.processMessage what=3
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 7979): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  889): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  889): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  889): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
,I/CLocInfoService(  889): CLocinfo wifi true 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2173): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2173): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2266): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7652): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7979): TimaSignature is unavailable
,D/ActivityThread( 7979): Added TimaKeyStore provider
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3683): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3683): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/BadgeProvider( 7963): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/ResourcesManager( 7979): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
V/BitmapFactory( 7941): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 7963): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7963): sendNotify, [notify] : null
D/BadgeProvider( 7963): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7963): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7963): update, [UpdateCount] : 1
,D/Launcher.Model( 1493): reloadBadges entered.
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,W/libprocessgroup(  889): failed to open /acct/uid_10033/pid_6299/cgroup.procs: No such file or directory
,W/libprocessgroup(  889): failed to open /acct/uid_10034/pid_4792/cgroup.procs: No such file or directory
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7239): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7239): 
,I/jxcore-log( 7239): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7239): 
,I/art     (  889): Explicit concurrent mark sweep GC freed 37868(2MB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 35MB/51MB, paused 1.292ms total 87.627ms
,I/GAV2    ( 7473): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  889): Killing 7105:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  889): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,V/GLSActivity( 2188): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 7239): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7239): 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 2188): Vacuum at: now=1453370624466 tag=VacuumService
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7609): notifyNetworkActivated
,W/libprocessgroup(  889): failed to open /acct/uid_10041/pid_7105/cgroup.procs: No such file or directory
,I/jxcore-log( 7239): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7239): 
,I/jxcore-log( 7239): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7239): 
,I/jxcore-log( 7239): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7239): 
,W/ContextImpl( 7609): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  889): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7609): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7609): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7609): exit::IDLE
D/InitializeManagerStateMachine( 7609): entry::NETWORK_CHECK
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1316): Starting #8
,I/Hs20UtilService( 1316): Message received 5007
D/InitializeManagerStateMachine( 7609): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7609): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7609): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7609): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7609): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7609): entry::SUCCESS
D/hcjo    ( 7609): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/KeyguardViewMediator( 1184): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/hcjo    ( 7609): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7609): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PersonaManager( 1184): isKioskContainerExistOnDevice
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/InitializeManagerStateMachine( 7609): exit::SUCCESS
,D/LockPatternUtilsCache( 1184): value : false
D/InitializeManagerStateMachine( 7609): entry::IDLE
D/KeyguardViewMediator( 1184): doKeyguard: not showing because lockscreen is off
,I/Hs20UtilService( 1316): Starting #9
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1316): Message received 5007
,I/ActivityManager(  889): Killing 5765:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,I/Hs20UtilService( 1316): Starting #10
,D/ConnectivityService(  889): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/Hs20UtilService( 1316): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1316): Starting #11
,I/Hs20UtilService( 1316): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  889): callSECApi what=220
,D/WifiStateMachine(  889): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7048): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7048): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7048): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7048): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  258): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup(  889): failed to open /acct/uid_10047/pid_5765/cgroup.procs: No such file or directory
,D/PowerManagerService(  889): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=889
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/FOTA_Client( 7718): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/FOTA_Client( 7718): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7718): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7736): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7736): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453370624807
,I/KLMS-2.4.503: ( 7736): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7736): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7736): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7736): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/KLMS-2.4.503: ( 7736): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7756): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7085): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6809): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6809): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6809): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6809): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6809): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6809): [SCU] == networkStateCheck == true
I/SA      ( 6809): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6809): isChinaCountryCode : false
I/SA      ( 6809): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6809): [OR] == networkStateCheck true ==
,I/SA      ( 6809): [OR] GetMyCountryZoneTask
,I/SA      ( 6809): [OR] onReceive END
,I/SA      ( 6809): [SRS] prepareGetMyCountryZone
,I/SA      ( 6809): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6809): [SSP] query invoked
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7775): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7775): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6809): [TPMU] GetMccFromDB : null
I/SA      ( 6809): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6809): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7795): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7795): premStatus:2
,I/KnoxUsageLogPro( 7795): isEulaShown : false
I/KnoxUsageLogPro( 7795): KnoxUsageReceiver onReceive : not Processible, just return
,D/Headlines( 5387): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
E/File    ( 6809): fail readDirectory() errno=2
,D/HeadlinesChannelUtil( 5387): getCountryCode(): countryCode = PL
,D/Headlines( 5387): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5387): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5387): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5387): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5387): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5387): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5387): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7925): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7925): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7925): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6877): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6877): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6877): StateMachine : Current State = 1
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6877): StateMachine : Changed Current State = 1
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7609): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7609): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7609): exit::IDLE
D/InitializeManagerStateMachine( 7609): entry::NETWORK_CHECK
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7609): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7609): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7609): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7609): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7609): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7609): entry::SUCCESS
D/hcjo    ( 7609): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7609): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7609): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7609): exit::SUCCESS
D/InitializeManagerStateMachine( 7609): entry::IDLE
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/PackageManager(  889): [MSG] MCS_UNBIND
,I/ActivityManager(  889): Killing 5644:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/CountryDetector(  889): No listener is left
,W/libprocessgroup(  889): failed to open /acct/uid_10049/pid_5644/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7632): wlan0: sending IPv6 Router Solicitation
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  889): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  889): identical MTU - not setting
D/ConnectivityService(  889): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  889): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  286): QcRouteController
,E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
,V/        (  286): QcRouteController
,W/NetworkManagementService(  889): route cmd failed: 
W/NetworkManagementService(  889): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  889): '
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  889): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  889): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  889): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  889): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
,D/ConnectivityService(  889): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
,D/ConnectivityService(  889): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2511): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2511): CM callback handler got msg 524295
,I/SA      ( 6809): [RC New] Execute method=[GET] start
,I/SA      ( 6809): [RC New] Security=[true]
,I/System.out( 6809): Thread-1066(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6809): Thread-1066(ApacheHTTPLog):isShipBuild true
,I/System.out( 6809): Thread-1066(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager(  889): waitForAlarm result :8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/SA      ( 6809): [RC New] [v2liruge] api execute + 959
,I/SA      ( 6809): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6809): AsyncTask #1 calls detatch()
,I/SA      ( 6809): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6809): [OCP] update openData : PL
,I/SA      ( 6809): [TPMU] getNetworkMcc : 
,I/SA      ( 6809): [SCU] saveMccToPreferece Start
,I/SA      ( 6809): [SCU] RegionMCC : 260
I/SA      ( 6809): [SSP] query invoked
,I/SA      ( 6809): [TPMU] GetMccFromDB : null
,I/SA      ( 6809): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6809): [SCU] saveMccToPreferece End
,I/SA      ( 6809): [RC New] executeRequest [v2liruge] end. 1011
,I/SA      ( 6809): [RC New] Execute end
,I/SA      ( 6809): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6809): [OR] GetMyCountryZoneTask Success
,D/WearableService( 2188): callingUid 10011, callindPid: 2188
,D/ResourcesManager( 7652): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7652): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7652): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7652): Using the GMSCore's GoogleHttpClient
,I/WifiStateMachine(  889): REQUEST_POWER_SAVE_ON
,D/WearableClient( 7652): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7652): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7652): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7652): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7652): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7652): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/WifiStateMachine(  889): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/MusicLeanback( 7652): Conditions not met for autocaching.
I/MusicLeanback( 7652): Stop autocaching.
,E/ActivityThread( 7652): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@226f00e9 that was originally bound here
E/ActivityThread( 7652): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@226f00e9 that was originally bound here
E/ActivityThread( 7652): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7652): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7652): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7652): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7652): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7652): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7652): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7652): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7652): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7652): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7652): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7652): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7652): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7652): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7652): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7652): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7652): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7652): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7652): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7652): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7652): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7652): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 420, PST = 362, CUR = 450
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/SurfaceFlinger(  258): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  258): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/PowerManagerService(  889): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 889) eventTime = 115806
,D/PowerManagerService(  889): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=889 (0x0)
D/PowerManagerService(  889): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=889, ws=WorkSource{10058}) (elapsedTime=3475)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,I/GAV4    ( 7826): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7632): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 7239): Test app app.js loaded
I/jxcore-log( 7239): 
,I/chromium( 7239): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7239): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7239): BLE advertisement is supported
I/jxcore-log( 7239): 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7048): mConnectivityHandler : connected
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7048): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7048): [GetString-S]
,I/ReactiveServiceManager( 7048): Supported : 1
,D/QSEECOMAPI: (  889): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: (  889): App is not loaded in QSEE
,D/QSEECOMAPI: (  889): Loaded image: APP id = 2
,D/QSEECOMAPI: (  889): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  889): QSEECom_shutdown_app, app_id = 2
,E/terrier (  889): handleString: Failed to handle string(-4)
E/terrier (  889): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 7048): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7048): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7048): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7048): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7048): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7048): [ensureRegistration] - No Samsung account
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 15s ago
,I/dhcpcd  ( 7632): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7632): wlan0: no IPv6 Routers available
,E/SMD     (  294): DCD ON
,D/PreloadUpdateManagerStateMachine( 7609): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7609): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7609): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7609): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7609): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7609): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7609): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7609): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7609): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7609): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7609): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7609): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7609): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7609): entry::IDLE
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  889): waitForAlarm result :4
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 2188): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2188): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7557): [1240] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7557): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 350, PST = 354, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ActivityManager(  889): Waited long enough for: ServiceRecord{28f8f5d6 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  294): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/Watchdog(  889): !@Sync 4
,E/SMD     (  294): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,I/PowerManagerService(  889): [PWL] Off : 30s ago
,I/PowerManagerService(  889): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  889): [PWL]     mWakeLockSummary : 0x1
,D/SSRM:m  (  889): SIOP:: AP = 320, PST = 346, CUR = 450
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...,
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  889): SIOP:: AP = 310, PST = 343, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 50s ago
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 340, CUR = 450
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  889): !@Sync 5
,E/SMD     (  294): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2188): Scheduling Phenotype for one-off execution 12836 seconds from now (1453370677245)
,D/GetConfigurationSnapshotOperation( 2188): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2188): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2188): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  889): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 2188): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2188): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2188): (HTTPLog)-Thread-299-847492404: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2188): Tagging socket 71 with tag 1000120100000000{268440065,0} uid -1, pid: 2188, getuid(): 10011
,I/qtaguid ( 2188): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 2188, getuid(): 10011
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 336, CUR = 450
,D/LocationManagerService(  889): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2188): Tagging socket 71 with tag 1000120100000000{268440065,0} uid -1, pid: 2188, getuid(): 10011
,D/LocationManagerService(  889): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2188): Tagging socket 71 with tag 1000120100000000{268440065,0} uid -1, pid: 2188, getuid(): 10011
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 332, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 75s ago
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 329, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/Watchdog(  889): !@Sync 6
,E/SMD     (  294): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 2188): disconnect managed GoogleApiClient
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 324, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 315, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 105s ago
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 270, PST = 300, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/Watchdog(  889): !@Sync 7
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 270, PST = 292, CUR = 450
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  889): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7239): --= Surplus to requirements =--
I/jxcore-log( 7239): 
,I/jxcore-log( 7239): ****TEST TOOK:  ms ****
I/jxcore-log( 7239): 
I/jxcore-log( 7239): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7239): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 8173): 
D/AndroidRuntime( 8173): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8173): CheckJNI is OFF
,D/AndroidRuntime( 8173): setted country_code = Poland
,D/AndroidRuntime( 8173): setted countryiso_code = PL
,D/AndroidRuntime( 8173): setted sales_code = XEO
,D/AndroidRuntime( 8173): readGMSProperty: start
,D/AndroidRuntime( 8173): readGMSProperty: already setted!!
D/AndroidRuntime( 8173): readGMSProperty: end
D/AndroidRuntime( 8173): addProductProperty: start
,E/AffinityControl( 8173): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8173): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  889): START PACKAGE DELETE: observer{50555030}
D/PackageManager(  889): pkg{<packageName>}
D/PackageManager(  889): user{0}
D/PackageManager(  889): caller{2000}
D/PackageManager(  889): flags{3}
,D/PersonaManagerService(  889): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  889): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  889): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  889): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  889): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  889): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  889): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  889): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  889): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  889): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  889): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  889): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  889): Killing 7239:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  889):   Force finishing activity ActivityRecord{20287f3f u0 com.test.thalitest/.MainActivity t9}
,D/FocusedStackFrame(  889): Set to : 0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SurfaceFlinger(  258): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  258): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/WifiService(  889): Client connection lost with reason: 4
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  889): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,I/art     ( 2511): Explicit concurrent mark sweep GC freed 31286(1961KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 21MB/35MB, paused 539us total 35.663ms
,I/art     ( 1584): Explicit concurrent mark sweep GC freed 10378(695KB) AllocSpace objects, 1(39KB) LOS objects, 40% free, 16MB/27MB, paused 452us total 76.998ms
,I/art     ( 6150): Explicit concurrent mark sweep GC freed 31805(1724KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 411us total 37.496ms
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader(  889): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1493): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1493): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1493): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1493): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SamsungIME( 1872): mOCRHelper is null
,D/ResourcesManager( 1493): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/GeofencerStateMachine( 2188): Ignoring removeGeofence because network location is disabled.
,E/libprocessgroup(  889): failed to kill 1 processes for processgroup 7239
,W/ResourcesManager( 1493): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1493): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/KLMS-2.4.503: ( 7736): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7736): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453370747969
,I/art     (  889): Explicit concurrent mark sweep GC freed 52395(3MB) AllocSpace objects, 41(656KB) LOS objects, 31% free, 35MB/51MB, paused 5.038ms total 126.667ms
,D/ResourcesManager(  889): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  889): WaitForGcToComplete blocked for 102.933ms for cause Explicit
,I/KLMS-2.4.503: ( 7736): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7736): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/SMD     (  294): DCD ON
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/RegisteredServicesCache( 1475): empty dynamic service
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/EnterpriseDeviceManagerService(  889): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  889): Admin package name: com.google.android.gms
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,E/Zygote  ( 8202): MountEmulatedStorage()
E/Zygote  ( 8202): v2
I/libpersona( 8202): KNOX_SDCARD checking this for 10103
I/libpersona( 8202): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8202 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/SELinux ( 8202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/art     (  889): Explicit concurrent mark sweep GC freed 9925(494KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 2.209ms total 175.674ms
,D/TimaKeyStoreProvider( 8202): TimaSignature is unavailable
,D/ActivityThread( 8202): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager( 8202): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/SurfaceWidgetView( 1493): destroyHardwareResources():361828825
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  889): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/RCPManagerService(  889): PackageReceiver onReceive()
,I/HarmonyEASService(  889): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/Launcher( 1493): onRestart, Launcher: 37173391
,D/Launcher( 1493): onStart, Launcher: 37173391
D/Launcher.HomeView( 1493): onStart
,D/KnoxMUMContainerPolicy(  889): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2266): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2266): [237392/6] SurfaceWidget drawing first frame
,D/BackupManagerService(  889): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  889): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  889): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  889): uID is 10191
V/EnterpriseBillingPolicy(  889): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  889): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  889): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  889): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  889): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  889): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  889): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  889): removeObsoleteFile: deleting file=9_task.xml
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SurfaceFlinger(  258): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  889): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/StatusBarManagerService(  889): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/elm:14451( 8202): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8202): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8202): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8202): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/elm:14451( 8202): ElmAgentService : onCreate()
,D/InputMethodManagerService(  889): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  ( 8221): MountEmulatedStorage()
E/Zygote  ( 8221): v2
I/libpersona( 8221): KNOX_SDCARD checking this for 10016
I/libpersona( 8221): KNOX_SDCARD not a persona
,D/elm:14451( 8202): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  889): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8221 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,W/InputMethodManagerService(  889): Got RemoteException sending setActive(false) notification to pid 7239 uid 10191
,D/elm:14451( 8202): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 8202): MDMBridge.getInstance()
D/elm:14451( 8202): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SELinux ( 8221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/SELinux ( 8221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8221): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/elm:14451( 8202): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  889): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/TimaKeyStoreProvider( 8221): TimaSignature is unavailable
,D/ActivityThread( 8221): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/Timeline(  889): Timeline: Activity_windows_visible id: ActivityRecord{2c134089 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:235921
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/elm:14451( 8202): ElmAgentService : onDestroy().
,I/ActivityManager(  889): Killing 7135:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,D/ResourcesManager( 8221): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/SSRM:m  (  889): SIOP:: AP = 270, PST = 287, CUR = 450
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager(  889): delete codoeFile: 
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/PackageManager(  889): result of delete: 1{50555030}
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8221): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8221): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8221): onReceive() : package name is not s health. Return !!!
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/AndroidRuntime( 8173): Shutting down VM
,I/PCWCLIENTTRACE_PushUtil( 7048): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7048): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7048): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7048): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10050/pid_7135/cgroup.procs: No such file or directory
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 8238): MountEmulatedStorage()
E/Zygote  ( 8238): v2
I/libpersona( 8238): KNOX_SDCARD checking this for 10033
I/libpersona( 8238): KNOX_SDCARD not a persona
,D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,I/ActivityManager(  889): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8238 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  889): Killing 7154:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  889): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  889): onPackageRemoved : com.test.thalitest
,I/SELinux ( 8238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8238): TimaSignature is unavailable
,D/ActivityThread( 8238): Added TimaKeyStore provider
,W/libprocessgroup(  889): failed to open /acct/uid_10057/pid_7154/cgroup.procs: No such file or directory
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 8238): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8255): MountEmulatedStorage()
E/Zygote  ( 8255): v2
I/libpersona( 8255): KNOX_SDCARD checking this for 10034
I/libpersona( 8255): KNOX_SDCARD not a persona
,I/SELinux ( 8255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  889): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8255 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 7174:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 8255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8255): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8255): TimaSignature is unavailable
,D/ActivityThread( 8255): Added TimaKeyStore provider
,W/libprocessgroup(  889): failed to open /acct/uid_1000/pid_7174/cgroup.procs: No such file or directory
,D/ResourcesManager( 8255): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,F/libc    ( 8255): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78567f8f in tid 8255 (oid.app.shealth)
,E/audit_log( 2119): File locking failed. error= Bad file number
E/audit_log( 2119): File locking failed. error= Bad file number
,I/ActivityManager(  889): Process com.sec.android.app.shealth (pid 8255)(adj 0) has died(241,537)
,I/EventHub(  889): Removing device '/dev/input/event4' due to inotify event
,I/Zygote  (  321): Process 8255 exited due to signal (7)
,F/libc    ( 7085): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7764ea00 in tid 7085 (om.sec.spp.push)
,F/libc    ( 7085): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2119): File locking failed. error= Bad file number
,I/ActivityManager(  889): Process com.sec.spp.push (pid 7085)(adj 0) has died(246,538)
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,I/EventHub(  889): Removing device '/dev/input/event5' due to inotify event
,E/Zygote  ( 8275): MountEmulatedStorage()
,E/Zygote  ( 8275): v2
I/libpersona( 8275): KNOX_SDCARD checking this for 10037
I/libpersona( 8275): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8275 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 293us total 17.079ms
,I/Zygote  (  321): Process 7085 exited due to signal (7)
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 8.531ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.227ms
,I/SELinux ( 8275): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8275): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  889): Removing device '/dev/input/event6' due to inotify event
,D/TimaKeyStoreProvider( 8275): TimaSignature is unavailable
,D/ActivityThread( 8275): Added TimaKeyStore provider
,D/ResourcesManager( 8275): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8275): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8275): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  889): Removing device '/dev/input/event7' due to inotify event
,F/libc    ( 8275): Fatal signal 7 (SIGBUS), code 2, fault addr 0xaf99827d in tid 8275 (moteNotiProcess)
F/libc    ( 8275): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2119): File locking failed. error= Bad file number
,I/ActivityManager(  889): Process com.sec.spp.push:RemoteNotiProcess (pid 8275)(adj 0) has died(245,538)
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8290): MountEmulatedStorage()
,I/EventHub(  889): Removing device '/dev/input/event8' due to inotify event
E/Zygote  ( 8290): v2
I/libpersona( 8290): KNOX_SDCARD checking this for 10041
I/libpersona( 8290): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8290 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/Zygote  (  321): Process 8275 exited due to signal (7)
,I/SELinux ( 8290): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8290): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  889): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider( 8290): TimaSignature is unavailable
,D/ActivityThread( 8290): Added TimaKeyStore provider
,D/ResourcesManager( 8290): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8290): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8290): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 8290): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 8290): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 8290): Shutting down VM
,F/libc    ( 8290): Fatal signal 7 (SIGBUS), code 2, fault addr 0x72800151 in tid 8290 (sdk.samsunglink)
,F/libc    ( 8290): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2119): File locking failed. error= Bad file number
,I/EventHub(  889): Removing device '/dev/input/event10' due to inotify event
,I/ActivityManager(  889): Process com.samsung.android.sdk.samsunglink (pid 8290)(adj 0) has died(245,538)
,I/SA      ( 6809): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6809): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10191 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1797): Fatal signal 7 (SIGBUS), code 2, fault addr 0x772a2dd4 in tid 1797 (d.process.acore)
,F/libc    ( 1797): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2119): File locking failed. error= Bad file number
,I/EventHub(  889): Removing device '/dev/input/event11' due to inotify event
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/Zygote  (  321): Process 8290 exited due to signal (7)
,I/ActivityManager(  889): Process android.process.acore (pid 1797)(adj 0) has died(249,538)
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8310): MountEmulatedStorage()
,E/Zygote  ( 8310): v2
I/libpersona( 8310): KNOX_SDCARD checking this for 10047
I/libpersona( 8310): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8310 uid=10047 gids={50047, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/Zygote  (  321): Process 1797 exited due to signal (7)
,I/SELinux ( 8310): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8310): TimaSignature is unavailable
D/ActivityThread( 8310): Added TimaKeyStore provider
,D/ResourcesManager( 8310): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8310): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8310): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8310): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8310): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8310): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8310): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8310): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ContextImpl( 8310): Unable to create files subdir /data/data/com.sec.android.gallery3d/cache
E/ActivityThread( 8310): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8310): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb44e8000 in tid 8310 (droid.gallery3d)
,F/libc    ( 8310): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2119): File locking failed. error= Bad file number
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  889): Process com.sec.android.gallery3d (pid 8310)(adj 0) has died(249,539)
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8325): MountEmulatedStorage()
E/Zygote  ( 8325): v2
I/libpersona( 8325): KNOX_SDCARD checking this for 10049
I/libpersona( 8325): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8325 uid=10049 gids={50049, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/Zygote  (  321): Process 8310 exited due to signal (7)

```
