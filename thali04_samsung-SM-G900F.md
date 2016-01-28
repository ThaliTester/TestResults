#### Test 573480784751f5c_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/Mms/FreeMessageReceiver( 5693): onReceive, action : android.intent.action.PACKAGE_ADDED
--------- beginning of system
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageReceiverService( 5693): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5693): onHandleIntent: ACTION_PACKAGE_ADDED
E/Zygote  ( 7327): MountEmulatedStorage()
E/Zygote  ( 7327): v2
I/libpersona( 7327): KNOX_SDCARD checking this for 10050
I/libpersona( 7327): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7327 uid=10050 gids={50050, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 7327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7327): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7327): TimaSignature is unavailable
D/ActivityThread( 7327): Added TimaKeyStore provider
D/ResourcesManager( 7327): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 7327): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7327): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/MyFiles ( 7327): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
E/installd(  297): system dir 0 : /system/app/
E/installd(  297): system dir 1 : /system/priv-app/
E/installd(  297): system dir 2 : /vendor/app/
E/installd(  297): system dir 3 : /oem/app/
I/TactileAssist(  902): enable value -1
I/TactileAssist(  902): internal enable value -1
I/TactileAssist(  902): intensity value -1
I/TactileAssist(  902): saveAppList value true
I/TactileAssist(  902): List of disabled apps :
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/PackageManager(  902): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 7346): MountEmulatedStorage()
E/Zygote  ( 7346): v2
I/libpersona( 7346): KNOX_SDCARD checking this for 10057
I/libpersona( 7346): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7346 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7346): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7346): TimaSignature is unavailable
D/ActivityThread( 7346): Added TimaKeyStore provider
D/ResourcesManager( 7346): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7346): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7346): onReceive() it will make start service
D/Compatibility( 7346): onHandleIntent()
D/Compatibility( 7346): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
D/Compatibility( 7346): found: 2
I/UpdateIcingCorporaServi( 1588): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7346): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7346): skipping ResolveInfo{1270b6a1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7346): considering ResolveInfo{132900c6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7346): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7346): enabling receiver ResolveInfo{5d5d887 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7346): enabling receiver ResolveInfo{237083b4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7346): enabling receiver ResolveInfo{30411bdd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7346): enabling receiver ResolveInfo{c246352 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7346): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/ContextImpl( 6257): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/ResourcesManager( 1588): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/UpdateIcingCorporaServi( 1588): UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7371): MountEmulatedStorage()
E/Zygote  ( 7371): v2
I/libpersona( 7371): KNOX_SDCARD checking this for 10098
I/libpersona( 7371): KNOX_SDCARD not a persona
D/AndroidRuntime( 7352): 
D/AndroidRuntime( 7352): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7352): CheckJNI is OFF
D/AndroidRuntime( 7352): setted country_code = Poland
I/ActivityManager(  902): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7371 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
D/AndroidRuntime( 7352): setted countryiso_code = PL
I/ActivityManager(  902): Killing 6294:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
D/AndroidRuntime( 7352): setted sales_code = XEO
D/AndroidRuntime( 7352): readGMSProperty: start
D/AndroidRuntime( 7352): readGMSProperty: already setted!!
D/AndroidRuntime( 7352): readGMSProperty: end
D/AndroidRuntime( 7352): addProductProperty: start
I/SELinux ( 7371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/TimaKeyStoreProvider( 7371): TimaSignature is unavailable
D/ActivityThread( 7371): Added TimaKeyStore provider
W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6294/cgroup.procs: No such file or directory
D/ResourcesManager( 7371): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager( 7371): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/AffinityControl( 7352): AffinityControl: registerfunction enter
D/AndroidRuntime( 7352): Calling main entry com.android.commands.am.Am
E/[CarMode]( 7371): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7371): SampleAppCoreManager VACVersion '2.2.0.11867'
E/PersonaManagerService(  902): inState():  stateMachine is null !!
I/VlingoAndroidCore( 7371): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  902): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 902  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  902): mDVFSHelper.acquire()
D/FocusedStackFrame(  902): Set to : 0
D/Launcher.HomeView( 1536): onPause
D/Launcher( 1536): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7352): Shutting down VM
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/Zygote  ( 7398): MountEmulatedStorage()
E/Zygote  ( 7398): v2
I/libpersona( 7398): KNOX_SDCARD checking this for 10191
I/libpersona( 7398): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7398 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SELinux ( 7398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7398): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/Zygote  ( 7411): MountEmulatedStorage()
E/Zygote  ( 7411): v2
I/libpersona( 7411): KNOX_SDCARD checking this for 10032
I/libpersona( 7411): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7411 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/MicrophoneInputStream( 1588): mic_close gfk@145662ad
I/SELinux ( 7411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TimaKeyStoreProvider( 7398): TimaSignature is unavailable
E/SELinux ( 7411): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityThread( 7398): Added TimaKeyStore provider
V/AudioPolicyManager(  294): stopInput() input 29
V/AudioPolicyManager(  294): releaseInput() 29
V/AudioPolicyManager(  294): closeInput(29)
V/audio_hw_primary(  294): in_standby: enter
I/HotwordRecognitionRnr( 1588): Stopping hotword detection.
I/HotwordRecognitionRnr( 1588): Hotword detection finished
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  902): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher.HomeView( 1536): onStop
V/ActivityManager(  902): Display changed displayId=0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2120): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2120): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2120): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2120): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2120): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SurfaceWidgetView( 1536): destroyHardwareResources():835348322
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/audio_hw_primary(  294): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  294): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  294): disable_audio_route: reset mixer path: audio-record
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  294): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): disable_audio_route: exit
V/audio_hw_primary(  294): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: DEC2 Volume
D/audio_route(  294): Setting mixer control: value: 0
D/audio_route(  294): Setting mixer control: SLIM TX7 MUX, value: 0
D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  294): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  294): Setting mixer control: value: 0
D/audio_route(  294): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): stop_input_stream: exit: status(0)
V/audio_hw_primary(  294): in_standby: exit:  status(0)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/audio_hw_primary(  294): adev_close_input_stream
V/audio_hw_primary(  294): in_standby: enter
D/TimaKeyStoreProvider( 7411): TimaSignature is unavailable
V/audio_hw_primary(  294): in_standby: exit:  status(0)
E/audio_hw_primary(  294): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  294): releaseInput() exit
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ActivityThread( 7411): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/accuweather( 2120): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2120): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ResourcesManager( 7398): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager( 7411): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
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
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ResourcesManager( 7411): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Launcher( 1536): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SurfaceWidgetView( 1536): destroyHardwareResources():835348322
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/SMD     (  286): DCD ON
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/System.out( 7411): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7411): Inside WakeupProvider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/DatabaseUtils( 7411): Writing exception to parcel
E/DatabaseUtils( 7411): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7411): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7411): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7411): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7411): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7411): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7411): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7411): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7411): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7411): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7411): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7371): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/AlarmManager(  902): waitForAlarm result :8
I/VlingoApplication( 7411): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
D/PowerManagerService(  902): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  902): Nap time (uid 1000)...
I/PowerManagerService(  902): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  902): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  902): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI(  902): setDeviceInteractive: 0
D/PowerManagerService(  902): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService(  902): handleSandman : startDream()
E/PowerManagerService(  902): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  902): Sleeping (uid 1000)...
D/PowerManagerService(  902): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  902): [input device light] setInputDeviceLightOn is called : 0
D/InputManager-JNI(  902): sysfs_write +: /sys/class/input/event2/device/enabled: 0
I/SurfaceFlinger(  257): id=15 createSurf (1080x1920),2 flag=404, ColorFade
D/PowerManagerService(  902): [input device light] handleInputDeviceLightOff
D/InputManager-JNI(  902): sysfs_write +: /sys/class/input/event1/device/enabled: 0
I/WebViewFactory( 7398): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/InputManager-JNI(  902): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ResourcesManager( 7398): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/InputManager-JNI(  902): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/SContextService(  902): 	.unregisterCallback : 1, client=
D/SContextService(  902): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@1703ea12, Service = Auto Rotation, used = 1
W/CAE     (  902): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  902): stop(ContextProvider.java:149)
V/CAE     (  902): clear(AutoRotationRunner.java:182)
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
V/CAE     (  902): disable(AutoRotationRunner.java:171)
I/CAE     (  902): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  902): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs(  301): sendContextData: -78, 7, 0, 0
W/System.err( 7371): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7371): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7371): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7371): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7371): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7371): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7371): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7371): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7371): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7371): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7371): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7371): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7371): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7371): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7371): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7371): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7371): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7371): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7371): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7371): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7371): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7371): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7371): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/CAE     (  902): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  902): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
I/LibraryLoader( 7398): Loading: webviewchromium
I/LibraryLoader( 7398): Time to load native libraries: 2 ms (timestamps 3762-3764)
I/LibraryLoader( 7398): Expected native library version number "",actual native library version number ""
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
E/DatabaseUtils( 7411): Writing exception to parcel
E/DatabaseUtils( 7411): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7411): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7411): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7411): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7411): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7411): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7411): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7411): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7411): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7411): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7411): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7371): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/System.err( 7371): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7371): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7371): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7371): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7371): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7371): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7371): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7371): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7371): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7371): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7371): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7371): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7371): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7371): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7371): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7371): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7371): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7371): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7371): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7371): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7371): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7371): [DLApplication]-Init Called!:false
E/[CarMode]( 7371): [DLApplication]-Init Started!:true
V/WebViewChromiumFactoryProvider( 7398): Binding Chromium to main looper Looper (main, tid 1) {30411bdd}
E/Watchdog(  902): !@Sync 3
I/LibraryLoader( 7398): Expected native library version number "",actual native library version number ""
I/chromium( 7398): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/[CarModeFW]( 7371): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7371): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7371): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7371): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7371): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7371): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7371): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7371): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7371): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7371): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7371): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7371): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7371): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7371): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoAndroidCore( 7411): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/BrowserStartupController( 7398): Initializing chromium process, renderers=0
W/art     ( 7398): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7398): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7398): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7398): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/CAE     (  902): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  902): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  902): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  902): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  902): removeSContextService() : service = Auto Rotation
D/SContextService(  902): ===== SContext Service List =====
D/SContextManager(  902):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@a0d1c, service=Auto Rotation
D/KeyguardViewMediator( 1182): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1182): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1182): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1182): notifyScreenOffLocked
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/MessageDataHandler( 7371): initialize
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/[CarModeFW]( 7371): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7371): CDH-initiazlieCaches : after sync
I/SQLiteSecureOpenHelper( 3511): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3511): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/KeyguardViewMediator( 1182): timeout : 5000
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/DisplayPowerController(  902): ColorFade: onAnimationStart
D/DisplayPowerController(  902): getFinalBrightness : 8 -> 0
I/Adreno-EGL( 7398): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7398): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7398): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7398): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7398): Remote Branch: 
I/Adreno-EGL( 7398): Local Patches: 
I/Adreno-EGL( 7398): Reconstruct Branch: 
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/lights  (  902): lcd : 0 +
D/DisplayPowerController(  902): getFinalBrightness : 8 -> 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/lights  (  902): lcd : 0 -
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/KeyguardViewMediator( 1182): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1182): handleNotifyScreenOff
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LightsService(  902): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 902) 
D/LightsService(  902): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/LightsService(  902): [SvcLED]  onSensorChanged::light value = 5
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SensorManager(  902): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  902): turn on LED for fully charged
D/SensorManager(  902): unregisterListener ::   
D/lights  (  902): led_pattern : 5 +
D/lights  (  902): led_pattern : 5 -
D/LightsService(  902): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
W/chromium( 7398): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/[CarModeFW]( 7371): CDH-buildContactCacheWireFrame : cur len =0
W/chromium( 7398): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/CAE     (  902): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  902): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  902): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  902): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  301): sendContextData: -76, 13, -46, 0
D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/art     ( 7398): Attempt to remove local handle scope entry from IRT, ignoring
D/[CarModeFW]( 7371): CDH-ContactDataHandler initiazlieCaches time : 127
D/[CarModeFW]( 7371): CDH-initiazlieCaches : end sync
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/AwContents( 7398): onDetachedFromWindow called when already detached. Ignoring
I/CAE     (  902): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 54, 0,
D/SensorHubManager(  902): SendSensorHubData: send data = -63, 14, 12, 54, 0
D/Sensorhubs(  301): sendContextData: -63, 14, 12, 54, 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/SystemWebViewEngine( 7398): CordovaWebView is running on device made by: samsung
E/MotionRecognitionService(  902):  handler : SCREEN_OFF end 
D/[CarModeFW]( 7371): DrivingManager-initialize...
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SensorService(  902): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  902): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  902): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/WifiStateMachine(  902): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  902): handleScreenStateChanged Exit: false
E/WifiStateMachine(  902): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  902): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  902): do suspend true
D/NotificationService(  902): ACTION_SCREEN_OFF
D/LightsService(  902): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 902) 
D/LightsService(  902): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  902): [SvcLED]  onSensorChanged::light value = 5
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SensorManager(  902): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  902): unregisterListener ::   
D/LightsService(  902): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/art     ( 7398): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7398): Attempt to remove local handle scope entry from IRT, ignoring
D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  294): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  294): adev_set_parameters: exit
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/VlingoApplication( 7411): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7411): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/SecExternalDisplayIntents_Java(  902): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/DisplayPowerState(  902): !@ ColorFade entry
D/DisplayPowerController(  902): ColorFade: onAnimationEnd
D/IpRemoteDisplayController(  902): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  902): Bridge Server is not available
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/AutomaticBrightnessController(  902): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  902): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  902): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  902): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/VolumePanel( 1182): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1182): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
E/LightSensor(  902): Light old sensor_state 513, new sensor_state : 1 en : 0
D/VolumePanel( 1182): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1182): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SensorManager(  902): unregisterListener ::   
E/Sensors (  902): Acc old sensor_state 1, new sensor_state : 0 en : 0
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/PersonaManagerService(  902): ACTION_SCREEN_OFF onReceive
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SensorManager(  902): unregisterListener ::   
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/DisplayPowerController(  902): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  902): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  902): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
V/ActivityManager(  902): Display changed displayId=0
D/PersonaManagerServiceHandler(  902): MSG_ACTION_SCREEN_OFF called
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/NfcService( 1494): call the applyRotuiing
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/StatusBar.NetworkController( 1182): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/Activity( 7398): performCreate Call secproduct feature valuefalse
D/Activity( 7398): performCreate Call debug elastic valuetrue
D/STATUSBAR-PhoneStatusBar( 1182):      ACTION_SCREEN_OFF is finished!!!! 
E/StatusBar( 1182): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1182): dismissHelpPopup 
D/accuweather( 2120): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2120): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2120): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SystemBroadcastReceiver( 6424): [#DCM#] [DCM_Performance] onReceive completed in time  1416 microsec. 
I/SystemBroadcastReceiver( 6424): [#DCM#] Calling notifyListeners. 
I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
W/ActivityManager(  902): getTasks: caller 10085 does not hold GET_TASKS; limiting output
W/ActivityManager(  902): getTasks: caller 10085 does not hold GET_TASKS; limiting output
D/PowerManagerService(  902): [PWL] sb release: PowerManagerService.Broadcasts
I/DCMPolicyManager( 6424): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 6424): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
D/SSRM:m  (  902): SIOP:: AP = 380, PST = 382, CUR = 450
I/MediaPlayer( 7371): Need to enable context aware info
V/MediaPlayer-JNI( 7371): native_setup
V/MediaPlayer( 7371): constructor
V/MediaPlayer( 7371): setListener
E/MediaPlayer-JNI( 7371): QCMediaPlayer mediaplayer NOT present
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  276): 
D/[CarModeFW]( 7371): PushMessageManager-bindPushMessageService
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
I/[CarModeFW]( 7371): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7371): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1453985640577
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1453985640577
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1453985640578
D/[CarMode]( 7371): [DLServiceManager]-requestRecommendedLocationList
I/[CarMode]( 7371): [LogNotNull]-Package name is: com.google.android.apps.maps
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1453985640579
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1453985640580
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1453985640580
E/[CarMode]( 7371): [DLApplication]-Init End!:true
D/TP/SmsProvider( 1500): query,matched:2, calling pid = 7371
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1500): query,matched:2, calling pid = 7371
D/TP/SmsProvider( 1500): match 2:Elapsed time : 0.259 ms
D/TP/SmsProvider( 1500): match 2:Elapsed time : 4.695 ms
W/ActivityManager(  902): Activity pause timeout for ActivityRecord{16b64fae u0 com.test.thalitest/.MainActivity t9}
E/Zygote  ( 7478): MountEmulatedStorage()
I/libpersona( 7478): KNOX_SDCARD checking this for 10003
E/Zygote  ( 7478): v2
I/libpersona( 7478): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7478 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/art     (  315): Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 11.421ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 8.051ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 7.494ms
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
D/SurfaceControl(  902): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService(  902): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/MISC PowerHAL(  902): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  902): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  902): Got set_interactive hint
D/[CarModeFW]( 7371): CDH-buildContactCacheWireFrame : cur len =0
I/SELinux ( 7478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/PowerManagerService(  902): [PWL] Off : 0s ago
I/PowerManagerService(  902): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  902): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=902, ws=null) (elapsedTime=547)
I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=108)
I/SELinux ( 7478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=107)
I/PowerManagerService(  902): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  902): [PWL]     mDisplayReady : false
D/DisplayPowerController(  902): getFinalBrightness : 0 -> 0
D/PowerManagerService(  902): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  902): [PWL] sb release: PowerManagerService.Display
E/SELinux ( 7478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MessageDataHandler( 7371):  getInboxList smsCursor : 64
D/TP/MmsProvider( 1500): Query uri=content://mms, match=0, calling pid = 7371
D/[CarMode]( 7371): [DLApplication]-GooglePlayServices SUCCESS.
D/OpenGLRenderer( 7398): Render dirty regions requested: true
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/TP/MmsProvider( 1500): Query uri=content://mms/inbox, match=2, calling pid = 7371
D/TimaKeyStoreProvider( 7478): TimaSignature is unavailable
D/ActivityThread( 7478): Added TimaKeyStore provider
E/Zygote  ( 7494): MountEmulatedStorage()
E/Zygote  ( 7494): v2
I/libpersona( 7494): KNOX_SDCARD checking this for 10019
I/libpersona( 7494): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7494 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
D/ActivityManager(  902): post active user change for 0
D/KnoxTimeoutHandler(  902): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  902): handleActiveUserChange for user 0
E/[CarMode]( 7371): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
I/UpdateManagerReceiver( 7371): Intent : android.intent.action.PACKAGE_ADDEDThu Jan 28 13:54:00 GMT+01:00 2016
I/SELinux ( 7494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7494): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/MessageDataHandler( 7371):  getInboxList mmsCursor : 65
I/ActivityManager(  902): Killing 6314:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##41
D/[CarModeFW]( 7371): CDH-buildContactCacheWireFrame : cur len =0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 7478): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
E/Zygote  ( 7507): MountEmulatedStorage()
E/Zygote  ( 7507): v2
I/libpersona( 7507): KNOX_SDCARD checking this for 1000
I/libpersona( 7507): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7507 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7494): TimaSignature is unavailable
D/ActivityThread( 7494): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 7478): PlaceProvider onCreate()
D/MessageDataHandler( 7371):  getInboxList mms,sms cursor join : 78
D/[CarModeFW]( 7371): RecommendHandler-selection = type = '3'
D/[CarModeFW]( 7371): PushMessageService-onCreate
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
I/MessageDataHandler( 7371): getUnreadMessageCount :0
D/LockPatternUtilsCache( 1182): value : false
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 215
I/ActivityManager(  902): Killing 6559:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
I/ActivityManager(  902): Killing 6370:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##42
I/ActivityManager(  902): Killing 6351:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##43
D/ResourcesManager( 7494): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/OpenGLRenderer( 7398): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7398): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7398): Enabling debug mode 0
,D/[CarModeFW]( 7371): CDH-buildContactCacheWireFrame : cur len =0
,D/TimaKeyStoreProvider( 7507): TimaSignature is unavailable
,D/ActivityThread( 7507): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1500): query,matched:0, calling pid = 7371
V/TP/MmsSmsProvider( 1500): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1500): match 0:Elapsed time : 1.936 ms
,D/[CarModeFW]( 7371): RecommendHandler-selection = type = '3'
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/[CarModeFW]( 7371): PushMessageManager-onServiceConnected
,D/[CarModeFW]( 7371): PushMessageService-registerPushMessageServiceListener
,W/libprocessgroup(  902): failed to open /acct/uid_10035/pid_6314/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1500): query,matched:13, calling pid = 7371
,D/ResourcesManager( 7507): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/TP/MmsSmsProvider( 1500): match 13:Elapsed time : 1.499 ms
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/MessageDataHandler( 7371):  getInboxList address cursor : 8
,D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/TP/MmsSmsProvider( 1500): query,matched:0, calling pid = 7371
V/TP/MmsSmsProvider( 1500): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1500): match 0:Elapsed time : 2.178 ms
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/CustomFrequencyManagerService(  902): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 902  tag : ACTIVITY_RESUME_BOOSTER@6
,W/IInputConnectionWrapper( 7398): showStatusIcon on inactive InputConnection
I/Timeline( 7398): Timeline: Activity_idle id: android.os.BinderProxy@11641e4 time:104591
,W/ActivityManager(  902): mDVFSHelper.release()
I/Timeline(  902): Timeline: Activity_windows_visible id: ActivityRecord{16b64fae u0 com.test.thalitest/.MainActivity t9} time:104592
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SurfaceFlinger(  257): id=14 Removed Starting com.test.thalitest (6/9)
,D/MessageDataHandler( 7371):  getInboxList thread cursor : 40
I/SurfaceFlinger(  257): id=14 Removed Starting com.test.thalitest (-2/9)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/MessageDataHandler( 7371):  thread, addr result: 6
I/[CarModeFW]( 7371): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 310
I/[CarModeFW]( 7371): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 310
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ContextImpl( 7507): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7533): MountEmulatedStorage()
I/libpersona( 7533): KNOX_SDCARD checking this for 10111
E/Zygote  ( 7533): v2
I/libpersona( 7533): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7533 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/JsMessageQueue( 7398): Set native->JS mode to OnlineEventsBridgeMode
,D/UserAnalysis.SecureDbManager( 7478): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7478): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7478): Create SecureDbHelper
,I/SELinux ( 7533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7533): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7507): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/IntelligenceServiceApplication( 7478): onCreate()
,I/SQLiteSecureOpenHelper( 7478): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7478): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7478): Open Place.db in secure mode
,D/TimaKeyStoreProvider( 7533): TimaSignature is unavailable
,D/ActivityThread( 7533): Added TimaKeyStore provider
,E/FilterInstaller( 7507): There is no requred permission
,I/ActivityManager(  902): Killing 2700:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,I/SQLiteSecureOpenHelper( 7478): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7478): ...getDatabaseLocked(b,b,pwd)
,D/jxcore_app_log( 7398): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358141952
,D/ResourcesManager( 7533): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/PackageIntentReceiver( 7533): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7533): Not GearManger package! 
,I/art     (  902): Explicit concurrent mark sweep GC freed 242655(16MB) AllocSpace objects, 4(4MB) LOS objects, 30% free, 35MB/51MB, paused 1.855ms total 116.321ms
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7551): MountEmulatedStorage()
E/Zygote  ( 7551): v2
I/libpersona( 7551): KNOX_SDCARD checking this for 10117
I/libpersona( 7551): KNOX_SDCARD not a persona
,I/chromium( 7398): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  902): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7551 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 6197:com.google.android.talk/u0a116 (adj 15): bgCount ##41
,I/SELinux ( 7551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarModeFW]( 7371): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 7371): MyPlaceProvider-=============
D/[CarModeFW]( 7371): MyPlaceProvider-=============
D/[CarModeFW]( 7371): MyPlaceProvider-=============
E/SELinux ( 7551): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 7371): MyPlaceProvider-=============
D/[CarModeFW]( 7371): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7371): MyPlaceProvider-==============
D/[CarModeFW]( 7371): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7371): MyPlaceProvider-==============
,D/[CarModeFW]( 7371): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7371): MyPlaceProvider-==============
D/[CarModeFW]( 7371): MyPlaceProvider-latitude is not valid
,W/libprocessgroup(  902): failed to open /acct/uid_10037/pid_6351/cgroup.procs: No such file or directory
W/libprocessgroup(  902): failed to open /acct/uid_10037/pid_6370/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6559/cgroup.procs: No such file or directory
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 611
,D/[CarMode]( 7371): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@2ecc33ca, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ae88dcf8] LOCATIONS
,D/TimaKeyStoreProvider( 7551): TimaSignature is unavailable
,D/ActivityThread( 7551): Added TimaKeyStore provider
,W/libprocessgroup(  902): failed to open /acct/uid_10045/pid_2700/cgroup.procs: No such file or directory
,D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 656
I/[CarModeFW]( 7371): -[snowdeer] Rec : Missed Call : 445
,I/[CarModeFW]( 7371): -[snowdeer] Rec : Favorite : 9
,D/ResourcesManager( 7551): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,I/chromium( 7398): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7398): 
,W/ResourcesManager( 7551): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/[CarModeFW]( 7371): -[snowdeer] Rec : CallLog : 8
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7569): MountEmulatedStorage()
I/libpersona( 7569): KNOX_SDCARD checking this for 10045
E/Zygote  ( 7569): v2
I/libpersona( 7569): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7569 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7569): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  902): failed to open /acct/uid_10116/pid_6197/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7569): TimaSignature is unavailable
D/ActivityThread( 7569): Added TimaKeyStore provider
,D/MagazineService Version( 7551): Magazine-Administrator: 11
,D/MagazineService Version( 7551): Magazine-Provider: 14
,I/ActivityManager(  902): Killing 6651:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,D/MagazineService Version( 7551): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7551): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7551): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,D/ResourcesManager( 7569): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7569): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7551): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7585): MountEmulatedStorage()
I/libpersona( 7585): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7585): v2
I/libpersona( 7585): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7585 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7551): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/System.out( 7411): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7585): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  902): Killing 6673:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7585): TimaSignature is unavailable
,D/ActivityThread( 7585): Added TimaKeyStore provider
,W/libprocessgroup(  902): failed to open /acct/uid_10074/pid_6651/cgroup.procs: No such file or directory
,D/ResourcesManager( 7585): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/CalendarProvider2( 7569): CalendarProvider2.onCreate() called
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6673/cgroup.procs: No such file or directory
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7602): MountEmulatedStorage()
I/libpersona( 7602): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7602): v2
I/libpersona( 7602): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 6717:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/SELinux ( 7602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7602): TimaSignature is unavailable
,D/ActivityThread( 7602): Added TimaKeyStore provider
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6717/cgroup.procs: No such file or directory
,D/ResourcesManager( 7602): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AcmsPackageEventListener( 7602): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7602): Enter Oncreate
,D/AcmsServiceMonitor( 7602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 7602): creating AcmsCore
,D/AcmsCore( 7602): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7602): AcmsCore
,D/AcmsCore( 7602): init
,D/AcmsCore( 7602): Looper handler is not null
D/AcmsCore( 7602): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7602): Incrementing - Counter value: 1
,D/AcmsCore( 7602): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 7602): onStartCommand
,D/AcmsCertificateMngr( 7602): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7602): AcmsRevocationMngr
,D/AcmsService( 7602): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7602): Enter incrementSvcCounter with startId 1
,D/AcmsServiceMonitor( 7602): Incrementing - Counter value: 2
,D/AcmsService( 7602): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7602): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7602): Inside handle Intent
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/AcmsService( 7602): App added - package name: com.test.thalitest
,D/AcmsCore( 7602): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 7602): Incrementing - Counter value: 3
D/AcmsCore( 7602): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7602): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7602): Decrementing - Counter value: 2
,E/Zygote  ( 7620): MountEmulatedStorage()
I/libpersona( 7620): KNOX_SDCARD checking this for 10165
E/Zygote  ( 7620): v2
I/libpersona( 7620): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7620 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 7371): -[snowdeer] Rec : Schedule : 595
,I/[CarModeFW]( 7371): -[snowdeer] Rec : During DL app : 1
,I/[CarModeFW]( 7371): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7371): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7371): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7371): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7371): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7371): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 1272
,D/TimaKeyStoreProvider( 7620): TimaSignature is unavailable
,D/ActivityThread( 7620): Added TimaKeyStore provider
,D/ResourcesManager( 7620): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/[CarModeFW]( 7371): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7371): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7371): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7371): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 1335
,D/KidsPlatformStub( 7620): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7638): MountEmulatedStorage()
I/libpersona( 7638): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7638): v2
I/libpersona( 7638): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7638 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 7638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7638): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7638): TimaSignature is unavailable
,D/ActivityThread( 7638): Added TimaKeyStore provider
,D/ResourcesManager( 7638): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7638): (284) automatic index on shooting_modes(title_id)
,D/Finsky  ( 6575): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  902): Killing 6032:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2490): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2490): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2490): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6032/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2490): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 2490): Submit a task: k
D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 2490): Processing package: com.test.thalitest
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7661): MountEmulatedStorage()
E/Zygote  ( 7661): v2
I/libpersona( 7661): KNOX_SDCARD checking this for 10039
I/libpersona( 7661): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7661 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/GassUtils( 2490): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2490): Found info for package com.test.thalitest in db.
I/SELinux ( 7661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7661): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
D/TimaKeyStoreProvider( 7661): TimaSignature is unavailable
D/ActivityThread( 7661): Added TimaKeyStore provider
D/ResourcesManager( 7661): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
D/AcmsKeyStoreHelper( 7602):  getKeyStoreForApplication Enter
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
W/BaseAppContext( 2490): Using Auth Proxy for data requests.
I/AcmsKeyStoreHelper( 7602): Key Store exist
I/AcmsKeyStoreHelper( 7602): Hence loading the keystore file
V/TaskCloserActivity( 6049): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
I/ActivityManager(  902): Killing 6236:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
D/BootupListener( 1500): ACTION_DRIVELINK
D/SettingsProvider(  902): name = drivelink_navigation
D/SettingsProvider(  902): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  902): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  902): selectionArgs: false
D/SettingsProvider(  902): selectionArgs: 1001
D/SecContentProvider(  902): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  902): ret = -1
D/BootupListener( 1500): NAVI : com.google.android.apps.maps
D/SettingsProvider(  902): name = internet_call_settings_visibility
D/SettingsProvider(  902): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  902): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  902): selectionArgs: false
D/SettingsProvider(  902): selectionArgs: 1001
D/SecContentProvider(  902): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  902): ret = -1
D/AcmsKeyStoreHelper( 7602):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7602): getKeyStoreForApplication success 
D/AcmsCore( 7602): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7602): Decrementing - Counter value: 1
D/AcmsCore( 7602): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 7602): This is NOT a valid MirrorLink app
D/AcmsCore( 7602): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7602): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7602): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7602): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor( 7602): getSvcCounter - Counter value: 0
D/AcmsService( 7602): Enter onDestroy
I/AcmsService( 7602): cleanUp(): inside service clean up
D/AcmsCore( 7602): AcmsCore: inside DeInit
D/AcmsCore( 7602): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7602): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7602): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7602): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7602): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7602): getSvcCounter - Counter value: 0
D/AcmsService( 7602): killing acms process
I/Process ( 7602): Sending signal. PID: 7602 SIG: 9
W/jxcore-log( 7398): Initializing JXcore engine
W/jxcore-log( 7398): JXcore engine is ready
I/ActivityManager(  902): Process ACMS.Process (pid 7602)(adj 0) has died(61,545)
W/libprocessgroup(  902): failed to open /acct/uid_10167/pid_6236/cgroup.procs: No such file or directory
D/SecurityLogAgent:SEDenialService(  902): Got Modify Event and sending Denial Intent foraudit.log
E/auditd  ( 2156): In denial and Property audit_ondenial is set to 1 
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  902): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
W/jxcore-log( 7398): Starting JXcore engine
E/Zygote  ( 7679): MountEmulatedStorage()
E/Zygote  ( 7679): v2
I/libpersona( 7679): KNOX_SDCARD checking this for 1000
I/libpersona( 7679): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7679 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/art     (  315): Explicit concurrent mark sweep GC freed 8762(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 14.941ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.710ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.843ms
I/SELinux ( 7679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/jxcore-log( 7398): Platform android
W/jxcore-log( 7398): 
W/jxcore-log( 7398): Process ARCH arm
W/jxcore-log( 7398): 
D/TimaKeyStoreProvider( 7679): TimaSignature is unavailable
D/ActivityThread( 7679): Added TimaKeyStore provider
D/ResourcesManager( 7679): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/SecurityLogAgent( 7679):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 7679):  SeDenialReceiver : File path = null
I/ActivityManager(  902): Killing 6163:com.google.android.gm/u0a113 (adj 15): bgCount ##41
I/CalendarProvider2( 7569): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/SMD     (  286): DCD ON
E/Zygote  ( 7694): MountEmulatedStorage()
E/Zygote  ( 7694): v2
I/libpersona( 7694): KNOX_SDCARD checking this for 10148
I/libpersona( 7694): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7694 uid=10148 gids={50148, 9997} abi=armeabi-v7a
W/art     ( 2490): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 116.935ms
I/SELinux ( 7694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  902): failed to open /acct/uid_10113/pid_6163/cgroup.procs: No such file or directory
I/SELinux ( 7694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  902): Killing 6424:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
E/SELinux ( 7694): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7694): TimaSignature is unavailable
,D/ActivityThread( 7694): Added TimaKeyStore provider
,D/ResourcesManager( 7694): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7694): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7694): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  902): failed to open /acct/uid_10004/pid_6424/cgroup.procs: No such file or directory
,E/Zygote  ( 7709): MountEmulatedStorage()
,E/Zygote  ( 7709): v2
I/libpersona( 7709): KNOX_SDCARD checking this for 10149
I/libpersona( 7709): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7709 uid=10149 gids={50149, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 6508:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/SELinux ( 7709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7709): TimaSignature is unavailable
,D/ActivityThread( 7709): Added TimaKeyStore provider
,D/ResourcesManager( 7709): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7709): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7709): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  902): failed to open /acct/uid_10043/pid_6508/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2490): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2490): Module APK com.google.android.play.games already loaded
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager(  902): Killing 6106:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
,I/jxcore-log( 7398): JXcore Cordova bridge is ready!
I/jxcore-log( 7398): 
,W/jxcore-log( 7398): JXcore engine is started
,I/GAV2    ( 7152): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup(  902): failed to open /acct/uid_10093/pid_6106/cgroup.procs: No such file or directory
,I/jxcore-log( 7398): Toggling radios to true
I/jxcore-log( 7398): 
,D/BluetoothAdapter( 7398): enable()
,D/BluetoothAdapter( 7398): enable(): BT is already enabled..!
,D/WifiService(  902): New client listening to asynchronous messages
,I/WifiManager( 7398): packageName : com.test.thalitest
,D/SecContentProvider(  902): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  902): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  902): mCursor = null
,D/WifiService(  902): setWifiEnabled: true pid=7398, uid=10191
,E/WifiService(  902): Invoking mWifiStateMachine.setWifiEnabled
,I/Icing   ( 2490): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
W/ActivityManager(  902): Permission Denial: getCurrentUser() from pid=7398, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  902): Failed getting userId using ActivityManagerNative
W/WifiService(  902): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7398, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  902): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  902): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  902): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  902): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  902): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  902): name = wifi_on
,I/WifiService(  902): disconnect: pid=7398, uid=10191
,I/jxcore-log( 7398): Radios toggled
I/jxcore-log( 7398): 
,I/jxcore-log( 7398): My device name is: samsung-SM-G900F
I/jxcore-log( 7398): 
I/wpa_supplicant( 1281): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1281): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1281): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  902): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1281): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1281): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1281): Disconnected - do not scan
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  902): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  902): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  902): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  902): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  902): do suspend true
D/ResourcesManager( 2490): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/WifiP2pService(  902): InactiveState{ what=143375 }
,D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2231): Read error: ssl=0x99c31e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2231): SSL shutdown failed: ssl=0x99c31e00: I/O error during system call, Broken pipe
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  902): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  902): updateNetworkInfo()
D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  902): updateNetworkInfo()
D/ConnectivityService(  902): ignoring duplicate network state non-change
,E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/ConnectivityService(  902): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,E/WifiStateMachine(  902): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1281): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1281): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1281): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1281): First Scan Start
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1281): Scan requested (ret=0) - scan timeout 30 seconds
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Validated
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  902): ConnectModeState: Network connection lost 
D/StatusBar.NetworkController( 1182): applyOpen
,E/WifiStateMachine(  902): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  902): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  902): do suspend true
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  902): InactiveState{ what=143375 }
,D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1302): Starting #6
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,I/Icing   ( 2490): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService(  902): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  902): Not allowed due to - mEnabled false
E/WifiStateMachine(  902): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  902): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  902): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524292
D/ConnectivityService(  902): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  902): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  902): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Disconnected - quitting
D/TelephonyNetworkFactory( 1500): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524292
,D/WifiStateMachine(  902): updateConfiguredNetworkExpiration - currTime: 1453985643626
,D/WifiStateMachine(  902): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
E/WifiStateMachine(  902): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiNetworkAgent(  902): NetworkAgent: NetworkAgent channel lost
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  902): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  902): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/ConnectivityService(  902): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
V/NetworkStats(  902): updateIfacesLocked()
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
V/NetworkStats(  902): performPollLocked(flags=0x1)
,D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  902): UpdateStatsForKnox
D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  902): mCursor = null
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
V/NetworkStats(  902): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  902): mCursor = null
,V/NetworkStats(  902): performPollLocked() took 18ms
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
I/Hs20UtilService( 1302): Starting #7
I/Hs20UtilService( 1302): Message received 5007
,D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,I/VacuumService( 2231): Vacuum at: now=1453985643733 tag=VacuumService
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1500): FileWriteThread : threadType = 3
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 2120): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/ApplicationPolicy(  902): updateDataUsageMap
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  902): MasterInitialState.processMessage what=3
D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,D/SmartBondingService(  902): getSBEnabled() enabled =false
I/CLocInfoService(  902): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  902): CLoinfo wifi false
,W/SLocation(  902): No Active Data Connection
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7233): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7233): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7233): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7233): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
,I/NetworkMonitor( 5319): type=WIFI subType= reason=null isConnected=false
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7782): MountEmulatedStorage()
E/Zygote  ( 7782): v2
I/libpersona( 7782): KNOX_SDCARD checking this for 10002
I/libpersona( 7782): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3699): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/ActivityManager(  902): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7782 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7233): noConnectivity : true
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/DBG_DM  ( 3699): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SELinux ( 7782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7782): TimaSignature is unavailable
,D/ActivityThread( 7782): Added TimaKeyStore provider
,D/ResourcesManager( 7782): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  902): Killing 6121:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7802): MountEmulatedStorage()
E/Zygote  ( 7802): v2
I/libpersona( 7802): KNOX_SDCARD checking this for 1000
I/libpersona( 7802): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7802 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7802): TimaSignature is unavailable
,D/ActivityThread( 7802): Added TimaKeyStore provider
,D/ResourcesManager( 7802): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  902): failed to open /acct/uid_10102/pid_6121/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7802): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7802): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7802): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7802): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7802): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7802): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7819): MountEmulatedStorage()
E/Zygote  ( 7819): v2
I/libpersona( 7819): KNOX_SDCARD checking this for 10010
I/libpersona( 7819): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7819 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1281): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1281): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1281): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1281): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  902): [1,453,985,644,646 ms] noteScanEnd no scan source
,I/SELinux ( 7819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/WifiStateMachine(  902): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@35abecd3 sup_state=SCANNING debouncing=false
,I/SELinux ( 7819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  902): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  902): setDetailed state send new extra info0x
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,I/CLocInfoService(  902): External Intent Received android.net.wifi.SCAN_RESULTS
,E/SELinux ( 7819): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7819): TimaSignature is unavailable
,D/ActivityThread( 7819): Added TimaKeyStore provider
,D/ResourcesManager( 7819): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1281): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1281): Associated with C0.AA.48
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  902): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,I/wpa_supplicant( 1281): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  902): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  902): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,I/ActivityManager(  902): Killing 5817:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,I/wpa_supplicant( 1281): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/FOTA_Client( 7819): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/wpa_supplicant( 1281): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1281): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1281): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1281): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1281): Blacklist: Clear (temp) 
I/wpa_supplicant( 1281): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/FOTA_Client( 7819): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  902): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  902): Network connection established
,D/WifiNative-HAL(  902): callSECApiVoid - ID [50]
,E/WifiStateMachine(  902): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  902): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  902): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  902): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  902): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  902): Got NetworkAgent Messenger
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  902): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  902): updateNetworkInfo()
,D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902): NetworkAgent connected
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  902): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  902): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  902): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client( 7819): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine(  902): Start Dhcp Watchdog 2
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/Zygote  ( 7845): MountEmulatedStorage()
I/libpersona( 7845): KNOX_SDCARD checking this for 10018
E/Zygote  ( 7845): v2
,I/libpersona( 7845): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7845 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 6144:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
,I/SELinux ( 7845): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7845): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  902): failed to open /acct/uid_10112/pid_5817/cgroup.procs: No such file or directory
,E/SELinux ( 7845): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7845): TimaSignature is unavailable
,D/ActivityThread( 7845): Added TimaKeyStore provider
,D/ResourcesManager( 7845): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  902): do suspend false
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  902): InactiveState{ what=143375 }
D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
,D/SecContentProvider2(  902): mCursor = null
,W/libprocessgroup(  902): failed to open /acct/uid_10153/pid_6144/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7845): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7845): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453985644928
,I/KLMS-2.4.503: ( 7845): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7845): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7845): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  902): Killing 6964:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7860): MountEmulatedStorage()
E/Zygote  ( 7860): v2
I/libpersona( 7860): KNOX_SDCARD checking this for 10036
I/libpersona( 7860): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7860 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7860): TimaSignature is unavailable
,D/ActivityThread( 7860): Added TimaKeyStore provider
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7860): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5257): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,W/libprocessgroup(  902): failed to open /acct/uid_10070/pid_6964/cgroup.procs: No such file or directory
,I/SA      ( 7298): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7298): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7298): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7298): [SLFUCHKMGR] constructor called
,I/SA      ( 7298): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7298): [OR] == isSIMCardReady false ==
,I/SA      ( 7298): [SCU] == networkStateCheck == false
I/SA      ( 7298): [OR] onReceive END
,E/SPPClientService( 5257): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7879): MountEmulatedStorage()
E/Zygote  ( 7879): v2
I/libpersona( 7879): KNOX_SDCARD checking this for 10070
I/libpersona( 7879): KNOX_SDCARD not a persona
,E/dhcpcd  ( 7878): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ActivityManager(  902): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7879 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/dhcpcd  ( 7878): version 5.5.6 starting
,E/dhcpcd  ( 7878): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,V/AlarmManager(  902): waitForAlarm result :4
,I/SELinux ( 7879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  902): Killing 6937:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
E/SELinux ( 7879): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7878): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7878): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7878): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7878): bssid match
,I/dhcpcd  ( 7878): wlan0: rebinding lease of 192.168.1.136
,D/TimaKeyStoreProvider( 7879): TimaSignature is unavailable
,D/ActivityThread( 7879): Added TimaKeyStore provider
,D/ResourcesManager( 7879): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7879): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7879): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7879): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7879): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7879): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7879): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7879): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7879): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7879): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  902): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  902): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  902): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  902): selectionArgs: false
D/SettingsProvider(  902): selectionArgs: 10070
D/SecContentProvider(  902): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  902): ret = -1
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  902): failed to open /acct/uid_10011/pid_6937/cgroup.procs: No such file or directory
,D/accuweather( 7879): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7879): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7879): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7879): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7879): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7879): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7879): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7879): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7879): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7879): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7902): MountEmulatedStorage()
E/Zygote  ( 7902): v2
I/libpersona( 7902): KNOX_SDCARD checking this for 1000
I/libpersona( 7902): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7902 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 7188:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/SELinux ( 7902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7902): TimaSignature is unavailable
,D/ActivityThread( 7902): Added TimaKeyStore provider
,D/ResourcesManager( 7902): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  902): failed to open /acct/uid_10014/pid_7188/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7902): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7902): premStatus:2
,I/KnoxUsageLogPro( 7902): isEulaShown : false
I/KnoxUsageLogPro( 7902): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7917): MountEmulatedStorage()
,E/Zygote  ( 7917): v2
I/libpersona( 7917): KNOX_SDCARD checking this for 10087
I/libpersona( 7917): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7917 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 7207:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7917): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7917): TimaSignature is unavailable
,D/ActivityThread( 7917): Added TimaKeyStore provider
,D/ResourcesManager( 7917): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  902): failed to open /acct/uid_10015/pid_7207/cgroup.procs: No such file or directory
,I/ActivityManager(  902): Killing 6631:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,D/Headlines( 5515): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5515): getCountryCode(): countryCode = PL
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5515): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5515): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5515): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5515): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5515): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5515): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5515): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7939): MountEmulatedStorage()
I/libpersona( 7939): KNOX_SDCARD checking this for 10127
E/Zygote  ( 7939): v2
I/libpersona( 7939): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7939 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  315): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 308us total 20.061ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.156ms
,I/SELinux ( 7939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7939): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 14.208ms
,D/TimaKeyStoreProvider( 7939): TimaSignature is unavailable
,D/ActivityThread( 7939): Added TimaKeyStore provider
,I/PowerManagerService(  902): [PWL] Off : 5s ago
I/PowerManagerService(  902): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  902): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=902, ws=null) (elapsedTime=2006)
I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=902, ws=WorkSource{10058}) (elapsedTime=512)
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  902): failed to open /acct/uid_10033/pid_6631/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7939): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7939): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7939): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7939): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7939): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,E/SMD     (  286): DCD ON
,I/LibraryLoader( 7939): Loading: webviewchromium
,I/LibraryLoader( 7939): Time to load native libraries: 5 ms (timestamps 9662-9667)
,I/LibraryLoader( 7939): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7939): Binding Chromium to main looper Looper (main, tid 1) {5d77de3}
,I/LibraryLoader( 7939): Expected native library version number "",actual native library version number ""
,I/chromium( 7939): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7939): Initializing chromium process, renderers=0
,W/art     ( 7939): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7939): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7939): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7939): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7939): Requires BLUETOOTH permission
,I/Adreno-EGL( 7939): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7939): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7939): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7939): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7939): Remote Branch: 
I/Adreno-EGL( 7939): Local Patches: 
I/Adreno-EGL( 7939): Reconstruct Branch: 
,I/NSApplication( 7939): Starting up...
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8006): MountEmulatedStorage()
I/libpersona( 8006): KNOX_SDCARD checking this for 10137
E/Zygote  ( 8006): v2
I/libpersona( 8006): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8006 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 4880:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 8006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8006): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8006): TimaSignature is unavailable
,D/ActivityThread( 8006): Added TimaKeyStore provider
,W/libprocessgroup(  902): failed to open /acct/uid_10034/pid_4880/cgroup.procs: No such file or directory
,D/ResourcesManager( 8006): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8006): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8006): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8006): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7878): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,D/QuickConnect( 8006): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8006): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8006): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8021): MountEmulatedStorage()
,E/Zygote  ( 8021): v2
I/libpersona( 8021): KNOX_SDCARD checking this for 10162
I/libpersona( 8021): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8021 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 7271:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,I/dhcpcd  ( 7878): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 8021): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8021): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8021): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8021): TimaSignature is unavailable
,D/ActivityThread( 8021): Added TimaKeyStore provider
,D/ResourcesManager( 8021): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8021): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  902): failed to open /acct/uid_10041/pid_7271/cgroup.procs: No such file or directory
W/ResourcesManager( 8021): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  902): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  902): do suspend true
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/Zygote  ( 8065): MountEmulatedStorage()
,E/Zygote  ( 8065): v2
I/libpersona( 8065): KNOX_SDCARD checking this for 10077
I/libpersona( 8065): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8065 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
D/WifiP2pService(  902): InactiveState{ what=143375 }
D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,E/WifiStateMachine(  902): WifiStateMachine DHCP successful
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,E/WifiStateMachine(  902): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  902): Not connected state, yet.
E/WifiStateMachine(  902): VerifyingLinkState enter
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,I/SELinux ( 8065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,I/SELinux ( 8065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
E/SELinux ( 8065): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
D/WifiStateMachine(  902): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  902): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  902): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL(  902): callSECApiInt - ID [210]
E/WifiStateMachine(  902): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  902): updateNetworkInfo()
,D/ConnectivityService(  902): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  902): Adding iface wlan0 to network 503
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  902): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
D/WifiWatchdogStateMachine.SingDnsChecker(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,E/WifiStateMachine(  902): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  902): Now, connected state.
E/WifiStateMachine(  902): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
,E/WifiStateMachine(  902): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  902): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/TimaKeyStoreProvider( 8065): TimaSignature is unavailable
,E/WifiStateMachine(  902): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  902): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  902): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
D/ActivityThread( 8065): Added TimaKeyStore provider
,I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  902): mBoosterFLAG : 0
I/WifiTrafficPoller(  902): current booster mode : FullMode
,E/ConnectivityService(  902): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  902): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  902): updateSourceRoutes : add src route for:192.168.1.136
,D/WifiNative-HAL(  902): callSECApiVoid - ID [212]
,V/        (  280): QcRouteController
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  902): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine(  902): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,V/        (  280): QcRouteController
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,I/ActivityManager(  902): Killing 5630:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8021): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ResourcesManager( 8065): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/        (  280): QcRouteController
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7679): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7679): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7679): StateMachine : Current State = 1
,D/SecurityLogAgent( 7679): StateMachine : Changed Current State = 1
,I/ActivityManager(  902): Killing 5693:com.android.mms/u0a49 (adj 15): bgCount ##41
,V/        (  280): QcRouteController
,D/BadgeProvider( 8065): onCreate
,D/BadgeProvider( 8065): DatabaseHelper
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,D/CountryDetector(  902): No listener is left
,D/ConnectivityService(  902): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  902): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  902): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  902): updateNetworkInfo()
D/ConnectivityService(  902): calling update connectivity
E/ConnectivityService(  902): updateNetworkInfo()
D/ConnectivityService(  902): ignoring duplicate network state non-change
D/ConnectivityService(  902): ignoring duplicate network state non-change
D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Validated
,I/art     (  902): Explicit concurrent mark sweep GC freed 64597(3MB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 35MB/51MB, paused 1.478ms total 116.081ms
,D/ConnectivityService(  902): currentScore = 0, newScore = 60
D/ConnectivityService(  902):    accepting network in place of null
D/ConnectivityService(  902): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/TelephonyNetworkFactory( 1500): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  902): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  902): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/Zygote  ( 8098): MountEmulatedStorage()
E/Zygote  ( 8098): v2
I/libpersona( 8098): KNOX_SDCARD checking this for 10177
I/libpersona( 8098): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8098 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity(  902): Not allowed due to - mEnabled false
,D/ConnectivityService(  902): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  902): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  902): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService(  902): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  902): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,V/NetworkStats(  902): updateIfacesLocked()
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
V/NetworkStats(  902): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  902): UpdateStatsForKnox
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  902): performPollLocked() took 4ms
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/BadgeProvider( 8065): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/SELinux ( 8098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524290
I/SELinux ( 8098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524290
E/SELinux ( 8098): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
W/libprocessgroup(  902): failed to open /acct/uid_10047/pid_5630/cgroup.procs: No such file or directory
D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524290
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
W/libprocessgroup(  902): failed to open /acct/uid_10049/pid_5693/cgroup.procs: No such file or directory
,D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
V/NetworkStats(  902): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/BadgeProvider( 8065): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8065): sendNotify, [notify] : null
D/BadgeProvider( 8065): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8065): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8065): update, [UpdateCount] : 1
,D/Launcher.Model( 1536): reloadBadges entered.
,D/TimaKeyStoreProvider( 8098): TimaSignature is unavailable
,D/ActivityThread( 8098): Added TimaKeyStore provider
,W/ActivityManager(  902): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 8098): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  902): Killing 7327:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7661): notifyNetworkActivated
,W/ContextImpl( 7661): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  902): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  902): failed to open /acct/uid_10050/pid_7327/cgroup.procs: No such file or directory
,D/hcjo    ( 7661): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7661): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7661): exit::IDLE
D/InitializeManagerStateMachine( 7661): entry::NETWORK_CHECK
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7661): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7661): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7661): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7661): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7661): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7661): entry::SUCCESS
D/hcjo    ( 7661): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1302): Starting #8
,D/hcjo    ( 7661): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7661): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/Hs20UtilService( 1302): Message received 5007
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7661): exit::SUCCESS
D/InitializeManagerStateMachine( 7661): entry::IDLE
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/KeyguardViewMediator( 1182): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/KeyguardViewMediator( 1182): doKeyguard: not showing because lockscreen is off
,I/Hs20UtilService( 1302): Starting #9
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1302): Starting #10
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1302): Starting #11
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  902): callSECApi what=220
D/WifiStateMachine(  902): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/PowerManagerService(  902): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=902
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ProcessCpuTracker(  902): Skipping unknown process pid 7951
,W/ProcessCpuTracker(  902): Skipping unknown process pid 7954
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  902): MasterInitialState.processMessage what=3
,D/SmartBondingService(  902): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  902): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  902): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2120): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/CLocInfoService(  902): CLocinfo wifi true 
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2207): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2207): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3699): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3699): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5319): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7233): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7233): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7233): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7233): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
,I/DIAGMON_AGENT( 7802): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7802): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7819): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7819): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7819): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7845): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7845): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453985647517
,I/KLMS-2.4.503: ( 7845): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7845): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7845): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7845): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7845): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7860): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5257): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7298): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7298): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7298): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7298): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7298): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7298): [SCU] == networkStateCheck == true
,I/SA      ( 7298): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7298): isChinaCountryCode : false
I/SA      ( 7298): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7298): [OR] == networkStateCheck true ==
,I/SA      ( 7298): [OR] GetMyCountryZoneTask
,I/SA      ( 7298): [OR] onReceive END
,I/SA      ( 7298): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7298): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7298): [SSP] query invoked
,D/accuweather( 7879): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7879): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 7298): [TPMU] GetMccFromDB : null
I/SA      ( 7298): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7298): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7902): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7902): premStatus:2
,I/KnoxUsageLogPro( 7902): isEulaShown : false
I/KnoxUsageLogPro( 7902): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 7298): fail readDirectory() errno=2
,D/Headlines( 5515): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5515): getCountryCode(): countryCode = PL
,D/Headlines( 5515): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5515): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5515): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5515): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5515): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5515): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5515): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8006): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8006): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 8006): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7679): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7679): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7679): StateMachine : Current State = 1
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7679): StateMachine : Changed Current State = 1
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7661): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7661): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7661): exit::IDLE
D/InitializeManagerStateMachine( 7661): entry::NETWORK_CHECK
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7661): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7661): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7661): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7661): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7661): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7661): entry::SUCCESS
D/hcjo    ( 7661): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7661): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7661): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7661): exit::SUCCESS
D/InitializeManagerStateMachine( 7661): entry::IDLE
,D/ConnectivityService(  902): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  902): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  902): identical MTU - not setting
D/ConnectivityService(  902): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  902): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  280): QcRouteController
D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,V/        (  280): QcRouteController
,W/NetworkManagementService(  902): route cmd failed: 
W/NetworkManagementService(  902): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  902): '
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  902): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  902): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  902): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  902): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524295
D/ConnectivityService(  902): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  902): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524295
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524295
D/ConnectivityService(  902): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524295
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7398): 
,I/SA      ( 7298): [RC New] Execute method=[GET] start
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/SA      ( 7298): [RC New] Security=[true]
,I/System.out( 7298): Thread-1136(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7298): Thread-1136(ApacheHTTPLog):isShipBuild true
,I/System.out( 7298): Thread-1136(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7398): 
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7398): 
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7398): 
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7398): 
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
,I/jxcore-log( 7398): 
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
,I/jxcore-log( 7398): 
,I/jxcore-log( 7398): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,I/jxcore-log( 7398): 
,D/FactoryTest( 6751): Not factory mode
,D/FactoryTest( 6751): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6751): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6751): still no open session command from host, so toast
,W/ContextImpl( 6751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6751): Timeline: Activity_launch_request id:com.android.settings time:112530
,E/PersonaManagerService(  902): inState():  stateMachine is null !!
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  902): mDVFSHelper.acquire()
,V/ActivityManager(  902): Display changed displayId=0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/MTPRx   ( 6751): started activity for popup
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SQLiteSecureOpenHelper( 3511): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3511): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6751): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6751): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6751): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6751): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6751): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6751): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6751): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SMD     (  286): DCD ON
,E/SettingsReceiverActivity( 6751): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  902): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@27581197 attribute=null, token = android.os.BinderProxy@7847388
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6751): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6751): dev.kiessupport is : TRUE
,D/Activity( 6751): performCreate Call secproduct feature valuefalse
,D/Activity( 6751): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ActivityManager(  902): post active user change for 0
D/KnoxTimeoutHandler(  902): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  902): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/Timeline( 7398): Timeline: Activity_idle id: android.os.BinderProxy@11641e4 time:112789
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7878): wlan0: sending IPv6 Router Solicitation
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PackageManager(  902): [MSG] MCS_UNBIND
,I/ActivityManager(  902): Killing 7346:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,I/SA      ( 7298): [RC New] [v2liruge] api execute + 1336
,I/SA      ( 7298): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7298): AsyncTask #1 calls detatch()
,I/SA      ( 7298): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7298): [OCP] update openData : PL
,I/SA      ( 7298): [TPMU] getNetworkMcc : 
,I/SA      ( 7298): [SCU] saveMccToPreferece Start
I/SA      ( 7298): [SCU] RegionMCC : 260
I/SA      ( 7298): [SSP] query invoked
,I/SA      ( 7298): [TPMU] GetMccFromDB : null
I/SA      ( 7298): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7298): [SCU] saveMccToPreferece End
,I/SA      ( 7298): [RC New] executeRequest [v2liruge] end. 1392
I/SA      ( 7298): [RC New] Execute end
,I/SA      ( 7298): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7298): [OR] GetMyCountryZoneTask Success
,W/libprocessgroup(  902): failed to open /acct/uid_10057/pid_7346/cgroup.procs: No such file or directory
,V/AlarmManager(  902): waitForAlarm result :8
,I/WifiStateMachine(  902): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  902): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  902): SIOP:: AP = 410, PST = 379, CUR = 450
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/PowerManagerService(  902): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 902) eventTime = 114344
,D/PowerManagerService(  902): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=902 (0x0)
D/PowerManagerService(  902): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=902, ws=WorkSource{10058}) (elapsedTime=3498)
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/GAV4    ( 7939): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ActivityManager(  902): mDVFSHelper.release()
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7233): mConnectivityHandler : connected
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7233): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7233): [GetString-S]
,I/ReactiveServiceManager( 7233): Supported : 1
D/QSEECOMAPI: (  902): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  902): App is not loaded in QSEE
,D/QSEECOMAPI: (  902): Loaded image: APP id = 3
,D/QSEECOMAPI: (  902): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  902): QSEECom_shutdown_app, app_id = 3
E/terrier (  902): handleString: Failed to handle string(-4)
E/terrier (  902): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7233): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7233): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7233): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7233): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7233): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7233): [ensureRegistration] - No Samsung account
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,I/dhcpcd  ( 7878): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 7398): Test app app.js loaded
I/jxcore-log( 7398): 
,I/chromium( 7398): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7398): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7398): BLE advertisement is supported
I/jxcore-log( 7398): 
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 15s ago
,V/AlarmManager(  902): waitForAlarm result :4
,D/PreloadUpdateManagerStateMachine( 7661): execute::IDLE:EXECUTE
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/PreloadUpdateManagerStateMachine( 7661): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7661): entry::CHECK_TIMEOUT_FOR_UPDATE
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/hcjo    ( 7661): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/hcjo    ( 7661): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7661): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 7661): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7661): entry::IDLE
,I/dhcpcd  ( 7878): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7878): wlan0: no IPv6 Routers available
,D/Finsky  ( 6575): [1065] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6575): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PreloadUpdateManagerStateMachine( 7661): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7661): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7661): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7661): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7661): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7661): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7661): entry::IDLE
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  902): SIOP:: AP = 350, PST = 369, CUR = 450
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  902): !@Sync 4
,V/AlarmManager(  902): waitForAlarm result :4
,D/SSRM:m  (  902): SIOP:: AP = 320, PST = 360, CUR = 450
,I/PowerManagerService(  902): [PWL] Off : 30s ago
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 310, PST = 351, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 50s ago
,D/SSRM:m  (  902): SIOP:: AP = 300, PST = 341, CUR = 450
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,E/Watchdog(  902): !@Sync 5
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 336, CUR = 450
,E/SMD     (  286): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,V/GLSActivity( 2231): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2231): Scheduling Phenotype for one-off execution 7678 seconds from now (1453985703663)
,D/GetConfigurationSnapshotOperation( 2231): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2231): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2231): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  902): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2231): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2231): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2231): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 2231, getuid(): 10011
,I/qtaguid ( 2231): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 2231, getuid(): 10011
,D/LocationManagerService(  902): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2231): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 2231, getuid(): 10011
,D/LocationManagerService(  902): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2231): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 2231, getuid(): 10011
,D/LocationManagerService(  902): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2231): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 2231, getuid(): 10011,
,D/LocationManagerService(  902): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2231): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 2231, getuid(): 10011
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON,
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 332, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 75s ago
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 328, CUR = 450
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  902): !@Sync 6
,I/ClearcutLoggerApiImpl( 2231): disconnect managed GoogleApiClient
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 323, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 314, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 105s ago
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 280, PST = 301, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,E/Watchdog(  902): !@Sync 7
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  902): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  902): SIOP:: AP = 270, PST = 293, CUR = 450
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  902): SIOP:: AP = 270, PST = 288, CUR = 450
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 7398): --= Surplus to requirements =--
I/jxcore-log( 7398): 
,I/jxcore-log( 7398): ****TEST TOOK:  ms ****
I/jxcore-log( 7398): 
I/jxcore-log( 7398): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7398): 
,D/AndroidRuntime( 8247): 
D/AndroidRuntime( 8247): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8247): CheckJNI is OFF
,D/AndroidRuntime( 8247): setted country_code = Poland
,D/AndroidRuntime( 8247): setted countryiso_code = PL
D/AndroidRuntime( 8247): setted sales_code = XEO
,D/AndroidRuntime( 8247): readGMSProperty: start
D/AndroidRuntime( 8247): readGMSProperty: already setted!!
D/AndroidRuntime( 8247): readGMSProperty: end
D/AndroidRuntime( 8247): addProductProperty: start
,E/AffinityControl( 8247): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8247): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  902): START PACKAGE DELETE: observer{157465934}
D/PackageManager(  902): pkg{<packageName>}
D/PackageManager(  902): user{0}
D/PackageManager(  902): caller{2000}
D/PackageManager(  902): flags{3}
,D/PersonaManagerService(  902): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  902): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  902): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  902): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  902): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  902): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  902): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService(  902): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  902): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  902): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  902): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  902): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  902): Killing 7398:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  902):   Force finishing activity ActivityRecord{16b64fae u0 com.test.thalitest/.MainActivity t9}
,D/FocusedStackFrame(  902): Set to : 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/WifiService(  902): Client connection lost with reason: 4
,I/ActivityManager(  902): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1588): Explicit concurrent mark sweep GC freed 3475(380KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 438us total 28.950ms
,I/art     ( 2490): Explicit concurrent mark sweep GC freed 5823(291KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 21MB/36MB, paused 590us total 33.092ms
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 6482): Explicit concurrent mark sweep GC freed 32235(1747KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 624us total 38.380ms
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 1536): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1536): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1536): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1536): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SamsungIME( 1883): mOCRHelper is null
,D/ResourcesManager( 1536): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1536): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1536): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 2231): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7845): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/InputReader(  902): Reconfiguring input devices.  changes=0x00000010
,I/KLMS-2.4.503: ( 7845): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453985774781
,I/KLMS-2.4.503: ( 7845): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7845): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  902): Explicit concurrent mark sweep GC freed 63457(4MB) AllocSpace objects, 45(720KB) LOS objects, 30% free, 35MB/51MB, paused 1.604ms total 144.115ms
,I/art     (  902): WaitForGcToComplete blocked for 76.378ms for cause Explicit
D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  ( 8274): MountEmulatedStorage()
E/Zygote  ( 8274): v2
I/libpersona( 8274): KNOX_SDCARD checking this for 10103
I/libpersona( 8274): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8274 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/SELinux ( 8274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/RegisteredServicesCache( 1494): empty dynamic service
,I/SELinux ( 8274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SMD     (  286): DCD ON
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/EnterpriseDeviceManagerService(  902): Package has changed for user 0
D/EnterpriseDeviceManagerService(  902): Admin package name: com.google.android.gms
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/TimaKeyStoreProvider( 8274): TimaSignature is unavailable
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ActivityThread( 8274): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 8274): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SurfaceWidgetView( 1536): destroyHardwareResources():835348322
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  902): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/Launcher( 1536): onRestart, Launcher: 718754175
,D/Launcher( 1536): onStart, Launcher: 718754175
D/Launcher.HomeView( 1536): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2120): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2120): [237392/6] SurfaceWidget drawing first frame
,D/elm:14451( 8274): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8274): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8274): MDMBridge.setEnterpriseBridge()
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/elm:14451( 8274): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/elm:14451( 8274): ElmAgentService : onCreate()
,D/elm:14451( 8274): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8274): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8274): MDMBridge.getInstance()
D/elm:14451( 8274): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14451( 8274): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 8293): MountEmulatedStorage()
E/Zygote  ( 8293): v2
I/libpersona( 8293): KNOX_SDCARD checking this for 10016
I/libpersona( 8293): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8293 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,D/RCPManagerService(  902): PackageReceiver onReceive()
,I/HarmonyEASService(  902): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  902): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  902): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/SELinux ( 8293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/elm:14451( 8274): ElmAgentService : onDestroy().
,I/ActivityManager(  902): Killing 6257:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,W/InputMethodManagerService(  902): Got RemoteException sending setActive(false) notification to pid 7398 uid 10191
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/JobSchedulerService(  902): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  902): uID is 10191
V/EnterpriseBillingPolicy(  902): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  902): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  902): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  902): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  902): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  902): removeObsoleteFile: deleting file=9_task.xml
,D/TimaKeyStoreProvider( 8293): TimaSignature is unavailable
,D/ActivityThread( 8293): Added TimaKeyStore provider
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/art     (  902): Explicit concurrent mark sweep GC freed 11730(573KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 35MB/51MB, paused 3.287ms total 263.913ms
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8293): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 8293): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8293): onReceive() : package name is not s health. Return !!!
I/Timeline(  902): Timeline: Activity_windows_visible id: ActivityRecord{d573c43 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:238898
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/PCWCLIENTTRACE_PushUtil( 7233): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7233): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7233): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7233): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6257/cgroup.procs: No such file or directory
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/Zygote  ( 8313): MountEmulatedStorage()
I/libpersona( 8313): KNOX_SDCARD checking this for 10033
E/Zygote  ( 8313): v2
I/libpersona( 8313): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8313 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 7152:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/SELinux ( 8313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager(  902): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/TimaKeyStoreProvider( 8313): TimaSignature is unavailable
,D/ActivityThread( 8313): Added TimaKeyStore provider
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/PackageManager(  902): delete codoeFile: 
,D/PackageManager(  902): result of delete: 1{157465934}
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/FeatureConfig( 8313): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/libprocessgroup(  902): failed to open /acct/uid_10097/pid_7152/cgroup.procs: No such file or directory
,D/AndroidRuntime( 8247): Shutting down VM
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  902): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  902): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8313): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8313): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 8313): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8313): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8313): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8313): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8313): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8330): MountEmulatedStorage()
E/Zygote  ( 8330): v2
I/libpersona( 8330): KNOX_SDCARD checking this for 10034
I/libpersona( 8330): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8330 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 7411:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,I/SELinux ( 8330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8330): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  902): failed to open /acct/uid_10032/pid_7411/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8330): TimaSignature is unavailable
,D/ActivityThread( 8330): Added TimaKeyStore provider
,D/ResourcesManager( 8330): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,F/libc    ( 8330): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74c3fde8 in tid 8347 (AsyncTask #1)
,E/audit_log( 2156): File locking failed. error= Bad file number
,F/libc    ( 8330): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2156): File locking failed. error= Bad file number
,I/ActivityManager(  902): Process com.sec.android.app.shealth (pid 8330)(adj 0) has died(220,552)
,I/EventHub(  902): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 5257): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74c3fde8 in tid 5257 (om.sec.spp.push)
,F/libc    ( 5257): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2156): File locking failed. error= Bad file number
,I/Zygote  (  315): Process 8330 exited due to signal (7)
,I/ActivityManager(  902): Process com.sec.spp.push (pid 5257)(adj 0) has died(225,552)
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8350): MountEmulatedStorage()
,E/Zygote  ( 8350): v2
I/libpersona( 8350): KNOX_SDCARD checking this for 10037
I/libpersona( 8350): KNOX_SDCARD not a persona
,I/Zygote  (  315): Process 5257 exited due to signal (7)
,I/EventHub(  902): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  902): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8350 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8350): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
I/EventHub(  902): Removing device '/dev/input/event6' due to inotify event
,E/SELinux ( 8350): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8350): TimaSignature is unavailable
,D/ActivityThread( 8350): Added TimaKeyStore provider
,I/EventHub(  902): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager( 8350): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/        ( 8350): Zip: read 65557 failed: I/O error
,W/zipro   ( 8350): Error opening archive /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk: I/O Error
D/asset   ( 8350): failed to open Zip archive '/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk'
,W/ContextImpl( 8350): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8350): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8350): Zip: read 65557 failed: I/O error
,W/        ( 8350): Zip: read 65557 failed: I/O error
,D/ResourcesManager( 8350): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,F/libc    ( 8350): Fatal signal 7 (SIGBUS), code 2, fault addr 0xaf8b193d in tid 8350 (moteNotiProcess)
,F/libc    ( 8350): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2156): File locking failed. error= Bad file number
,I/ActivityManager(  902): Process com.sec.spp.push:RemoteNotiProcess (pid 8350)(adj 0) has died(225,552)
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,I/EventHub(  902): Removing device '/dev/input/event8' due to inotify event
,E/Zygote  ( 8365): MountEmulatedStorage()
,E/Zygote  ( 8365): v2
I/libpersona( 8365): KNOX_SDCARD checking this for 10041
I/libpersona( 8365): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8365 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/Zygote  (  315): Process 8350 exited due to signal (7)
,I/SELinux ( 8365): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
I/EventHub(  902): Removing device '/dev/input/event9' due to inotify event
,E/SELinux ( 8365): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8365): TimaSignature is unavailable
,D/ActivityThread( 8365): Added TimaKeyStore provider
,D/ResourcesManager( 8365): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8365): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8365): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 8365): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
,E/ActivityThread( 8365): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8365): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73706aae in tid 8365 (sdk.samsunglink)
,F/libc    ( 8365): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2156): File locking failed. error= Bad file number
,I/EventHub(  902): Removing device '/dev/input/event10' due to inotify event
,I/ActivityManager(  902): Process com.samsung.android.sdk.samsunglink (pid 8365)(adj 0) has died(225,552)
,I/SA      ( 7298): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7298): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10191 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1845): Fatal signal 7 (SIGBUS), code 2, fault addr 0x776f8e10 in tid 1922 (ContactsProvide)
,F/libc    ( 1845): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2156): File locking failed. error= Bad file number
,I/ActivityManager(  902): Process android.process.acore (pid 1845)(adj 0) has died(231,553)
,F/libc    (  902): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa03c875c in tid 1545 (Binder_7)
,F/libc    (  902): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2156): File locking failed. error= Bad file number
,I/Zygote  (  315): Process 8365 exited due to signal (7)
,I/Zygote  (  315): Process 1845 exited due to signal (7)
,W/Sensors ( 7371): sensorservice died [0xaf097f80]
,W/AudioFlinger(  294): power manager service died !!!
,W/AudioFlinger(  294): power manager service died !!!
,D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb6a62000
,I/ServiceManager(  255): service 'wifip2p' died
I/ServiceManager(  255): service 'uimode' died
I/ServiceManager(  255): service 'jobscheduler' died
I/ServiceManager(  255): service 'msapwifi' died
I/ServiceManager(  255): service 'wifiscanner' died
I/ServiceManager(  255): service 'rttmanager' died
I/ServiceManager(  255): service 'connectivity' died
I/ServiceManager(  255): service 'sb_service' died
I/ServiceManager(  255): service 'clinfo' died
I/ServiceManager(  255): service 'servicediscovery' died
I/ServiceManager(  255): service 'updatelock' died
I/ServiceManager(  255): service 'wifi' died
I/ServiceManager(  255): service 'sec_analytics' died
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
I/ServiceManager(  255): service 'tactileassist' died
I/ServiceManager(  255): service 'bluetooth_manager' died
I/ServiceManager(  255): service 'bluetooth_secure_mode_manager' died
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
I/ServiceManager(  255): service 'notification' died
I/ServiceManager(  255): service 'devicestoragemonitor' died
I/ServiceManager(  255): service 'location' died
I/ServiceManager(  255): service 'country_detector' died
I/ServiceManager(  255): service 'sec_location' died
I/ServiceManager(  255): service 'search' died
I/ServiceManager(  255): service 'dropbox' died
I/ServiceManager(  255): service 'wallpaper' died
I/ServiceManager(  255): service 'audio' died
I/ServiceManager(  255): service 'DockObserver' died
I/ServiceManager(  255): service 'usb' died
I/ServiceManager(  255): service 'serial' died
I/ServiceManager(  255): service 'backup' died
I/ServiceManager(  255): service 'appwidget' died
I/ServiceManager(  255): service 'network_score' died
I/ServiceManager(  255): service 'netstats' died
I/ServiceManager(  255): service 'netpolicy' died
I/ServiceManager(  255): service 'batterystats' died
I/ServiceManager(  255): service 'appops' died
I/ServiceManager(  255): service 'power' died
I/ServiceManager(  255): service 'display' died
I/ServiceManager(  255),: service 'context_aware' died
I/ServiceManager(  255): service 'scontext' died
I/ServiceManager(  255): service 'barbeam' died
I/ServiceManager(  255): service 'multiwindow_facade' died
I/ServiceManager(  255): service 'window' died
I/ServiceManager(  255): service 'input' died
I/ServiceManager(  255): service 'persona' died
I/ServiceManager(  255): service 'account' died
I/ServiceManager(  255): service 'content' died
I/ServiceManager(  255): service 'DirEncryptService' died
I/ServiceManager(  255): service 'ReactiveService' died
I/ServiceManager(  255): service 'sedenial' died
I/ServiceManager(  255): service 'vibrator' died
I/ServiceManager(  255): service 'tw_toolbox' died
I/ServiceManager(  255): service 'tima' died
I/ServiceManager(  255): service 'cepproxyks' died
I/ServiceManager(  255): service 'CustomFrequencyManagerService' died
I/ServiceManager(  255): service 'samsung.smartfaceservice' died
I/ServiceManager(  255): service 'consumer_ir' died
I/ServiceManager(  255): service 'alarm' died
I/ServiceManager(  255): service 'enterprise_license_policy' died
I/ServiceManager(  255): service 'application_policy' died
I/ServiceManager(  255): service 'wifi_policy' died
I/ServiceManager(  255): service 'phone_restriction_policy' died
I/ServiceManager(  255): service 'remoteinjection' died
I/ServiceManager(  255): service 'SEAMService' died
I/ServiceManager(  255): service 'battery' died
I/ServiceManager(  255): service 'user' died
I/ServiceManager(  255): service 'procstats' died
I/ServiceManager(  255): service 'meminfo' died
I/ServiceManager(  255): service 'package' died
I/ServiceManager(  255): service 'activity' died
I/ServiceManager(  255): service 'dbinfo' died
I/ServiceManager(  255): service 'hardware' died
I/ServiceManager(  255): service 'webviewupdate' died
I/ServiceManager(  255): service 'telephony.registry' died
I/ServiceManager(  255): service 'edmnativehelper' died
I/ServiceManager(  255): service 'permission' died
I/ServiceManager(  255): service 'entropy' died
I/ServiceManager(  255): service 'cpuinfo' died
I/ServiceManager(  255): service 'gfxinfo' died
I/ServiceManager(  255): service 'usagestats' died
I/ServiceManager(  255): service 'scheduling_policy' died
I/ServiceManager(  255): service 'persona_policy' died
I/ServiceManager(  255): service 'sensorservice' died
I/ServiceManager(  255): service 'mdm.remotedesktop' died
I/SurfaceFlinger(  257): id=2 Removed FocusedStackFrame (4/8)
I/SurfaceFlinger(  257): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  257): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  257): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  257): id=6 Removed DimLayer (2/4)
I/SurfaceFlinger(  257): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  257): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  257): id=4 Removed DimLayer (-2/4)
I/SurfaceFlinger(  257): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (1/3)
I/SurfaceFlinger(  257): id=7 Removed com.android.systemui.ImageWallpaper (0/2)
I/SurfaceFlinger(  257): id=7 Removed com.android.systemui.ImageWallpaper (-2/2)
I/SurfaceFlinger(  257): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/2)
I/SurfaceFlinger(  257): id=9 Removed StatusBar (0/1)
I/SurfaceFlinger(  257): id=9 Removed StatusBar (-2/1)
I/SurfaceFlinger(  257): id=15 Removed ColorFade (0/0)
I/SurfaceFlinger(  257): id=15 Removed ColorFade (-2/0)
W/Sensors ( 1500): sensorservice died [0xaf053380]
D/qdhwcomposer(  257): hwc_blank: Unblanking display: 0
W/Sensors ( 1536): sensorservice died [0xaf0533c0]
E/WifiManager( 1500): Channel connection lost
I/SurfaceFlinger(  257): restart the boot-animation @ binderDied
F/libc    ( 2207): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758f3148 in tid 2230 (Binder_1)
E/audit_log( 2156): File locking failed. error= Bad file number
F/libc    ( 2207): Unable to open connection to debuggerd: Connection refused
E/WifiManager( 1588): Channel connection lost
W/Sensors ( 1302): sensorservice died [0x9d3212c0]
E/WifiManager( 1302): Channel connection lost
W/Sensors ( 1182): sensorservice died [0xaf0d00c0]
E/WifiManager( 1182): Channel connection lost
I/SurfaceFlinger(  257): id=5 Removed DimLayer (-2/0)
I/SurfaceFlinger(  257): id=6 Removed DimLayer (-2/0)
E/WifiManager( 2231): Channel connection lost
W/Sensors ( 2231): sensorservice died [0xaf07b840]
E/WifiManager( 1621): Channel connection lost
W/Sensors ( 1482): sensorservice died [0xaf0bcbc0]
W/Sensors ( 2258): sensorservice died [0xaf097c00]
,I/Zygote  (  315): Process 2207 exited due to signal (7)
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  257): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  257): hwc_blank: Done unblanking display: 0
,E/qdhwcomposer(  257): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  257): eventControl(0, 1) failed Operation not permitted
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0

```
