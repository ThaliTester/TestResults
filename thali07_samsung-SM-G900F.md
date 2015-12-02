#### Test 50388019193a02f_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/ResourcesManager( 5628): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/AssistantMenuSettingSearch( 5628): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5628): Make Setting DB
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
W/ContextImpl( 5628): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
,I/NotifUtils( 5560): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
I/NotifUtils( 5560): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
I/NotifUtils( 5560): Showing notification with unreadCount of 7 and unseenCount of 7
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5660): MountEmulatedStorage()
E/Zygote  ( 5660): v2
I/libpersona( 5660): KNOX_SDCARD checking this for 1000
I/libpersona( 5660): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5660 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  318): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 410us total 13.925ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 7.728ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 8.923ms
D/TimaKeyStoreProvider( 5660): TimaSignature is unavailable
D/ActivityThread( 5660): Added TimaKeyStore provider
D/ResourcesManager( 5660): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
D/PopupuiReceiver( 5660): onReceive() getAction : com.android.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2(  897): uri = -1 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
I/PopupuiReceiver_KNOX( 5660): getSealedState : true
D/SecContentProvider2(  897): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
I/PopupuiReceiver_KNOX( 5660): getSealedHideNotificationMessages : 1
D/SecContentProvider2(  897): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
I/PopupuiReceiver_KNOX( 5660): getCheckCoverPopupState : true
W/ContextImpl( 5660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:407 android.app.ActivityThread.handleReceiver:2945 
D/PopupuiReceiver( 5660): Action cable connected ! on - 
D/PopupuiReceiver( 5660): PopupuiService.java: dismissUSBCDetacheddDialog() unReigister
W/ContextImpl( 5660): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 com.sec.android.app.popupuireceiver.PopupuiService.dismissUSBCDetacheddDialog:130 com.sec.android.app.popupuireceiver.PopupuiService.onStartCommand:103 
E/SQLiteLog( 4177): (284) automatic index on conversation_participants_view(conversation_id)
W/ContextImpl( 5660): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 android.app.ActivityThread.handleStopService:3289 android.app.ActivityThread.access$2300:172 
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
E/SQLiteLog( 4177): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 4177): (284) automatic index on conversation_participants_view(conversation_id)
I/ActivityManager(  897): Killing 4537:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
I/HomeSyncInstallReceiver( 1477): This pkg do not need BT addr. Do nothing
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5690): MountEmulatedStorage()
I/libpersona( 5690): KNOX_SDCARD checking this for 10015
E/Zygote  ( 5690): v2
I/libpersona( 5690): KNOX_SDCARD not a persona
E/SQLiteLog( 4177): (284) automatic index on conversation_participants_view(conversation_id)
D/AndroidRuntime( 5653): 
D/AndroidRuntime( 5653): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  897): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5690 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
D/AndroidRuntime( 5653): CheckJNI is OFF
D/AndroidRuntime( 5653): setted country_code = Germany
D/AndroidRuntime( 5653): setted countryiso_code = DE
D/AndroidRuntime( 5653): setted sales_code = DBT
D/AndroidRuntime( 5653): readGMSProperty: start
D/AndroidRuntime( 5653): readGMSProperty: already setted!!
D/AndroidRuntime( 5653): readGMSProperty: end
D/AndroidRuntime( 5653): addProductProperty: start
I/SELinux ( 5690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5690): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 4177): (284) automatic index on conversation_participants_view(conversation_id)
D/TimaKeyStoreProvider( 5690): TimaSignature is unavailable
I/ActivityManager(  897): Killing 4385:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
D/ActivityThread( 5690): Added TimaKeyStore provider
W/libprocessgroup(  897): failed to open /acct/uid_10143/pid_4537/cgroup.procs: No such file or directory
D/ResourcesManager( 5690): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
I/PeopleDatabaseHelper( 1874): cleanUpNonGplusAccounts done.
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
E/Zygote  ( 5714): MountEmulatedStorage()
I/libpersona( 5714): KNOX_SDCARD checking this for 10016
E/Zygote  ( 5714): v2
I/libpersona( 5714): KNOX_SDCARD not a persona
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
I/ActivityManager(  897): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=5714 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  897): Killing 4566:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
E/SELinux ( 5714): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  897): failed to open /acct/uid_10099/pid_4385/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5714): TimaSignature is unavailable
D/ActivityThread( 5714): Added TimaKeyStore provider
E/AffinityControl( 5653): AffinityControl: registerfunction enter
D/ResourcesManager( 5714): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
W/ResourcesManager( 5714): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5714): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/AndroidRuntime( 5653): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  897): failed to open /acct/uid_10003/pid_4566/cgroup.procs: No such file or directory
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
E/PersonaManagerService(  897): inState():  stateMachine is null !!
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  897): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  897): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  897): mDVFSHelper.acquire()
D/FocusedStackFrame(  897): Set to : 0
D/Launcher.HomeView( 1505): onPause
D/AndroidRuntime( 5653): Shutting down VM
D/Launcher( 1505): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/GroupCast_FileTools( 5714): [getDirectoryForImageResized : 295] cleaning!!
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Zygote  ( 5735): MountEmulatedStorage()
E/Zygote  ( 5735): v2
I/libpersona( 5735): KNOX_SDCARD checking this for 10374
I/libpersona( 5735): KNOX_SDCARD not a persona
I/SurfaceFlinger(  249): id=12 createSurf (1x1),1 flag=404, Starting com.example.hello
I/ActivityManager(  897): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5735 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/System.err( 5714): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
I/SELinux ( 5735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/SELinux ( 5735): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/System.err( 5714): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 5714): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5714): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5714): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5714): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5714): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5714): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5714): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5714): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5714): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5714): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5714): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5714): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5714): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 5735): TimaSignature is unavailable
D/ActivityThread( 5735): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Zygote  ( 5750): MountEmulatedStorage()
E/Zygote  ( 5750): v2
I/libpersona( 5750): KNOX_SDCARD checking this for 1000
I/libpersona( 5750): KNOX_SDCARD not a persona
I/MicrophoneInputStream( 1571): mic_close gfk@2a845d14
I/ActivityManager(  897): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5750 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  897): Killing 4581:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  897): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
I/SELinux ( 5750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/AudioPolicyManager(  290): stopInput() input 26
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/audio_hw_primary(  290): in_standby: enter
D/Launcher.HomeView( 1505): onStop
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2090): [237392/6] Surface widget pause on instance = 1
D/TimaKeyStoreProvider( 5750): TimaSignature is unavailable
D/ActivityThread( 5750): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2090): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1171): value : false
D/accuweather( 2090): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2090): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2090): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetView( 1505): destroyHardwareResources():205734206
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/HotwordRecognitionRnr( 1571): Hotword detection finished
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/HotwordRecognitionRnr( 1571): Stopping hotword detection.
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5735): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/audio_hw_primary(  290): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  290): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  290): disable_audio_route: reset mixer path: audio-record
D/audio_route(  290): ++++ audio_route_update_mixer ==============
D/audio_route(  290): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  290): Setting mixer control: value: 0
D/audio_route(  290): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  290): disable_audio_route: exit
V/audio_hw_primary(  290): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  290): ++++ audio_route_update_mixer ==============
D/audio_route(  290): Setting mixer control: DEC2 Volume
D/audio_route(  290): Setting mixer control: value: 0
D/audio_route(  290): Setting mixer control: SLIM TX7 MUX, value: 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/audio_route(  290): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  290): Setting mixer control: value: 0
D/ResourcesManager( 5750): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/audio_route(  290): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/audio_route(  290): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  290): stop_input_stream: exit: status(0)
V/audio_hw_primary(  290): in_standby: exit:  status(0)
V/AudioPolicyManager(  290): releaseInput() 26
V/AudioPolicyManager(  290): closeInput(26)
V/audio_hw_primary(  290): adev_close_input_stream
V/audio_hw_primary(  290): in_standby: enter
V/audio_hw_primary(  290): in_standby: exit:  status(0)
E/audio_hw_primary(  290): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  290): releaseInput() exit
V/AlarmManager(  897): waitForAlarm result :8
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/accuweather( 2090): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2090): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Launcher( 1505): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1505): destroyHardwareResources():205734206
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/PCWCLIENTTRACE_LOG( 5750): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5750): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5750): new DMDBOpenHelper instance
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
I/PCWCLIENTTRACE_PushUtil( 5750): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5750): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5750): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5750): [onReceive] - android.intent.action.PACKAGE_ADDED
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/Zygote  ( 5767): MountEmulatedStorage()
E/Zygote  ( 5767): v2
I/libpersona( 5767): KNOX_SDCARD checking this for 10034
I/libpersona( 5767): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5767 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  897): Killing 4598:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
I/SELinux ( 5767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1171): value : false
I/SELinux ( 5767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  897): failed to open /acct/uid_10020/pid_4581/cgroup.procs: No such file or directory
I/WebViewFactory( 5735): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 5735): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 5767): TimaSignature is unavailable
D/ActivityThread( 5767): Added TimaKeyStore provider
I/LibraryLoader( 5735): Loading: webviewchromium
I/LibraryLoader( 5735): Time to load native libraries: 2 ms (timestamps 2671-2673)
I/LibraryLoader( 5735): Expected native library version number "",actual native library version number ""
W/libprocessgroup(  897): failed to open /acct/uid_10012/pid_4598/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
V/WebViewChromiumFactoryProvider( 5735): Binding Chromium to main looper Looper (main, tid 1) {28ff5065}
I/LibraryLoader( 5735): Expected native library version number "",actual native library version number ""
I/chromium( 5735): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
I/BrowserStartupController( 5735): Initializing chromium process, renderers=0
W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1171): value : false
W/chromium( 5735): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 5735): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/chromium( 5735): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5735): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter( 5735): 307376442: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5735): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5735): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5735): Build Date: 03/03/15 Tue
I/Adreno-EGL( 5735): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 5735): Remote Branch: 
I/Adreno-EGL( 5735): Local Patches: 
I/Adreno-EGL( 5735): Reconstruct Branch: 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/FeatureConfig( 5767): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 5767): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 5767): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 5767): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 5767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/chromium( 5735): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/ResourcesManager( 5767): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/chromium( 5735): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/ResourcesManager( 5767): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 5767): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5735): onDetachedFromWindow called when already detached. Ignoring
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ResourcesManager( 5767): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 5767): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SystemWebViewEngine( 5735): CordovaWebView is running on device made by: samsung
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 5767): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5767): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
W/ResourcesManager( 5767): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5767): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 5767): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 5767): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/ResourcesManager( 5767): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 5767): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager( 5767): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5767): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 5767): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/Activity( 5735): performCreate Call secproduct feature valuefalse
D/Activity( 5735): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/OpenGLRenderer( 5735): Render dirty regions requested: true
D/ActivityManager(  897): post active user change for 0
D/KnoxTimeoutHandler(  897): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  897): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=13 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/BitmapFactory( 5560): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
I/OpenGLRenderer( 5735): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/OpenGLRenderer( 5735): HWUI protection enabled for context ,  &this =0xaed53060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 5735): Enabling debug mode 0
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/NotifUtils( 5560): Account: 61035162 vibrate: false
I/NotifUtils( 5560): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|1729800001|null|10114
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/ValidateNoPeople(  897): Executing: validation for: 0|com.google.android.gm|1729800001|null|10114
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
I/SA      ( 5067): [PMR] Received action : android.intent.action.PACKAGE_ADDED
V/AudioPolicyManager(  290): getOutputsForDevice device 0002 -> 0002
I/AudioService(  897): getStreamVolume 5 index 110
D/LightsService(  897): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  897): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SA      ( 5067): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 5067): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10374 extra.user_handle.:0 ]
I/ActivityManager(  897): Killing 4363:com.android.vending/u0a30 (adj 15): bgCount ##41
D/ResourcesManager( 1171): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-2100714965|null|10114
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
V/BitmapFactory( 1171): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Mms/FreeMessageReceiver( 5245): onReceive, action : android.intent.action.PACKAGE_ADDED
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/SQLiteLog( 1775): (284) automatic index on sqlite_sq_AF626B00(STAT_DATA_ID)
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-913293406|null|10114
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
V/BitmapFactory( 1171): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/InputMethodManagerService(  897): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/KnoxNotification( 1171): ----- inflateViews : modified KnoxViewLocal -----
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/libprocessgroup(  897): failed to open /acct/uid_10030/pid_4363/cgroup.procs: No such file or directory
W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-865450363|null|10114
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
D/PersonaManager( 1171): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1171): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2955f00b
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1171): Icon Only
I/Timeline( 5735): Timeline: Activity_idle id: android.os.BinderProxy@1d7e1cd5 time:43250
I/ActivityManager(  897): Displayed com.example.hello/.MainActivity: +847ms
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Mms/FreeMessageReceiverService( 5245): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5245): onHandleIntent: ACTION_PACKAGE_ADDED
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/CustomFrequencyManagerService(  897): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  897): mDVFSHelper.release()
D/CustomFrequencyManagerService(  897): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline(  897): Timeline: Activity_windows_visible id: ActivityRecord{e1ec26c u0 com.example.hello/.MainActivity t11} time:43284
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/chromium( 5735): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5735): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/art     (  897): Explicit concurrent mark sweep GC freed 20913(1458KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 1.236ms total 101.537ms
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/JsMessageQueue( 5735): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
E/Zygote  ( 5828): MountEmulatedStorage()
I/libpersona( 5828): KNOX_SDCARD checking this for 10051
E/Zygote  ( 5828): v2
I/libpersona( 5828): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5828 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/chromium( 5735): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5735): 
,I/SELinux ( 5828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5828): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/ValidateNoPeople(  897): final affinity: 0.0
,I/ValidateNoPeople(  897): Executing: validation for: 0|com.google.android.gm|-2100714965|null|10114
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|-633420634|null|10114
I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
D/TimaKeyStoreProvider( 5828): TimaSignature is unavailable
D/ActivityThread( 5828): Added TimaKeyStore provider
I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|438982678|null|10114
I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/ValidateNoPeople(  897): final affinity: 0.0
,I/ValidateNoPeople(  897): Executing: validation for: 0|com.google.android.gm|-913293406|null|10114
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager( 5828): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (6/8)
,I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (-2/8)
,W/ResourcesManager( 5828): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5828): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/LockPatternUtilsCache( 1171): value : false
,E/Adreno-ES20( 5735): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5735): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/art     ( 1171): Explicit concurrent mark sweep GC freed 39435(1818KB) AllocSpace objects, 5(492KB) LOS objects, 30% free, 36MB/52MB, paused 932us total 105.423ms
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/ValidateNoPeople(  897): final affinity: 0.0
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,E/SMD     (  283): DCD ON
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|1919793178|null|10114
,I/ValidateNoPeople(  897): final affinity: 0.0
,D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,I/ValidateNoPeople(  897): Executing: validation for: 0|com.google.android.gm|-865450363|null|10114
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/CustomFrequencyManagerService(  897): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  tag : ACTIVITY_RESUME_BOOSTER@10
,I/ValidateNoPeople(  897): final affinity: 0.0
,D/MyFiles ( 5828): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  897): Validating: 0|com.google.android.gm|2046740944|null|10114
I/ValidateNoPeople(  897): final affinity: 0.0
D/WindowManager(  897): showStatusBarByNotification() mOpenByNotification=false
,D/jxcore_app_log( 5735): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359519744
D/JX-Cordova( 5735): jxcore cordova android initializing
E/installd(  293): system dir 0 : /system/app/
E/installd(  293): system dir 1 : /system/priv-app/
E/installd(  293): system dir 2 : /vendor/app/
E/installd(  293): system dir 3 : /oem/app/
,I/TactileAssist(  897): enable value -1
,I/TactileAssist(  897): internal enable value -1
I/TactileAssist(  897): intensity value -1
I/TactileAssist(  897): saveAppList value true
E/Watchdog(  897): !@Sync 1
,I/TactileAssist(  897): List of disabled apps :
,I/TactileAssist(  897): de.zalando.mobile
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/PackageManager(  897): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/SettingsProvider(  897): name = audio_safe_volume_state
,E/Zygote  ( 5852): MountEmulatedStorage()
E/Zygote  ( 5852): v2
I/libpersona( 5852): KNOX_SDCARD checking this for 10058
I/libpersona( 5852): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5852 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,W/jxcore-log( 5735): Initializing JXcore engine
W/jxcore-log( 5735): JXcore engine is ready
,W/jxcore-log( 5735): Starting JXcore engine
,I/SELinux ( 5852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5852): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 5852): TimaSignature is unavailable
,D/ActivityThread( 5852): Added TimaKeyStore provider
,E/auditd  ( 2130): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  897): Got Modify Event and sending Denial Intent foraudit.log
,D/ResourcesManager( 5852): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 5852): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  897): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/Compatibility( 5852): onReceive() it will make start service
,D/Compatibility( 5852): onHandleIntent()
,D/Compatibility( 5852): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10374, android.intent.extra.user_handle=0}]
,D/Compatibility( 5852): found: 2
,I/UpdateIcingCorporaServi( 1571): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/ContextImpl( 5628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,D/Compatibility( 5852): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5852): skipping ResolveInfo{218f32a9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5852): considering ResolveInfo{31e402e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5852): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5852): enabling receiver ResolveInfo{1d0387cf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5852): enabling receiver ResolveInfo{6fc155c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5852): enabling receiver ResolveInfo{28ff5065 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5852): enabling receiver ResolveInfo{1252313a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5852): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Zygote  ( 5871): MountEmulatedStorage()
E/Zygote  ( 5871): v2
I/libpersona( 5871): KNOX_SDCARD checking this for 10086
I/libpersona( 5871): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=5871 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 5735): Platform android
W/jxcore-log( 5735): 
W/jxcore-log( 5735): Process ARCH arm
W/jxcore-log( 5735): 
,I/SELinux ( 5871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5871): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  897): Killing 4815:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 5871): TimaSignature is unavailable
,D/ActivityThread( 5871): Added TimaKeyStore provider
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/jxcore-log( 5735): JXcore Cordova bridge is ready!
I/jxcore-log( 5735): 
,W/jxcore-log( 5735): JXcore engine is started
,D/ResourcesManager( 1874): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 5871): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5871): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_4815/cgroup.procs: No such file or directory
,E/jxcore-log( 5735): >> samsung-SM-G900F
E/jxcore-log( 5735): 
,I/jxcore-log( 5735): Total memory 1787449344
I/jxcore-log( 5735): 
,I/jxcore-log( 5735): Free memory 43659264
I/jxcore-log( 5735): 
I/jxcore-log( 5735): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5735): 
I/jxcore-log( 5735): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5735): 
,I/jxcore-log( 5735): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5735): 
,I/jxcore-log( 5735): Size 1080 1920
I/jxcore-log( 5735): 
,I/jxcore-log( 5735): Screen Brightness 134
I/jxcore-log( 5735): 
,E/jxcore-log( 5735): Dummy Error Log.
E/jxcore-log( 5735): 
,D/PushModule( 5871): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 5871): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 5871): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 5871): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 5871): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  897): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 5871): [1][a] ChatONV isn't installed.
,D/ChatON  ( 5871): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5893): MountEmulatedStorage()
E/Zygote  ( 5893): v2
I/libpersona( 5893): KNOX_SDCARD checking this for 10098
I/libpersona( 5893): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5893 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 4848:com.android.email/u0a163 (adj 15): bgCount ##41
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/SELinux ( 5893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5893): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5893): TimaSignature is unavailable
,D/ActivityThread( 5893): Added TimaKeyStore provider
,D/ResourcesManager( 5893): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10163/pid_4848/cgroup.procs: No such file or directory
,D/ResourcesManager( 1571): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/UpdateIcingCorporaServi( 1571): UpdateCorporaTask done [took 383 ms] updated apps [took 383 ms] 
,D/DocsApplication( 5893): Installing DEX configuration.
,D/DexInstaller( 5893): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 5893): Provided clientMode=RELEASE, packageInfo=PackageInfo{2798c630 com.google.android.apps.docs}
,D/TAG     ( 5893): onCreate()
,E/LightSensor(  897): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/CrossAppStateProvider( 5893): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/LightSensor(  897): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/jxcore-log( 5735): getBuffer is called!!!!
I/jxcore-log( 5735): 
,E/LightSensor(  897): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/PackageManager(  897): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  897): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RegisteredServicesCache( 1477): empty dynamic service
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/LightSensor(  897): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 1505): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,V/BitmapFactory( 1505): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_settings_icon.png
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  ( 5936): MountEmulatedStorage()
E/Zygote  ( 5936): v2
I/libpersona( 5936): KNOX_SDCARD checking this for 10099
I/libpersona( 5936): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=5936 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/FaceInterface( 5365): startFaceScan() : going on
,D/FaceInterface( 5365): startFaceScan() is called.
,I/ActivityManager(  897): Killing 4740:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  897): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  897): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 5936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BackupManagerService(  897): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ContentApp( 1220): startScan() is called.
,W/GAV2    ( 5893): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FaceValue( 1220): mSleepTime: 800
,D/FaceValue( 1220): mMaxThreadNum: 2
,D/ContentApp( 1220): startScan() is end.
,V/BackupManagerService(  897): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  897): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@27b2c62d
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ContentApp( 1220): face_restore FINISHED_TYPE: 3
,W/libprocessgroup(  897): failed to open /acct/uid_10017/pid_4740/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5936): TimaSignature is unavailable
,D/ActivityThread( 5936): Added TimaKeyStore provider
,D/FaceScanner( 1220): isNeedToRestore : start
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager( 5936): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 5936): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/GmsNetworkLocationProvi( 1449): DISABLE
,I/GCoreNlp( 1449): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/[CarMode]( 5936): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 5936): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 5936): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,D/LocationProviderProxy(  897): applying state to connected service
,D/LocationProviderProxy(  897): applying state to connected service
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5963): MountEmulatedStorage()
,E/Zygote  ( 5963): v2
I/libpersona( 5963): KNOX_SDCARD checking this for 10033
I/libpersona( 5963): KNOX_SDCARD not a persona
,I/SELinux ( 5963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  897): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=5963 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5963): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  318): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 14.080ms
,D/TimaKeyStoreProvider( 5963): TimaSignature is unavailable
,D/ActivityThread( 5963): Added TimaKeyStore provider
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 269us total 8.847ms
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/FaceInterface( 5365): startFaceScan() : going on
D/FaceInterface( 5365): startFaceScan() is called.
,D/ResourcesManager( 5963): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ContentApp( 1220): startScan() is called.
,D/ContentApp( 1220): startScan() is end.
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 261us total 8.332ms
,D/ContentApp( 1220): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1220): isNeedToRestore : start
,W/ResourcesManager( 5963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 5893): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/SSRM:m  (  897): SIOP:: AP = 480, PST = 440, CUR = 300
I/ActivityManager(  897): Waited long enough for: ServiceRecord{3756e2d6 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/System.out( 5963): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 5963): Inside WakeupProvider
,E/DatabaseUtils( 5963): Writing exception to parcel
E/DatabaseUtils( 5963): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5963): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5963): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5963): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5963): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5963): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5963): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5963): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5963): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5963): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5963): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 5936): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 5963): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,D/BluetoothAdapter( 5963): 490298602: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 5963): 490298602: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5963): 490298602: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 5963): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,W/System.err( 5936): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5936): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5936): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5936): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5936): 	at android.content.ContentResolver.query(ContentResolver.java:484)
,W/System.err( 5936): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5936): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5936): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5936): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
,W/System.err( 5936): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5936): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5936): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5936): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
,W/System.err( 5936): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 5936): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 5936): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 5936): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 5936): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
,W/System.err( 5936): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 5936): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
,W/System.err( 5936): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5936): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5936): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5936): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5936): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 5936): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5936): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5936): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5936): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5936): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5936): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 5936): [DLApplication]-Init Called!:false
,E/[CarMode]( 5936): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 5936): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 5936): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 5936): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 5936): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 5936): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 5936): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 5936): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 5936): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 5936): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 5936): ### android.os.Looper::loop(145)
I/[CarModeFW]( 5936): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 5936): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 5936): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 5936): ### com.android.internal.os.ZygoteInit::main(1194)
,D/VlingoApplication( 5963): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 5963): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MessageDataHandler( 5936): initialize
,D/[CarModeFW]( 5936): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 5936): CDH-initiazlieCaches : after sync
,D/[CarModeFW]( 5936): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 5936): CDH-ContactDataHandler initiazlieCaches time : 11
D/[CarModeFW]( 5936): CDH-initiazlieCaches : end sync
,D/BluetoothAdapter( 5936): 876813456: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5936): 876813456: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 5936): DrivingManager-initialize...
,I/SensorService(  897): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  897): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  897): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/MediaPlayer( 5936): Need to enable context aware info
V/MediaPlayer-JNI( 5936): native_setup
V/MediaPlayer( 5936): constructor
,V/MediaPlayer( 5936): setListener
,E/MediaPlayer-JNI( 5936): QCMediaPlayer mediaplayer NOT present
,I/art     (  897): Explicit concurrent mark sweep GC freed 34221(1909KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 1.188ms total 81.226ms
,D/[CarModeFW]( 5936): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 5936): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 5936): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1449078363278
,D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1449078363279
D/[CarMode]( 5936): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1449078363279
D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1449078363279
,D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1449078363279
D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1449078363279
,I/[CarMode]( 5936): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/[CarModeFW]( 5936): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 5936): RecommendHandler-selection = type = '3'
,E/[CarMode]( 5936): [DLApplication]-Init End!:true
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1483): query,matched:2, calling pid = 5936
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1483): match 2:Elapsed time : 2.330 ms
,E/Zygote  ( 5997): MountEmulatedStorage()
E/Zygote  ( 5997): v2
I/libpersona( 5997): KNOX_SDCARD checking this for 10020
I/libpersona( 5997): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=5997 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
E/Zygote  ( 6003): MountEmulatedStorage()
E/Zygote  ( 6003): v2
I/libpersona( 6003): KNOX_SDCARD checking this for 10003
I/libpersona( 6003): KNOX_SDCARD not a persona
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/ActivityManager(  897): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=6003 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
I/SELinux ( 5997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SELinux ( 6003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/SELinux ( 5997): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/SELinux ( 6003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6003): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[CarMode]( 5936): [DLApplication]-GooglePlayServices SUCCESS.
,D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/TP/SmsProvider( 1483): query,matched:2, calling pid = 5936
,D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
E/[CarMode]( 5936): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/TP/SmsProvider( 1483): match 2:Elapsed time : 1.668 ms
D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/[CarModeFW]( 5936): CDH-buildContactCacheWireFrame : cur len =0
D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/MessageDataHandler( 5936):  getInboxList smsCursor : 112
,D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/TP/MmsProvider( 1483): Query uri=content://mms/inbox, match=2, calling pid = 5936
,D/GeoLookout( 5524): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/TP/MmsProvider( 1483): Query uri=content://mms, match=0, calling pid = 5936
,D/TimaKeyStoreProvider( 6003): TimaSignature is unavailable
,D/ActivityThread( 6003): Added TimaKeyStore provider
,D/[CarModeFW]( 5936): CDH-buildContactCacheWireFrame : cur len =0
,I/UpdateManagerReceiver( 5936): Intent : android.intent.action.PACKAGE_ADDEDWed Dec 02 18:46:03 GMT+01:00 2015
,D/TimaKeyStoreProvider( 5997): TimaSignature is unavailable
,D/ActivityThread( 5997): Added TimaKeyStore provider
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 6003): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,E/Zygote  ( 6027): MountEmulatedStorage()
,E/Zygote  ( 6027): v2
I/libpersona( 6027): KNOX_SDCARD checking this for 1000
I/libpersona( 6027): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6027): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 5936): RecommendHandler-selection = type = '3'
D/MessageDataHandler( 5936):  getInboxList mmsCursor : 77
,I/MessageDataHandler( 5936): getUnreadMessageCount :0
D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 191
,I/ActivityManager(  897): Killing 5015:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,D/UserAnalysis.PlaceProvider( 6003): PlaceProvider onCreate()
,D/MessageDataHandler( 5936):  getInboxList mms,sms cursor join : 8
,D/TP/MmsSmsProvider( 1483): query,matched:0, calling pid = 5936
V/TP/MmsSmsProvider( 1483): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1483): match 0:Elapsed time : 0.896 ms
,D/TP/MmsSmsProvider( 1483): query,matched:13, calling pid = 5936
,D/TP/MmsSmsProvider( 1483): match 13:Elapsed time : 0.798 ms
,D/TimaKeyStoreProvider( 6027): TimaSignature is unavailable
,D/[CarModeFW]( 5936): PushMessageService-onCreate
D/ActivityThread( 6027): Added TimaKeyStore provider
,D/MessageDataHandler( 5936):  getInboxList address cursor : 13
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/ResourcesManager( 5997): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/ActivityManager(  897): Killing 4612:com.android.calendar/u0a150 (adj 15): bgCount ##41
,D/TP/MmsSmsProvider( 1483): query,matched:0, calling pid = 5936
V/TP/MmsSmsProvider( 1483): getSimpleConversations entered.
I/ActivityManager(  897): Killing 5095:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##42
,I/ActivityManager(  897): Killing 4653:com.android.providers.calendar/u0a46 (adj 15): bgCount ##43
D/TP/MmsSmsProvider( 1483): match 0:Elapsed time : 1.784 ms
,D/ResourcesManager( 6027): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/MessageDataHandler( 5936):  getInboxList thread cursor : 9
,D/[CarModeFW]( 5936): PushMessageManager-onServiceConnected
D/[CarModeFW]( 5936): PushMessageService-registerPushMessageServiceListener
,D/MessageDataHandler( 5936):  thread, addr result: 5
,I/[CarModeFW]( 5936): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 230
I/[CarModeFW]( 5936): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 230
,W/ContextImpl( 6027): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,D/UserAnalysis.SecureDbManager( 6003): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6003): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 6003): Create SecureDbHelper
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 6027): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,E/Zygote  ( 6043): MountEmulatedStorage()
E/Zygote  ( 6043): v2
I/libpersona( 6043): KNOX_SDCARD checking this for 10112
I/libpersona( 6043): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6043 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/IntelligenceServiceApplication( 6003): onCreate()
,I/SELinux ( 6043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SQLiteSecureOpenHelper( 6003): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 6003): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 6003): Open Place.db in secure mode
,D/ResourcesManager( 4517): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/FilterInstaller( 6027): There is no requred permission
,I/ActivityManager(  897): Killing 5151:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6043): TimaSignature is unavailable
,D/ActivityThread( 6043): Added TimaKeyStore provider
,D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 338
,I/SQLiteSecureOpenHelper( 6003): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 6003): ...getDatabaseLocked(b,b,pwd)
,I/[CarModeFW]( 5936): -[snowdeer] Rec : Missed Call : 334
,D/ResourcesManager( 6043): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/[CarModeFW]( 5936): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 5936): MyPlaceProvider-=============
D/[CarModeFW]( 5936): MyPlaceProvider-=============
D/[CarModeFW]( 5936): MyPlaceProvider-=============
D/[CarModeFW]( 5936): MyPlaceProvider-=============
D/[CarModeFW]( 5936): MyPlaceProvider----End print all data in content provider---
,D/[CarModeFW]( 5936): MyPlaceProvider-==============
D/[CarModeFW]( 5936): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5936): MyPlaceProvider-==============
,D/[CarModeFW]( 5936): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5936): MyPlaceProvider-==============
D/[CarModeFW]( 5936): MyPlaceProvider-latitude is not valid
,I/[CarModeFW]( 5936): -[snowdeer] Rec : Favorite : 11
,D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 353
,D/[CarMode]( 5936): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@c5767cac, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@f80ac132] LOCATIONS
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/PackageIntentReceiver( 6043): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 6043): Not GearManger package! 
,E/Zygote  ( 6060): MountEmulatedStorage()
,E/Zygote  ( 6060): v2
I/libpersona( 6060): KNOX_SDCARD checking this for 10046
I/libpersona( 6060): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6060 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[CarModeFW]( 5936): -[snowdeer] Rec : CallLog : 21
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/Zygote  ( 6067): MountEmulatedStorage()
E/Zygote  ( 6067): v2
I/libpersona( 6067): KNOX_SDCARD checking this for 10118
I/libpersona( 6067): KNOX_SDCARD not a persona
,I/SELinux ( 6060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  897): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=6067 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5184:com.sec.factory/1000 (adj 15): bgCount ##41
,I/SELinux ( 6067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/SELinux ( 6060): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SELinux ( 6067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6067): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6060): TimaSignature is unavailable
,D/ActivityThread( 6060): Added TimaKeyStore provider
,I/ActivityManager(  897): Killing 4764:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_10149/pid_5095/cgroup.procs: No such file or directory
,W/libprocessgroup(  897): failed to open /acct/uid_10037/pid_5015/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6067): TimaSignature is unavailable
W/libprocessgroup(  897): failed to open /acct/uid_10150/pid_4612/cgroup.procs: No such file or directory
,D/ActivityThread( 6067): Added TimaKeyStore provider
,W/libprocessgroup(  897): failed to open /acct/uid_10046/pid_4653/cgroup.procs: No such file or directory
,D/ResourcesManager( 6060): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 6060): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ResourcesManager( 6067): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 6067): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GAV2    ( 5560): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 6060): CalendarProvider2.onCreate() called
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_5151/cgroup.procs: No such file or directory
,D/MagazineService Version( 6067): Magazine-Administrator: 11
,D/MagazineService Version( 6067): Magazine-Provider: 14
,D/MagazineService Version( 6067): Magazine-Channel: 14
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6094): MountEmulatedStorage()
E/Zygote  ( 6094): v2
I/libpersona( 6094): KNOX_SDCARD checking this for 10118
I/libpersona( 6094): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=6094 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 6067): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 6067): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,I/SELinux ( 6094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_5184/cgroup.procs: No such file or directory
,I/SELinux ( 6094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,E/SELinux ( 6094): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 6067): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/TimaKeyStoreProvider( 6094): TimaSignature is unavailable
,D/ActivityThread( 6094): Added TimaKeyStore provider
,E/Zygote  ( 6107): MountEmulatedStorage()
E/Zygote  ( 6107): v2
I/libpersona( 6107): KNOX_SDCARD checking this for 1000
I/libpersona( 6107): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 6067): [onHandleIntent] Send broadcast to (com.example.hello).
,I/SELinux ( 6107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  897): failed to open /acct/uid_10078/pid_4764/cgroup.procs: No such file or directory
,I/SELinux ( 6107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6107): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6107): TimaSignature is unavailable
,D/ActivityThread( 6107): Added TimaKeyStore provider
,I/ActivityManager(  897): Killing 5287:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/ResourcesManager( 6107): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 6094): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 6094): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/HeadlinesChannelApplication( 6094): [onCreate]
,D/Headlines( 6094): Breath.onCreate
D/HeadlinesCardManager( 6094): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 6094): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 6094): CardProvider Library : 14
,W/libprocessgroup(  897): failed to open /acct/uid_10025/pid_5287/cgroup.procs: No such file or directory
,E/SMD     (  283): DCD ON
,D/MagazineService::CardProviderContentProvider( 6067): insertProvider: provider already exists.: com.samsung.android.app.headlines
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/MagazineService::CardProviderContentProvider( 6067): insertProvider: provider is updated.: com.samsung.android.app.headlines
,E/Zygote  ( 6125): MountEmulatedStorage()
E/Zygote  ( 6125): v2
I/libpersona( 6125): KNOX_SDCARD checking this for 1000
I/libpersona( 6125): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 6094): registerCardProvider: provider already exists.
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/Headlines( 6094): HeadlinesDataCenter ctor
,D/Headlines( 6094): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 6094): getCountryCode(): countryCode = DE
,D/HeadlinesCardManager( 6094): HeadlinesCardManager : constructor welcome :YES
,I/SELinux ( 6125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6125): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6125): TimaSignature is unavailable
,I/[CarModeFW]( 5936): -[snowdeer] Rec : Schedule : 445
D/ActivityThread( 6125): Added TimaKeyStore provider
,I/[CarModeFW]( 5936): -[snowdeer] Rec : During DL app : 2
,I/[CarModeFW]( 5936): -[snowdeer] Rec : Location Sharing : 3
,I/[CarModeFW]( 5936): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 5936): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 5936): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5936): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5936): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
,I/[CarModeFW]( 5936): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 826
I/[CarModeFW]( 5936): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5936): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 5936): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 826
,D/ResourcesManager( 6125): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/System.out( 5963): INFO:Resource not found:/Common.properties Using default values
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6125): Received: android.intent.action.PACKAGE_ADDED
,E/Zygote  ( 6147): MountEmulatedStorage()
,E/Zygote  ( 6147): v2
I/libpersona( 6147): KNOX_SDCARD checking this for 10135
I/libpersona( 6147): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6147 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5385:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,W/ContextImpl( 6125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/SELinux ( 6147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6147): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 6125): Enter Oncreate
,D/AcmsServiceMonitor( 6125): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6125): creating AcmsCore
D/AcmsCore( 6125): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6125): AcmsCore
,D/AcmsCore( 6125): init
D/AcmsCore( 6125): Looper handler is not null
,D/AcmsCore( 6125): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6125): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6125): Incrementing - Counter value: 1
E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AcmsCertificateMngr( 6125): AcmsCertificateMngr
D/AcmsCore( 6125): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/AcmsRevocationMngr( 6125): AcmsRevocationMngr
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/AcmsService( 6125): onStartCommand
D/AcmsService( 6125): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6125): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6125): Incrementing - Counter value: 2
D/AcmsService( 6125): Incremented Counter Value : onStartCommand
,W/libprocessgroup(  897): failed to open /acct/uid_10002/pid_5385/cgroup.procs: No such file or directory
,D/ActivityThread( 6125): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/TimaKeyStoreProvider( 6147): TimaSignature is unavailable
,D/ActivityThread( 6147): Added TimaKeyStore provider
,D/ResourcesManager( 6147): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 6147): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 6125): Inside handle Intent
,D/AcmsService( 6125): App added - package name: com.example.hello
D/AcmsCore( 6125): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6125): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6125): Incrementing - Counter value: 3
D/AcmsCore( 6125): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6125): Decremented Counter Value : handleStartIntent
,D/AcmsServiceMonitor( 6125): Decrementing - Counter value: 2
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6177): MountEmulatedStorage()
I/libpersona( 6177): KNOX_SDCARD checking this for 10166
E/Zygote  ( 6177): v2
I/libpersona( 6177): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=6177 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 8763(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 13.256ms
,D/PowerManagerService(  897): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  897): Nap time (uid 1000)...
,I/PowerManagerService(  897): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  897): Going to sleep due to screen timeout (uid 1000)...
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.592ms
D/InputManager-JNI(  897): setDeviceInteractive: 0
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  897): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  897): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  897): handleSandman : startDream()
,E/PowerManagerService(  897): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  897): Sleeping (uid 1000)...
D/PowerManagerService(  897): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  897): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  897): [input device light] handleInputDeviceLightOff
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 8.497ms
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  897): 	.unregisterCallback : 1, client=
,D/SContextService(  897): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@9ed2446, Service = Auto Rotation, used = 1
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,I/SELinux ( 6177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/CAE     (  897): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,I/SELinux ( 6177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/CAE     (  897): stop(ContextProvider.java:149)
,E/SELinux ( 6177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/CAE     (  897): clear(AutoRotationRunner.java:182)
,V/CAE     (  897): disable(AutoRotationRunner.java:171)
I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  298): sendContextData: -78, 7, 0, 0
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,D/CAE     (  897): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  897): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/TimaKeyStoreProvider( 6177): TimaSignature is unavailable
,D/ActivityThread( 6177): Added TimaKeyStore provider
,I/Adreno-EGL(  897): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  897): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  897): Build Date: 03/03/15 Tue
I/Adreno-EGL(  897): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  897): Remote Branch: 
I/Adreno-EGL(  897): Local Patches: 
I/Adreno-EGL(  897): Reconstruct Branch: 
I/GLSActivity( 1618): [ac] getting account id
,D/ResourcesManager( 6177): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 6177): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GLSUser ( 1618): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/CAE     (  897): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  897): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  897): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  897): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  897): removeSContextService() : service = Auto Rotation
D/SContextService(  897): ===== SContext Service List =====
D/SContextManager(  897):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@370a9040, service=Auto Rotation
,D/KeyguardViewMediator( 1171): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1171): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1171): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1171): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/KeyguardViewMediator( 1171): timeout : 5000
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/KidsPlatformStub( 6177): Package not found : com.sec.android.app.kidshome
,D/KeyguardViewMediator( 1171): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1171): handleNotifyScreenOff
,I/CAE     (  897): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  897): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  298): sendContextData: -76, 13, -47, 0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6198): MountEmulatedStorage()
,E/Zygote  ( 6198): v2
I/libpersona( 6198): KNOX_SDCARD checking this for 10170
I/libpersona( 6198): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6198 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/SQLiteSecureOpenHelper( 3313): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3313): getDatabaseLocked(b,b,pwd)...
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
I/SELinux ( 6198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6198): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService(  897): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  897):  handler : SCREEN_ON end
,D/DisplayPowerController(  897): ColorFade: onAnimationStart
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
,D/TimaKeyStoreProvider( 6198): TimaSignature is unavailable
,D/NotificationService(  897): ACTION_SCREEN_ON
D/LightsService(  897): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  897): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/ActivityThread( 6198): Added TimaKeyStore provider
,D/audio_hw_primary(  290): adev_set_parameters: enter: screen_state=on
V/voice   (  290): voice_set_parameters: enter: screen_state=on
V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
,D/lights  (  897): lcd : 0 +
,I/WifiNative-HAL(  897): startHal
,E/wifi    (  897): getStaticLongField sWifiHalHandle 0x959e17fc
D/wifi    (  897): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x1022e6
I/WifiNative-HAL(  897): Could not start hal
D/WifiStateMachine(  897): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  897): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  897): setSuspendOptimizations: 4 false
E/WifiStateMachine(  897): mSuspendOptNeedsDisabled 4
,I/SecExternalDisplayIntents_Java(  897): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
D/lights  (  897): lcd : 0 -
,D/IpRemoteDisplayController(  897): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController(  897): Bridge Server is not available
,D/PersonaManagerService(  897): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  897): MSG_ACTION_SCREEN_ON called
,D/ResourcesManager( 6198): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,I/NfcService( 1477): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1477): call the applyRotuiing
,E/SQLiteLog( 6198): (284) automatic index on shooting_modes(title_id)
,I/SamsungIME( 1851): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 2090): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2090): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2090): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2090): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2090): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/accuweather( 2090): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,E/Zygote  ( 6214): MountEmulatedStorage()
,E/Zygote  ( 6214): v2
I/libpersona( 6214): KNOX_SDCARD checking this for 10030
I/libpersona( 6214): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6214 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 5427:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,I/CalendarProvider2( 6060): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/SurfaceWidget.Renderer( 2090): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2090): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2090): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2090): [237392/6] SurfaceWidget drawing first frame
,I/SELinux ( 6214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
,E/SELinux ( 6214): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  897): Killing 5307:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,E/lowmemorykiller(  246): Error writing /proc/5307/oom_score_adj; errno=22
,D/DisplayPowerState(  897): !@ ColorFade entry
,D/DisplayPowerController(  897): ColorFade: onAnimationEnd
,D/TimaKeyStoreProvider( 6214): TimaSignature is unavailable
D/ActivityThread( 6214): Added TimaKeyStore provider
,D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,E/LightSensor(  897): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SensorManager(  897): unregisterListener ::   
E/Sensors (  897): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  897): unregisterListener ::   
,W/libprocessgroup(  897): failed to open /acct/uid_10172/pid_5427/cgroup.procs: No such file or directory
,D/ResourcesManager( 6214): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  897): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  897): Display changed displayId=0
,D/SSRM:m  (  897): SIOP:: AP = 480, PST = 445, CUR = 300
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,W/libprocessgroup(  897): failed to open /acct/uid_10004/pid_5307/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 897) 
,D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,E/LightSensor(  897): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  897): turn on LED for fully charged
,D/StatusBar.NetworkController( 1171): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/CAE     (  897): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  897): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  298): sendContextData: -76, 13, -46, 0
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 17, 46, 5,
D/SensorHubManager(  897): SendSensorHubData: send data = -63, 14, 17, 46, 5
,D/Sensorhubs(  298): sendContextData: -63, 14, 17, 46, 5
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  897):  handler : SCREEN_OFF end 
,I/WifiNative-HAL(  897): startHal
,E/wifi    (  897): getStaticLongField sWifiHalHandle 0x959e17fc
D/wifi    (  897): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x30171e
D/NotificationService(  897): ACTION_SCREEN_OFF
D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,I/WifiNative-HAL(  897): Could not start hal
D/WifiStateMachine(  897): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  897): handleScreenStateChanged Exit: false
,D/audio_hw_primary(  290): adev_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
,E/WifiStateMachine(  897): setSuspendOptimizations: 4 true
,E/WifiStateMachine(  897): mSuspendOptNeedsDisabled 0
I/SecExternalDisplayIntents_Java(  897): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  897): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  897): Bridge Server is not available
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1171): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1171): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  897): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  897): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1477): call the applyRotuiing
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor5:87000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor5:87000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm raised 1 at 87.0 degC
,I/ThermalEngine(  307): ACTION: OPT_CURR_REQ 1
,I/art     (  897): Explicit concurrent mark sweep GC freed 26765(1666KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 1.214ms total 86.435ms
,D/STATUSBAR-PhoneStatusBar( 1171):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1171): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1171): dismissHelpPopup 
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  897): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService(  897): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/MISC PowerHAL(  897): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  897): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  897): Invalid hint ID.
I/QCOM PowerHAL(  897): Got set_interactive hint
,I/PowerManagerService(  897): [PWL] Off : 0s ago
I/PowerManagerService(  897): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  897): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=897, ws=WorkSource{10117}) (elapsedTime=16705)
I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1874, ws=null) (elapsedTime=13339)
I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2205)
I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2205)
I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              'GCoreFlp' (uid=10012, pid=1449, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=7)
I/PowerManagerService(  897): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  897): [PWL]     mDisplayReady : false
I/PowerManagerService(  897): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Display
,D/accuweather( 2090): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2090): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2090): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 6214): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  897): SIOP:: AP = 480, PST = 450, CUR = 300
,D/X       (  897): broadcastSiopLevelIntent:: currentSiopLevel = 1
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ContentApp( 1220):  LEVEL : 1
,D/Finsky  ( 6214): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  897): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  897): unregisterListener ::   
,D/lights  (  897): led_pattern : 3 +
,D/lights  (  897): led_pattern : 3 -
,D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6259): MountEmulatedStorage()
E/Zygote  ( 6259): v2
I/libpersona( 6259): KNOX_SDCARD checking this for 10012
I/libpersona( 6259): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6259 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6259): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6214): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6214): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6259): TimaSignature is unavailable
,D/ActivityThread( 6259): Added TimaKeyStore provider
,D/ResourcesManager( 6259): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6259): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6259): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6259): VM with version 2.1.0 has multidex support
I/MultiDex( 6259): install
I/MultiDex( 6259): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  897): Killing 5341:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,D/Finsky  ( 6214): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6214): [1] 2.run: Finished loading 1 libraries.
,V/JNIHelp ( 6259): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 6214): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1874): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1874): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/ChimeraCfgMgr( 1874): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Finsky  ( 6214): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/libprocessgroup(  897): failed to open /acct/uid_10044/pid_5341/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:85000 mC
I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:85000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 85.0 degC
D/Vision  ( 1874): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1874): Failed to find package metadata for com.example.hello
,D/Vision  ( 1874): No vision deps
I/ConfigFetchService( 1874): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/ConfigFetchService( 1874): launchTask
,I/PeopleContactsSync( 1874): CP2 sync disabled
,E/Zygote  ( 6285): MountEmulatedStorage()
I/libpersona( 6285): KNOX_SDCARD checking this for 10040
E/Zygote  ( 6285): v2
I/libpersona( 6285): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6285 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityThread( 6259): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6259): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cf47e1c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6259): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 6285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6285): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 1874): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/TimaKeyStoreProvider( 6285): TimaSignature is unavailable
,D/ActivityThread( 6285): Added TimaKeyStore provider
,V/ConfigFetchTask( 1874): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VdHphLIAp_Je0Ul5HRiXYm3mFLvq1hcdztVHNFYcWi0QJ_bIe0KzwT4FbbC-WI0Uqw_IfyS_68T-5gaYbwzVFsl5Rz5RVpxZz2t2D7DWfpN6dGGWN9mhGmFc9Jd43ENLXFe7dRTc7hEesffImtwnDsuQnpSfgCEnY5jnhJvAd4IzbBMb3kxy6iln8S6lQePlMvN7dBlxDipq8yXsv80pOMgyirerxpeyFICSlJ_Gw4ya8AN90a_XJc1-axsFh44MOOstlTKUOA-nlfDYZYp6yQDSMJhBUuyFBqx9lBp0sp4GPd5oc
,D/ResourcesManager( 6285): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/GoogleURLConnFactory( 1874): Using platform SSLCertificateSocketFactory
,D/SSRM:a  (  897): DeviceInfo:: 000000000000
D/SSRM:a  (  897): SettingsAirViewInfo:: 000000000
,D/ResourcesManager( 6259): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/System.out( 1874): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1874): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1874): (HTTPLog)-Thread-244-718206900: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ConfigFetchTask( 1874): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1874): fetch service done; releasing wakelock
,I/ConfigFetchService( 1874): stopping self
,D/ResourcesManager( 4177): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 6259): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 4177): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 4177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/Finsky  ( 6214): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/JNIHelp ( 4177): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  897): Killing 5202:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,D/BootupListener( 1483): ACTION_DRIVELINK
,D/SettingsProvider(  897): name = drivelink_navigation
D/SettingsProvider(  897): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  897): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  897): selectionArgs: false
D/SettingsProvider(  897): selectionArgs: 1001
D/SecContentProvider(  897): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  897): ret = -1
,D/BootupListener( 1483): NAVI : com.google.android.apps.maps
D/SettingsProvider(  897): name = internet_call_settings_visibility
D/SettingsProvider(  897): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  897): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  897): selectionArgs: false
D/SettingsProvider(  897): selectionArgs: 1001
D/SecContentProvider(  897): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  897): ret = -1
,W/System  ( 4177): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ae9412b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 4177): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 4177): Installed default security provider GmsCore_OpenSSL
,I/Babel_RequestWriter( 4177): error sending REQ[fc:4; creat:1449077666588; type:bev-613187144]; took 2 ms (error code == 101)
,W/libprocessgroup(  897): failed to open /acct/uid_10126/pid_5202/cgroup.procs: No such file or directory
,D/GCM     ( 1618): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1618): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1874): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 5114): callingUid 10012, callindPid: 5114
,E/MDM     ( 1449): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/BluetoothAdapter( 5735): disable()
,E/BluetoothManagerService(  897): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService(  897): New client listening to asynchronous messages
,I/WifiManager( 5735): packageName : com.example.hello
,D/SecContentProvider(  897): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  897): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  897): mCursor = null
D/LocationInitializer( 1874): Restart initialization of location
,D/WifiService(  897): setWifiEnabled: false pid=5735, uid=10374
E/WifiService(  897): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  897): name = wifi_on
,I/jxcore-log( 5735): ****TEST TOOK:  5037  ms ****
I/jxcore-log( 5735): 
,I/jxcore-log( 5735): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5735): 
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor8:86000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor8:86000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS8' Sensor 'tsens_tz_sensor8' - alarm raised 1 at 86.0 degC
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4708): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4708): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4708): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 74.0 degC
,V/AlarmManager(  897): waitForAlarm result :4
,D/Finsky  ( 6214): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6334): MountEmulatedStorage()
E/Zygote  ( 6334): v2
I/libpersona( 6334): KNOX_SDCARD checking this for 10149
I/libpersona( 6334): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6334 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/SELinux ( 6334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6334): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AndroidRuntime( 6321): 
D/AndroidRuntime( 6321): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6321): CheckJNI is OFF
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 4708): RegionGroup for  is null
,D/AndroidRuntime( 6321): setted country_code = Germany
D/AndroidRuntime( 6321): setted countryiso_code = DE
,D/AndroidRuntime( 6321): setted sales_code = DBT
,D/AndroidRuntime( 6321): readGMSProperty: start
D/AndroidRuntime( 6321): readGMSProperty: already setted!!
D/AndroidRuntime( 6321): readGMSProperty: end
,D/AndroidRuntime( 6321): addProductProperty: start
,D/TimaKeyStoreProvider( 6334): TimaSignature is unavailable
,D/ActivityThread( 6334): Added TimaKeyStore provider
,D/ResourcesManager( 6334): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,I/GLSUser ( 1618): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1618): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1618): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1618): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6334): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6334): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/BluetoothManager( 4708): getConnectedDevices
,W/Finsky  ( 6214): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothManager( 4708): getConnectedDevices
,D/BluetoothManager( 4708): getConnectedDevices
,I/GLSUser ( 1618): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1618): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1618): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1618): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6357): MountEmulatedStorage()
E/Zygote  ( 6357): v2
I/libpersona( 6357): KNOX_SDCARD checking this for 10150
I/libpersona( 6357): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6357 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6357): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6357): TimaSignature is unavailable
,D/ActivityThread( 6357): Added TimaKeyStore provider
,D/ResourcesManager( 6357): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 6357): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1618): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1618): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1618): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1618): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6214): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/AffinityControl( 6321): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6321): Calling main entry com.android.commands.pm.Pm
,D/daemonapp( 1340): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PackageManager(  897): START PACKAGE DELETE: observer{761318758}
D/PackageManager(  897): pkg{<packageName>}
D/PackageManager(  897): user{0}
D/PackageManager(  897): caller{2000}
D/PackageManager(  897): flags{3}
D/PersonaManagerService(  897): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  897): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  897): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  897): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  897): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  897): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  897): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  897): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  897): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  897): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  897): !@killApplicatoin: 10374, uninstall pkg
,I/ActivityManager(  897): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  897): Killing 5735:com.example.hello/u0a374 (adj 0): stop com.example.hello
,I/ActivityManager(  897):   Force finishing activity ActivityRecord{e1ec26c u0 com.example.hello/.MainActivity t11}
,D/FocusedStackFrame(  897): Set to : 0
E/SMD     (  283): DCD ON
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (5/8)
I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/WifiService(  897): Client connection lost with reason: 4
,W/PackageSettings(  897): Skipping PackageSetting{5551fd8 com.test.thalitest/10367} due to missing metadata
,I/ActivityManager(  897): Force stopping com.example.hello appid=10374 user=0: pkg removed
,I/art     ( 4517): Explicit concurrent mark sweep GC freed 2846(160KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 311us total 16.544ms
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:86000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:86000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 86.0 degC
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 1505): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1505): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/GeofencerStateMachine( 1449): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 1505): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,E/SamsungIME( 1851): mOCRHelper is null
W/ResourcesManager( 1505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1505): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/InputReader(  897): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/art     ( 1618): Explicit concurrent mark sweep GC freed 14925(823KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 17MB/29MB, paused 748us total 31.655ms
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/Babel_RequestWriter( 4177): error sending REQ[fc:5; creat:1449077666588; type:bev-613187144]; took 0 ms (error code == 101)
,D/RegisteredServicesCache( 1477): empty dynamic service
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/RCPManagerService(  897): PackageReceiver onReceive()
I/HarmonyEASService(  897): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  897): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  897): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  897): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  897): uID is 10374
V/EnterpriseBillingPolicy(  897): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - might be a vpn vendor package 
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/talkback/talkback.apk
V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - end - null
,D/EnterpriseDeviceManagerService(  897): Package has changed for user 0
D/EnterpriseDeviceManagerService(  897): Admin package name: com.google.android.gms
,D/TaskPersister(  897): removeObsoleteFile: deleting file=11_task.xml
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/GCM     ( 1618): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  897): Explicit concurrent mark sweep GC freed 42351(3MB) AllocSpace objects, 7(112KB) LOS objects, 30% free, 36MB/52MB, paused 11.493ms total 254.542ms
,D/ChimeraCfgMgr( 1874): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/PackageManager(  897): delete codoeFile: 
D/ChimeraCfgMgr( 1874): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1874): [KidAccountFixer] No network connection
,D/PackageManager(  897): result of delete: 1{761318758}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/AndroidRuntime( 6321): Shutting down VM
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/GAV2    ( 5893): Thread[GAThread,5,main]: No campaign data found.
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  897): clearDefaults: com.example.hello
,I/CrashAnrDetector(  897): onPackageRemoved : com.example.hello
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor7:87000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor7:87000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS7' Sensor 'tsens_tz_sensor7' - alarm raised 1 at 87.0 degC
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4708): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4708): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4708): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6393): MountEmulatedStorage()
E/Zygote  ( 6393): v2
I/libpersona( 6393): KNOX_SDCARD checking this for 10036
I/libpersona( 6393): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6393 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6393): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1618): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1618): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1618): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1618): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Finsky  ( 6214): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/TimaKeyStoreProvider( 6393): TimaSignature is unavailable
,D/ActivityThread( 6393): Added TimaKeyStore provider
,D/Finsky  ( 6214): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/Finsky  ( 6214): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ResourcesManager( 6393): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/Finsky  ( 6214): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,E/SharedPreferencesImpl( 6214): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/SurfaceWidgetView( 1505): destroyHardwareResources():205734206
,V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  897): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/ActivityManager(  897): Killing 5489:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/Launcher( 1505): onRestart, Launcher: 1016242631
,D/Launcher( 1505): onStart, Launcher: 1016242631
D/Launcher.HomeView( 1505): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2090): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2090): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  897): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  897): Got RemoteException sending setActive(false) notification to pid 5735 uid 10374
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,F/libc    ( 6393): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78233388 in tid 6393 (ndroid.app.sns3)
,I/art     ( 1449): Explicit concurrent mark sweep GC freed 24936(1457KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 18MB/30MB, paused 498us total 53.110ms
,D/DeviceConnectionService( 1449): client connected with version: 7571000
,F/libc    ( 1449): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f9f2fe0 in tid 4506 (Binder_5)
F/libc    ( 6393): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2130): File locking failed. error= Bad file number
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
F/libc    ( 1449): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2130): File locking failed. error= Bad file number
E/audit_log( 2130): File locking failed. error= Bad file number
,I/ActivityManager(  897): Process com.sec.android.app.sns3 (pid 6393)(adj 0) has died(120,573)
,W/libprocessgroup(  897): failed to open /acct/uid_10094/pid_5489/cgroup.procs: No such file or directory
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,F/libc    ( 1505): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77ecc2bc in tid 1790 (RenderThread)
,F/libc    ( 1505): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2130): File locking failed. error= Bad file number
,D/LocationManagerService(  897): Location listener died
D/GpsStatusListenerHelper(  897): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@2dcebf58
I/LocationManagerService(  897): remove 18a4ef90 by com.google.android.gms
,D/LocationManagerService(  897): provider request: passive ProviderRequest[ON interval=0]
,V/BackupManagerService(  897): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  897): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,D/LocationManagerService(  897): Location listener died
I/LocationManagerService(  897): remove 3634f84a by com.google.android.gms
D/LocationManagerService(  897): provider request: passive ProviderRequest[ON interval=0]
E/SensorService(  897): Error disabling sensor 13 (Operation not permitted)
,D/WifiService(  897): Client connection lost with reason: 4
,I/EventHub(  897): Removing device '/dev/input/event4' due to inotify event
,W/GmsClient( 6214): service died
,E/Zygote  ( 6414): MountEmulatedStorage()
E/Zygote  ( 6414): v2
I/libpersona( 6414): KNOX_SDCARD checking this for 10036
I/libpersona( 6414): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.auth.sp.facebook.SnsAccountFbAuthSSOReceiver: pid=6414 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  897): Process com.google.android.gms.persistent (pid 1449)(adj 1) has died(131,573)
,I/Zygote  (  318): Process 6393 exited due to signal (7)
,F/libc    (  897): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa03c94bc in tid 918 (Binder_2)
F/libc    (  897): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2130): File locking failed. error= Bad file number
,F/libc    ( 5963): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb50d461c in tid 5976 (HeapTrimmerDaem)
F/libc    ( 5963): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2130): File locking failed. error= Bad file number
,W/Finsky  ( 6214): [1] GmsDeviceFeaturesHelper.onConnectionFailed: onConnectionFailed result: ConnectionResult{statusCode=INTERNAL_ERROR, resolution=null}
,I/Zygote  (  318): Process 1449 exited due to signal (7)
,I/Zygote  (  318): Process 1505 exited due to signal (7)
,I/Zygote  (  318): Process 5963 exited due to signal (7)
,I/SELinux ( 6414): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6414): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'wifi' died
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
W/Sensors ( 5365): sensorservice died [0xaef7c540]
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'backup' died
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
I/ServiceManager(  247): service 'commontime_management' died
I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died
I/ServiceManager(  247): service 'country_detector' died
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
E/audit_log( 2130): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
W/AudioFlinger(  290): power manager service died !!!
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
W/AudioFlinger(  290): power manager service died !!!
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
I/S,erviceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
E/audit_log( 2130): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'dbinfo' died
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (4/8)
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'usagestats' died
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/6)
I/ServiceManager(  247): service 'activity' died
I/SurfaceFlinger(  249): id=5 Removed DimLayer (0/5)
I/ServiceManager(  247): service 'scheduling_policy' died
I/SurfaceFlinger(  249): id=6 Removed DimLayer (2/4)
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'entropy' died
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/4)
I/ServiceManager(  247): service 'package' died
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/4)
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (0/3)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/3)
I/SurfaceFlinger(  249): id=15 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (0/2)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (0/1)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/1)
I/SurfaceFlinger(  249): id=15 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/1)
I/SurfaceFlinger(  249): id=14 Removed ColorFade (0/0)
I/SurfaceFlinger(  249): id=14 Removed ColorFade (-2/0)
F/libc    ( 6414): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759a5bd8 in tid 6414 (ndroid.app.sns3)
W/Sensors ( 5936): sensorservice died [0xaef79fc0]
F/libc    ( 6414): Unable to open connection to debuggerd: Connection refused
F/libc    ( 1874): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b74a2 in tid 6389 (AsyncOperationS)
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
F/libc    ( 1874): Unable to open connection to debuggerd: Connection refused
W/Sensors ( 2223): sensorservice died [0xaefbabc0]
W/Sensors ( 1483): sensorservice died [0xaefc5380]
E/WifiManager( 1483): Channel connection lost
W/Sensors ( 1298): sensorservice died [0xaed21300]
W/Sensors ( 1471): sensorservice died [0xaefbabc0]
W/Sensors ( 1171): sensorservice died [0xaef7f100]
E/WifiManager( 1171): Channel connection lost
E/WifiManager( 1571): Channel connection lost
E/WifiManager( 1298): Channel connection lost
,F/libc    ( 5560): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78a7f8b8 in tid 5560 (ogle.android.gm)
F/libc    ( 5560): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2130): File locking failed. error= Bad file number
F/libc    ( 4708): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7584ae46 in tid 4708 (oid.app.shealth)
F/libc    ( 4708): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2130): File locking failed. error= Bad file number
I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:90000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:90000 mC
,I/Zygote  (  318): Process 6414 exited due to signal (7)
F/libc    ( 1851): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7868d06b in tid 1851 (oid.inputmethod)
,F/libc    ( 1851): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2130): File locking failed. error= Bad file number
,F/libc    ( 4517): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73f67950 in tid 4536 (AppProvider)
,F/libc    ( 4517): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2130): File locking failed. error= Bad file number
,I/Zygote  (  318): Process 4708 exited due to signal (7)
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:80000 mC
,I/Zygote  (  318): Process 1874 exited due to signal (7)
,I/Zygote  (  318): Process 5560 exited due to signal (7)
I/Zygote  (  318): Process 1851 exited due to signal (7)
,I/Zygote  (  318): Process 4517 exited due to signal (7)
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor7:74000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor7:74000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS7' Sensor 'tsens_tz_sensor7' - alarm cleared 1 at 74.0 degC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:82000 mC
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:88000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:89000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:78000 mC
,D/AcmsKeyStoreHelper( 6125):  getKeyStoreForApplication Enter
,F/libc    ( 6125): Fatal signal 7 (SIGBUS), code 2, fault addr 0x735e3101 in tid 6159 (AcmsHandlerThre)
,F/libc    ( 6125): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2130): File locking failed. error= Bad file number
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:75000 mC
E/installd(  293): eof
E/installd(  293): failed to read size
I/installd(  293): closing connection
,I/Zygote  (  318): Process 6125 exited due to signal (7)
,I/SurfaceFlinger(  249): Disp[0] Orientation 0=>0
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:76000 mC,
,E/qdoverlay(  249): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  249): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  249): hwc_set_primary: display commit fail for 0 dpy!
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:76000 mC
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 74.0 degC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC

```
