#### Test 5038801932cd575_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/GroupCast_FileTools( 5644): [getDirectoryForImageResized : 295] cleaning!!
W/System.err( 5644): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 5644): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 5644): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5644): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5644): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5644): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5644): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5644): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5644): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5644): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5644): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5644): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5644): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5644): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5644): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
--------- beginning of system
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5666): MountEmulatedStorage()
E/Zygote  ( 5666): v2
I/libpersona( 5666): KNOX_SDCARD checking this for 1000
I/libpersona( 5666): KNOX_SDCARD not a persona
I/ActivityManager(  852): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5666 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  852): Killing 4555:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
I/SELinux ( 5666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/PeopleDatabaseHelper( 1895): cleanUpNonGplusAccounts done.
D/TimaKeyStoreProvider( 5666): TimaSignature is unavailable
D/ActivityThread( 5666): Added TimaKeyStore provider
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
W/libprocessgroup(  852): failed to open /acct/uid_10012/pid_4555/cgroup.procs: No such file or directory
D/ResourcesManager( 5666): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
I/PCWCLIENTTRACE_LOG( 5666): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5666): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5666): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 5666): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5666): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5666): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5666): [onReceive] - android.intent.action.PACKAGE_ADDED
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5683): MountEmulatedStorage()
I/libpersona( 5683): KNOX_SDCARD checking this for 10034
E/Zygote  ( 5683): v2
I/libpersona( 5683): KNOX_SDCARD not a persona
I/ActivityManager(  852): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5683 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  852): Killing 4348:com.android.vending/u0a30 (adj 15): bgCount ##41
I/SELinux ( 5683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  852): failed to open /acct/uid_10030/pid_4348/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5683): TimaSignature is unavailable
D/ActivityThread( 5683): Added TimaKeyStore provider
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/FeatureConfig( 5683): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 5683): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/art     (  852): Explicit concurrent mark sweep GC freed 22241(1535KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.207ms total 84.695ms
W/ResourcesManager( 5683): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 5683): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 5683): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 5683): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 5683): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 5683): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 5683): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 5683): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
W/ResourcesManager( 5683): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager( 5683): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5683): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 5683): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/AndroidRuntime( 5704): 
D/AndroidRuntime( 5704): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5704): CheckJNI is OFF
D/AndroidRuntime( 5704): setted country_code = Germany
D/AndroidRuntime( 5704): setted countryiso_code = DE
D/AndroidRuntime( 5704): setted sales_code = DBT
D/AndroidRuntime( 5704): readGMSProperty: start
D/AndroidRuntime( 5704): readGMSProperty: already setted!!
D/AndroidRuntime( 5704): readGMSProperty: end
D/AndroidRuntime( 5704): addProductProperty: start
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
I/SA      ( 5031): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5031): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 5031): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10374 extra.user_handle.:0 ]
I/ActivityManager(  852): Killing 4611:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
D/Mms/FreeMessageReceiver( 5222): onReceive, action : android.intent.action.PACKAGE_ADDED
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 5704): AffinityControl: registerfunction enter
I/libpersona( 5726): KNOX_SDCARD checking this for 10051
E/Zygote  ( 5726): MountEmulatedStorage()
I/libpersona( 5726): KNOX_SDCARD not a persona
E/Zygote  ( 5726): v2
W/libprocessgroup(  852): failed to open /acct/uid_10143/pid_4611/cgroup.procs: No such file or directory
I/ActivityManager(  852): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5726 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/Mms/FreeMessageReceiverService( 5222): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5222): onHandleIntent: ACTION_PACKAGE_ADDED
D/AndroidRuntime( 5704): Calling main entry com.android.commands.am.Am
I/SELinux ( 5726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/PersonaManagerService(  852): inState():  stateMachine is null !!
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  852): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  852): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  852): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  852): mDVFSHelper.acquire()
D/FocusedStackFrame(  852): Set to : 0
D/TimaKeyStoreProvider( 5726): TimaSignature is unavailable
D/Launcher.HomeView( 1488): onPause
D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/ActivityThread( 5726): Added TimaKeyStore provider
D/AndroidRuntime( 5704): Shutting down VM
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 5750): MountEmulatedStorage()
E/Zygote  ( 5750): v2
I/libpersona( 5750): KNOX_SDCARD checking this for 10374
I/libpersona( 5750): KNOX_SDCARD not a persona
I/ActivityManager(  852): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5750 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
I/SELinux ( 5750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/SurfaceFlinger(  249): id=12 createSurf (1x1),1 flag=404, Starting com.example.hello
E/SELinux ( 5750): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/SMD     (  284): DCD ON
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5726): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/TimaKeyStoreProvider( 5750): TimaSignature is unavailable
W/ResourcesManager( 5726): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5726): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ActivityThread( 5750): Added TimaKeyStore provider
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/Launcher.HomeView( 1488): onStop
V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  852): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/MicrophoneInputStream( 1548): mic_close gfk@204491d9
D/ConnectivityService(  852): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2230): [237392/6] Surface widget pause on instance = 1
V/AudioPolicyManager(  289): stopInput() input 26
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2230): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/audio_hw_primary(  289): in_standby: enter
D/ResourcesManager( 5750): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/HotwordRecognitionRnr( 1548): Stopping hotword detection.
I/HotwordRecognitionRnr( 1548): Hotword detection finished
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/accuweather( 2230): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/StatusBarManagerService(  852): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/ActivityThread( 1488): Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1488): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1488): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 1488): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 1488): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1488): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 1488): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1488): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 1488): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 1488): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1488): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1488): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 1488): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/Launcher( 1488): onTrimMemory. Level: 20
D/accuweather( 2230): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2230): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/accuweather( 2230): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2230): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1488): destroyHardwareResources():53970086
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/audio_hw_primary(  289): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  289): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  289): disable_audio_route: reset mixer path: audio-record
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): disable_audio_route: exit
V/audio_hw_primary(  289): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: DEC2 Volume
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  289): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  289): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/audio_route(  289): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): stop_input_stream: exit: status(0)
V/audio_hw_primary(  289): in_standby: exit:  status(0)
V/AudioPolicyManager(  289): releaseInput() 26
V/AudioPolicyManager(  289): closeInput(26)
V/audio_hw_primary(  289): adev_close_input_stream
V/audio_hw_primary(  289): in_standby: enter
V/audio_hw_primary(  289): in_standby: exit:  status(0)
E/audio_hw_primary(  289): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  289): releaseInput() exit
E/Watchdog(  852): !@Sync 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SettingsProvider(  852): name = audio_safe_volume_state
I/ActivityManager(  852): Activity reported stop, but no longer stopping: ActivityRecord{3d7e693f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9}
D/SurfaceWidgetView( 1488): destroyHardwareResources():53970086
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/MyFiles ( 5726): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/installd(  296): system dir 0 : /system/app/
E/installd(  296): system dir 1 : /system/priv-app/
E/installd(  296): system dir 2 : /vendor/app/
E/installd(  296): system dir 3 : /oem/app/
V/BitmapFactory( 5536): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
I/TactileAssist(  852): enable value -1
I/TactileAssist(  852): internal enable value -1
I/TactileAssist(  852): intensity value -1
I/TactileAssist(  852): saveAppList value true
I/TactileAssist(  852): List of disabled apps :
I/TactileAssist(  852): de.zalando.mobile
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 5750): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 5750): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 5750): Loading: webviewchromium
E/Zygote  ( 5771): MountEmulatedStorage()
E/Zygote  ( 5771): v2
I/libpersona( 5771): KNOX_SDCARD checking this for 10058
I/libpersona( 5771): KNOX_SDCARD not a persona
I/LibraryLoader( 5750): Time to load native libraries: 3 ms (timestamps 3624-3627)
I/LibraryLoader( 5750): Expected native library version number "",actual native library version number ""
I/ActivityManager(  852): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5771 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
V/AlarmManager(  852): waitForAlarm result :4
I/SELinux ( 5771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5771): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/WebViewChromiumFactoryProvider( 5750): Binding Chromium to main looper Looper (main, tid 1) {3846781b}
I/LibraryLoader( 5750): Expected native library version number "",actual native library version number ""
I/chromium( 5750): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/BrowserStartupController( 5750): Initializing chromium process, renderers=0
W/art     ( 5750): Attempt to remove local handle scope entry from IRT, ignoring
D/PackageManager(  852): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/NotifUtils( 5536): Account: 61035162 vibrate: false
I/NotifUtils( 5536): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
W/chromium( 5750): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 5750): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5750): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5750): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/TimaKeyStoreProvider( 5771): TimaSignature is unavailable
D/BluetoothAdapter( 5750): 779849144: getState() :  mService = null. Returning STATE_OFF
D/ActivityThread( 5771): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Adreno-EGL( 5750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5750): Build Date: 03/03/15 Tue
I/Adreno-EGL( 5750): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 5750): Remote Branch: 
I/Adreno-EGL( 5750): Local Patches: 
I/Adreno-EGL( 5750): Reconstruct Branch: 
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 5771): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|1729800001|null|10114
W/ResourcesManager( 5771): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
I/ValidateNoPeople(  852): Executing: validation for: 0|com.google.android.gm|1729800001|null|10114
V/AudioPolicyManager(  289): getOutputsForDevice device 0002 -> 0002
I/AudioService(  852): getStreamVolume 5 index 110
D/LightsService(  852): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 852) 
D/LightsService(  852): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  852): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  852): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/ResourcesManager( 1169): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
D/Compatibility( 5771): onReceive() it will make start service
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
E/SQLiteLog( 1784): (284) automatic index on sqlite_sq_AF9AE150(STAT_DATA_ID)
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|-2100714965|null|10114
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 5750): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/Compatibility( 5771): onHandleIntent()
D/Compatibility( 5771): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10374, android.intent.extra.user_handle=0}]
W/chromium( 5750): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/Compatibility( 5771): found: 2
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
W/art     ( 5750): Attempt to remove local handle scope entry from IRT, ignoring
D/Compatibility( 5771): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5771): skipping ResolveInfo{f902aff com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
I/UpdateIcingCorporaServi( 1548): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
W/AwContents( 5750): onDetachedFromWindow called when already detached. Ignoring
D/Compatibility( 5771): considering ResolveInfo{db630cc com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5771): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5771): enabling receiver ResolveInfo{23391f15 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ContextImpl( 5570): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 5771): enabling receiver ResolveInfo{608d22a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5771): enabling receiver ResolveInfo{3846781b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5771): enabling receiver ResolveInfo{2e7b8db8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 5810): MountEmulatedStorage()
I/libpersona( 5810): KNOX_SDCARD checking this for 10086
E/Zygote  ( 5810): v2
I/libpersona( 5810): KNOX_SDCARD not a persona
I/ActivityManager(  852): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=5810 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
D/Compatibility( 5771): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/SELinux ( 5810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/SystemWebViewEngine( 5750): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 5810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5810): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|-913293406|null|10114
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1169): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@116c3e3b
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/LockPatternUtilsCache( 1169): value : false
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
I/ValidateNoPeople(  852): final affinity: 0.0
I/ValidateNoPeople(  852): Executing: validation for: 0|com.google.android.gm|-2100714965|null|10114
I/PhoneStatusBar( 1169): Icon Only
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 5750): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5750): Attempt to remove local handle scope entry from IRT, ignoring
D/TimaKeyStoreProvider( 5810): TimaSignature is unavailable
D/ActivityThread( 5810): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|-865450363|null|10114
I/ValidateNoPeople(  852): final affinity: 0.0
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
I/ValidateNoPeople(  852): final affinity: 0.0
I/ValidateNoPeople(  852): Executing: validation for: 0|com.google.android.gm|-913293406|null|10114
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|-633420634|null|10114
I/ValidateNoPeople(  852): final affinity: 0.0
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|438982678|null|10114
I/ValidateNoPeople(  852): final affinity: 0.0
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Activity( 5750): performCreate Call secproduct feature valuefalse
D/Activity( 5750): performCreate Call debug elastic valuetrue
I/ValidateNoPeople(  852): final affinity: 0.0
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|1919793178|null|10114
I/ValidateNoPeople(  852): final affinity: 0.0
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
D/OpenGLRenderer( 5750): Render dirty regions requested: true
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SecContentProvider2(  852): uri = 14 selection = getSealedState
D/SecContentProvider2(  852): mCursor = null
D/SecContentProvider2(  852): KnoxCustomManagerService offline: service is not available
D/ActivityManager(  852): post active user change for 0
D/KnoxTimeoutHandler(  852): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  852): handleActiveUserChange for user 0
D/ResourcesManager( 5810): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 1895): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/ResourcesManager( 5810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SurfaceFlinger(  249): id=13 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
D/ApplicationPolicy(  852): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  852): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ValidateNoPeople(  852): Validating: 0|com.google.android.gm|2046740944|null|10114
I/ValidateNoPeople(  852): final affinity: 0.0
D/WindowManager(  852): showStatusBarByNotification() mOpenByNotification=false
I/art     ( 1169): Explicit concurrent mark sweep GC freed 40661(1931KB) AllocSpace objects, 4(348KB) LOS objects, 30% free, 36MB/52MB, paused 5.181ms total 145.864ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 5750): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ActivityManager(  852): Killing 4638:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 5750): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 5750): Enabling debug mode 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/libprocessgroup(  852): failed to open /acct/uid_10017/pid_4638/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InputMethodManagerService(  852): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ActivityManager(  852): Displayed com.example.hello/.MainActivity: +774ms
W/ContextImpl(  852): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Timeline( 5750): Timeline: Activity_idle id: android.os.BinderProxy@29319e0b time:44201
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PushModule( 5810): [PushClientApplication] (main) PushClientApplication.onCreate()
I/PushModule( 5810): [PushClientApplication] (main) PushModule version: 0.9.01.12
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PushModule( 5810): [PushClientApplication] (main) Discovered public push client. disable in app push client.
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/CustomFrequencyManagerService(  852): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  852): mDVFSHelper.release()
I/Timeline(  852): Timeline: Activity_windows_visible id: ActivityRecord{193e525b u0 com.example.hello/.MainActivity t11} time:44250
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/CustomFrequencyManagerService(  852): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1169): value : false
D/ChatON  ( 5810): [1][isApplicationInstalled] com.android.mms was installed
I/chromium( 5750): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5750): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PackageManager(  852): [MSG] SEND_PENDING_BROADCAST
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  852): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/InputReader(  852): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 1488): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ContextImpl( 5810): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/chromium( 5750): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5750): 
W/ActivityManager(  852): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
D/JsMessageQueue( 5750): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
V/BitmapFactory( 1488): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_settings_icon.png
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/RegisteredServicesCache( 1465): empty dynamic service
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (6/8)
V/AlarmManager(  852): waitForAlarm result :8
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (-2/8)
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/Adreno-ES20( 5750): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5750): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ChatON  ( 5810): [1][a] ChatONV isn't installed.
D/ChatON  ( 5810): [1][a] ChatONVPlugIn.isAvailable()
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/BackupManagerService(  852): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  852): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  852): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/CustomFrequencyManagerService(  852): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  tag : ACTIVITY_RESUME_BOOSTER@10
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/art     (  852): Explicit concurrent mark sweep GC freed 26340(1571KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 3.977ms total 164.341ms
,D/SecContentProvider2(  852): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  852): mCursor = null
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/jxcore_app_log( 5750): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259362304
,D/JX-Cordova( 5750): jxcore cordova android initializing
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  ( 5850): MountEmulatedStorage()
I/libpersona( 5850): KNOX_SDCARD checking this for 10098
E/Zygote  ( 5850): v2
I/libpersona( 5850): KNOX_SDCARD not a persona
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,I/ActivityManager(  852): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5850 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  852): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  852): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/ActivityManager(  852): Killing 4937:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/jxcore-log( 5750): Initializing JXcore engine
W/jxcore-log( 5750): JXcore engine is ready
I/SELinux ( 5850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5850): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/BackupManagerService(  852): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  852): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@35d2694d
,W/jxcore-log( 5750): Starting JXcore engine
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/TimaKeyStoreProvider( 5850): TimaSignature is unavailable
D/ActivityThread( 5850): Added TimaKeyStore provider
D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_4937/cgroup.procs: No such file or directory
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 5850): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/auditd  ( 2037): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  852): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  852): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  852): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/jxcore-log( 5750): Platform android
W/jxcore-log( 5750): 
W/jxcore-log( 5750): Process ARCH arm
W/jxcore-log( 5750): 
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,V/GmsNetworkLocationProvi( 1629): DISABLE
,I/jxcore-log( 5750): JXcore Cordova bridge is ready!
I/jxcore-log( 5750): 
,W/jxcore-log( 5750): JXcore engine is started
,I/GCoreNlp( 1629): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/ResourcesManager( 1548): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,E/jxcore-log( 5750): >> samsung-SM-G900F
E/jxcore-log( 5750): 
,I/jxcore-log( 5750): Total memory 1787449344
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Free memory 46411776
I/jxcore-log( 5750): 
I/jxcore-log( 5750): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5750): 
,D/DocsApplication( 5850): Installing DEX configuration.
,I/UpdateIcingCorporaServi( 1548): UpdateCorporaTask done [took 1177 ms] updated apps [took 1176 ms] 
,I/jxcore-log( 5750): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Size 1080 1920
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Screen Brightness 134
I/jxcore-log( 5750): 
,E/jxcore-log( 5750): Dummy Error Log.
E/jxcore-log( 5750): 
,D/LocationProviderProxy(  852): applying state to connected service
,D/LocationProviderProxy(  852): applying state to connected service
,D/DexInstaller( 5850): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 5850): Provided clientMode=RELEASE, packageInfo=PackageInfo{1c17b21e com.google.android.apps.docs}
,D/TAG     ( 5850): onCreate()
,D/CrossAppStateProvider( 5850): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,W/ContextImpl(  852): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 4388): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/SSRM:m  (  852): SIOP:: AP = 470, PST = 438, CUR = 300
,I/jxcore-log( 5750): getBuffer is called!!!!
I/jxcore-log( 5750): 
,I/ActivityManager(  852): Waited long enough for: ServiceRecord{197f7508 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5874): MountEmulatedStorage()
E/Zygote  ( 5874): v2
I/libpersona( 5874): KNOX_SDCARD checking this for 10099
I/libpersona( 5874): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=5874 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 4945:com.android.email/u0a163 (adj 15): bgCount ##41
,I/SELinux ( 5874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/GAV2    ( 5850): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SELinux ( 5874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5874): TimaSignature is unavailable
,D/ActivityThread( 5874): Added TimaKeyStore provider
,W/libprocessgroup(  852): failed to open /acct/uid_10163/pid_4945/cgroup.procs: No such file or directory
,D/ResourcesManager( 5874): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 5874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/FaceInterface( 5363): startFaceScan() : going on
D/FaceInterface( 5363): startFaceScan() is called.
,D/ContentApp( 1217): startScan() is called.
,D/FaceValue( 1217): mSleepTime: 800
D/FaceValue( 1217): mMaxThreadNum: 2
,D/ContentApp( 1217): startScan() is end.
,D/ContentApp( 1217): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1217): isNeedToRestore : start
,E/[CarMode]( 5874): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 5874): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 5874): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5897): MountEmulatedStorage()
,E/Zygote  ( 5897): v2
I/libpersona( 5897): KNOX_SDCARD checking this for 10033
I/libpersona( 5897): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=5897 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5897): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/FaceInterface( 5363): startFaceScan() : going on
D/FaceInterface( 5363): startFaceScan() is called.
,D/ContentApp( 1217): startScan() is called.
,D/ContentApp( 1217): startScan() is end.
,D/ContentApp( 1217): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1217): isNeedToRestore : start
,D/TimaKeyStoreProvider( 5897): TimaSignature is unavailable
D/ActivityThread( 5897): Added TimaKeyStore provider
,D/ResourcesManager( 5897): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 5897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/System.out( 5897): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 5897): Inside WakeupProvider
,E/DatabaseUtils( 5897): Writing exception to parcel
E/DatabaseUtils( 5897): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5897): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5897): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5897): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5897): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5897): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5897): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5897): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5897): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5897): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5897): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 5874): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 5897): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,W/System.err( 5874): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 5874): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5874): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
,W/System.err( 5874): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5874): 	at android.content.ContentResolver.query(ContentResolver.java:484)
,W/System.err( 5874): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5874): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5874): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5874): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5874): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
D/BluetoothAdapter( 5897): 801756392: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 5897): 801756392: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5897): 801756392: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 5897): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
W/System.err( 5874): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5874): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err( 5874): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 5874): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 5874): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 5874): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 5874): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
,W/System.err( 5874): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 5874): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
,W/System.err( 5874): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
,W/System.err( 5874): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5874): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5874): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
,W/System.err( 5874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5874): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5874): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
,W/System.err( 5874): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5874): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,W/System.err( 5874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 5874): [DLApplication]-Init Called!:false
,E/[CarMode]( 5874): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 5874): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 5874): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 5874): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 5874): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 5874): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 5874): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 5874): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 5874): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 5874): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 5874): ### android.os.Looper::loop(145)
I/[CarModeFW]( 5874): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 5874): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 5874): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 5874): ### com.android.internal.os.ZygoteInit::main(1194)
,I/MessageDataHandler( 5874): initialize
,D/[CarModeFW]( 5874): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 5874): CDH-initiazlieCaches : after sync
,W/GAV2    ( 5850): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/BluetoothAdapter( 5874): 829069182: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 5874): 829069182: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 5874): DrivingManager-initialize...
,I/SensorService(  852): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  852): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  852): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/[CarModeFW]( 5874): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 5874): CDH-ContactDataHandler initiazlieCaches time : 13
D/[CarModeFW]( 5874): CDH-initiazlieCaches : end sync
,D/VlingoApplication( 5897): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 5897): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 5874): Need to enable context aware info
V/MediaPlayer-JNI( 5874): native_setup
V/MediaPlayer( 5874): constructor
,V/MediaPlayer( 5874): setListener
,E/MediaPlayer-JNI( 5874): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 5874): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 5874): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 5874): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarMode]( 5874): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1448315161893
,D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1448315161893
D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1448315161893
D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1448315161893
,D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1448315161893
,I/[CarMode]( 5874): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1448315161899
,E/[CarMode]( 5874): [DLApplication]-Init End!:true
,D/TP/SmsProvider( 1478): query,matched:2, calling pid = 5874
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1478): match 2:Elapsed time : 2.093 ms
,E/Zygote  ( 5931): MountEmulatedStorage()
I/libpersona( 5931): KNOX_SDCARD checking this for 10003
E/Zygote  ( 5931): v2
I/libpersona( 5931): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=5931 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 292us total 13.701ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.849ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.513ms
,I/SELinux ( 5931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/[CarModeFW]( 5874): CDH-buildContactCacheWireFrame : cur len =0
,I/SELinux ( 5931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/TP/SmsProvider( 1478): query,matched:2, calling pid = 5874
E/SELinux ( 5931): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 5874): RecommendHandler-selection = type = '3'
,D/TP/SmsProvider( 1478): match 2:Elapsed time : 1.447 ms
,D/MessageDataHandler( 5874):  getInboxList smsCursor : 75
,D/TP/MmsProvider( 1478): Query uri=content://mms/inbox, match=2, calling pid = 5874
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/[CarMode]( 5874): [DLApplication]-GooglePlayServices SUCCESS.
,D/TP/MmsProvider( 1478): Query uri=content://mms, match=0, calling pid = 5874
,E/Zygote  ( 5946): MountEmulatedStorage()
,E/Zygote  ( 5946): v2
I/libpersona( 5946): KNOX_SDCARD checking this for 10020
I/libpersona( 5946): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=5946 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 5946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5946): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5931): TimaSignature is unavailable
,D/ActivityThread( 5931): Added TimaKeyStore provider
,D/[CarModeFW]( 5874): CDH-buildContactCacheWireFrame : cur len =0
,E/SMD     (  284): DCD ON
,D/MessageDataHandler( 5874):  getInboxList mmsCursor : 65
,I/MessageDataHandler( 5874): getUnreadMessageCount :0
D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 144
,D/TimaKeyStoreProvider( 5946): TimaSignature is unavailable
,D/ActivityThread( 5946): Added TimaKeyStore provider
,D/[CarModeFW]( 5874): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 5874):  getInboxList mms,sms cursor join : 9
,E/[CarMode]( 5874): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/ResourcesManager( 5931): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/[CarModeFW]( 5874): RecommendHandler-selection = type = '3'
,D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 5874
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 0.887 ms
,D/TP/MmsSmsProvider( 1478): query,matched:13, calling pid = 5874
,D/TP/MmsSmsProvider( 1478): match 13:Elapsed time : 1.076 ms
,D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/MessageDataHandler( 5874):  getInboxList address cursor : 8
,D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 5874
,D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5500): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
,D/ResourcesManager( 5946): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 2.475 ms
,D/MessageDataHandler( 5874):  getInboxList thread cursor : 5
D/UserAnalysis.PlaceProvider( 5931): PlaceProvider onCreate()
,D/MessageDataHandler( 5874):  thread, addr result: 2
I/[CarModeFW]( 5874): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 173
I/[CarModeFW]( 5874): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 174
,I/UpdateManagerReceiver( 5874): Intent : android.intent.action.PACKAGE_ADDEDMon Nov 23 22:46:02 GMT+01:00 2015
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5965): MountEmulatedStorage()
I/libpersona( 5965): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5965): v2
I/libpersona( 5965): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 4968:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,I/SELinux ( 5965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 5874): PushMessageService-onCreate
,I/ActivityManager(  852): Killing 4549:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,I/ActivityManager(  852): Killing 4658:com.android.calendar/u0a150 (adj 15): bgCount ##42
I/ActivityManager(  852): Killing 5080:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##43
,D/UserAnalysis.SecureDbManager( 5931): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5931): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 5931): Create SecureDbHelper
,D/[CarModeFW]( 5874): PushMessageManager-onServiceConnected
D/[CarModeFW]( 5874): PushMessageService-registerPushMessageServiceListener
,D/TimaKeyStoreProvider( 5965): TimaSignature is unavailable
,D/ActivityThread( 5965): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 5931): onCreate()
,I/SQLiteSecureOpenHelper( 5931): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 5931): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 5931): Open Place.db in secure mode
,D/ResourcesManager( 5965): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/[CarModeFW]( 5874): -[snowdeer] Rec : Missed Call : 218
,D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 291
,I/[CarModeFW]( 5874): -[snowdeer] Rec : Favorite : 13
,W/ContextImpl( 5965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,I/SQLiteSecureOpenHelper( 5931): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 5931): ...getDatabaseLocked(b,b,pwd)
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,I/[CarModeFW]( 5874): -[snowdeer] Rec : CallLog : 5
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5965): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,E/FilterInstaller( 5965): There is no requred permission
,E/Zygote  ( 5982): MountEmulatedStorage()
,E/Zygote  ( 5982): v2
I/libpersona( 5982): KNOX_SDCARD checking this for 10112
I/libpersona( 5982): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5982 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  852): Killing 4186:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,D/[CarModeFW]( 5874): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 5874): MyPlaceProvider-=============
D/[CarModeFW]( 5874): MyPlaceProvider-=============
D/[CarModeFW]( 5874): MyPlaceProvider-=============
,D/[CarModeFW]( 5874): MyPlaceProvider-=============
D/[CarModeFW]( 5874): MyPlaceProvider----End print all data in content provider---
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/[CarModeFW]( 5874): MyPlaceProvider-==============
,D/[CarModeFW]( 5874): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 5874): MyPlaceProvider-==============
D/[CarModeFW]( 5874): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5874): MyPlaceProvider-==============
D/[CarModeFW]( 5874): MyPlaceProvider-latitude is not valid
,D/TimaKeyStoreProvider( 5982): TimaSignature is unavailable
,D/ActivityThread( 5982): Added TimaKeyStore provider
,E/Zygote  ( 5997): MountEmulatedStorage()
I/libpersona( 5997): KNOX_SDCARD checking this for 10046
E/Zygote  ( 5997): v2
I/libpersona( 5997): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5997 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 378
,I/SELinux ( 5997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5997): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/[CarMode]( 5874): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ee7e34b6, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@6c232974] LOCATIONS
,D/ResourcesManager( 5982): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/PowerManagerService(  852): [s] UserActivityState : 2 -> 4
,D/TimaKeyStoreProvider( 5997): TimaSignature is unavailable
,D/ActivityThread( 5997): Added TimaKeyStore provider
,I/PowerManagerService(  852): [PWL] On : 0 (46730 ms ago)
I/PowerManagerService(  852): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,I/PowerManagerService(  852): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI.Notification' ACQUIRE_CAUSES_WAKEUP (uid=10059, pid=1169, ws=null) (elapsedTime=9962)
,W/libprocessgroup(  852): failed to open /acct/uid_10037/pid_4968/cgroup.procs: No such file or directory
,W/libprocessgroup(  852): failed to open /acct/uid_10149/pid_5080/cgroup.procs: No such file or directory
W/libprocessgroup(  852): failed to open /acct/uid_10150/pid_4658/cgroup.procs: No such file or directory
,W/libprocessgroup(  852): failed to open /acct/uid_10046/pid_4549/cgroup.procs: No such file or directory
,I/ActivityManager(  852): Killing 5116:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/PackageIntentReceiver( 5982): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5982): Not GearManger package! 
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
W/libprocessgroup(  852): failed to open /acct/uid_10117/pid_4186/cgroup.procs: No such file or directory
,D/BatteryService(  852): level:100, scale:100, status:5, health:2, present:true, voltage: 4285, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  852): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  852): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  852):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  852): Plugged
I/MotionRecognitionService(  852): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  852): Explicit concurrent mark sweep GC freed 25928(1447KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 1.376ms total 94.513ms
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5997): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 5997): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Zygote  ( 6014): MountEmulatedStorage()
E/Zygote  ( 6014): v2
I/libpersona( 6014): KNOX_SDCARD checking this for 10118
I/libpersona( 6014): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=6014 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 5149:com.sec.factory/1000 (adj 15): bgCount ##41
,I/GAV2    ( 5536): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 6014): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6014): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_5116/cgroup.procs: No such file or directory
,E/SELinux ( 6014): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6014): TimaSignature is unavailable
,D/ActivityThread( 6014): Added TimaKeyStore provider
,D/ResourcesManager( 6014): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 6014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5997): CalendarProvider2.onCreate() called
,W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_5149/cgroup.procs: No such file or directory
,D/MagazineService Version( 6014): Magazine-Administrator: 11
,D/MagazineService Version( 6014): Magazine-Provider: 14
,D/MagazineService Version( 6014): Magazine-Channel: 14
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6032): MountEmulatedStorage()
I/libpersona( 6032): KNOX_SDCARD checking this for 10118
E/Zygote  ( 6032): v2
I/libpersona( 6032): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=6032 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 6014): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 6014): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,I/SELinux ( 6032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6032): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 6014): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 6044): MountEmulatedStorage()
,E/Zygote  ( 6044): v2
I/libpersona( 6044): KNOX_SDCARD checking this for 1000
I/libpersona( 6044): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/MagazineService::MagazineService( 6014): [onHandleIntent] Send broadcast to (com.example.hello).
,E/SELinux ( 6044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6032): TimaSignature is unavailable
,D/ActivityThread( 6032): Added TimaKeyStore provider
,I/ActivityManager(  852): Killing 5164:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 6032): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 6032): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6044): TimaSignature is unavailable
,D/ActivityThread( 6044): Added TimaKeyStore provider
,D/ResourcesManager( 6044): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/HeadlinesChannelApplication( 6032): [onCreate]
,D/Headlines( 6032): Breath.onCreate
,D/HeadlinesCardManager( 6032): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 6032): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 6032): CardProvider Library : 14
,D/MagazineService::CardProviderContentProvider( 6014): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6014): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 6032): registerCardProvider: provider already exists.
,D/Headlines( 6032): HeadlinesDataCenter ctor
,D/Headlines( 6032): HeadlinesDataCenter. mLocale = en_US
,W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_5164/cgroup.procs: No such file or directory
,D/HeadlinesChannelUtil( 6032): getCountryCode(): countryCode = DE
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 6032): HeadlinesCardManager : constructor welcome :YES
,E/Zygote  ( 6068): MountEmulatedStorage()
E/Zygote  ( 6068): v2
I/libpersona( 6068): KNOX_SDCARD checking this for 1000
I/libpersona( 6068): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/System.out( 5897): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 6068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 5874): -[snowdeer] Rec : Schedule : 636
,I/[CarModeFW]( 5874): -[snowdeer] Rec : During DL app : 2
,I/[CarModeFW]( 5874): -[snowdeer] Rec : Location Sharing : 1
,I/[CarModeFW]( 5874): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 5874): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5874): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5874): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 5874): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 952
,I/[CarModeFW]( 5874): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5874): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5874): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 5874): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 953
,D/TimaKeyStoreProvider( 6068): TimaSignature is unavailable
,D/ActivityThread( 6068): Added TimaKeyStore provider
,D/ResourcesManager( 6068): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6068): Received: android.intent.action.PACKAGE_ADDED
,E/Zygote  ( 6085): MountEmulatedStorage()
E/Zygote  ( 6085): v2
I/libpersona( 6085): KNOX_SDCARD checking this for 10135
I/libpersona( 6085): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6085 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 6068): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/ActivityManager(  852): Killing 4888:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,I/SELinux ( 6085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6085): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 6068): Enter Oncreate
,D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6068): creating AcmsCore
,D/AcmsCore( 6068): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6068): AcmsCore
,D/AcmsCore( 6068): init
,D/AcmsCore( 6068): Looper handler is not null
,D/AcmsCore( 6068): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsCertificateMngr( 6068): AcmsCertificateMngr
,D/AcmsRevocationMngr( 6068): AcmsRevocationMngr
D/TimaKeyStoreProvider( 6085): TimaSignature is unavailable
,D/AcmsServiceMonitor( 6068): Incrementing - Counter value: 1
D/AcmsCore( 6068): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/ActivityThread( 6085): Added TimaKeyStore provider
,D/AcmsService( 6068): onStartCommand
,D/AcmsService( 6068): Action: android.intent.action.PACKAGE_ADDED
,D/AcmsServiceMonitor( 6068): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6068): Incrementing - Counter value: 2
D/AcmsService( 6068): Incremented Counter Value : onStartCommand
,D/ActivityThread( 6068): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ResourcesManager( 6085): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/libprocessgroup(  852): failed to open /acct/uid_10078/pid_4888/cgroup.procs: No such file or directory
,W/ResourcesManager( 6085): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 6068): Inside handle Intent
D/AcmsService( 6068): App added - package name: com.example.hello
D/AcmsCore( 6068): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6068): Incrementing - Counter value: 3
D/AcmsCore( 6068): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6068): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6068): Decrementing - Counter value: 2
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  852): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=6116 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6116): MountEmulatedStorage()
E/Zygote  ( 6116): v2
I/libpersona( 6116): KNOX_SDCARD checking this for 10166
I/libpersona( 6116): KNOX_SDCARD not a persona
,I/SELinux ( 6116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6116): TimaSignature is unavailable
,D/ActivityThread( 6116): Added TimaKeyStore provider
,I/GLSActivity( 1689): [ac] getting account id
,D/ResourcesManager( 6116): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,I/GLSUser ( 1689): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/ResourcesManager( 6116): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 6116): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6133): MountEmulatedStorage()
I/libpersona( 6133): KNOX_SDCARD checking this for 10170
E/Zygote  ( 6133): v2
I/libpersona( 6133): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6133 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 11.072ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 7.721ms
,I/SELinux ( 6133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6133): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 409us total 8.567ms
,D/TimaKeyStoreProvider( 6133): TimaSignature is unavailable
,D/ActivityThread( 6133): Added TimaKeyStore provider
,D/ResourcesManager( 6133): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 6133): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6150): MountEmulatedStorage()
,E/Zygote  ( 6150): v2
I/libpersona( 6150): KNOX_SDCARD checking this for 10030
I/libpersona( 6150): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6150 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 5259:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/AcmsKeyStoreHelper( 6068):  getKeyStoreForApplication Enter
,I/SELinux ( 6150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6150): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6150): TimaSignature is unavailable
,D/ActivityThread( 6150): Added TimaKeyStore provider
,W/libprocessgroup(  852): failed to open /acct/uid_10025/pid_5259/cgroup.procs: No such file or directory
,I/AcmsKeyStoreHelper( 6068): Key Store exist
I/AcmsKeyStoreHelper( 6068): Hence loading the keystore file
,D/ResourcesManager( 6150): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/AcmsKeyStoreHelper( 6068):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6068): getKeyStoreForApplication success 
D/AcmsCore( 6068): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6068): Decrementing - Counter value: 1
D/AcmsCore( 6068): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6068): This is NOT a valid MirrorLink app
D/AcmsCore( 6068): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6068): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6068): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6068): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6068): getSvcCounter - Counter value: 0
D/AcmsService( 6068): Enter onDestroy
I/AcmsService( 6068): cleanUp(): inside service clean up
D/AcmsCore( 6068): AcmsCore: inside DeInit
D/AcmsCore( 6068): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6068): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6068): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6068): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6068): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 6068): getSvcCounter - Counter value: 0
D/AcmsService( 6068): killing acms process
I/Process ( 6068): Sending signal. PID: 6068 SIG: 9
,D/Finsky  ( 6150): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  852): Process ACMS.Process (pid 6068)(adj 0) has died(64,591)
,I/CalendarProvider2( 5997): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  852): Killing 5275:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,D/Finsky  ( 6150): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  852): failed to open /acct/uid_10172/pid_5275/cgroup.procs: No such file or directory
,E/Zygote  ( 6187): MountEmulatedStorage()
,E/Zygote  ( 6187): v2
I/libpersona( 6187): KNOX_SDCARD checking this for 10012
I/libpersona( 6187): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6187 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6187): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6150): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6150): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6187): TimaSignature is unavailable
,D/ActivityThread( 6187): Added TimaKeyStore provider
,D/ResourcesManager( 6187): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6187): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6187): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  852): Killing 5379:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,D/Finsky  ( 6150): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6150): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 6187): VM with version 2.1.0 has multidex support
I/MultiDex( 6187): install
I/MultiDex( 6187): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6150): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/libprocessgroup(  852): failed to open /acct/uid_10002/pid_5379/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 1895): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1895): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/Finsky  ( 6150): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 6187): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ConfigFetchService( 1895): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1895): launchTask
,I/PeopleContactsSync( 1895): CP2 sync disabled
,D/ChimeraCfgMgr( 1895): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/ResourcesManager( 1895): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/Vision  ( 1895): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1895): Failed to find package metadata for com.example.hello
,D/Vision  ( 1895): No vision deps
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6213): MountEmulatedStorage()
I/libpersona( 6213): KNOX_SDCARD checking this for 10040
E/Zygote  ( 6213): v2
I/libpersona( 6213): KNOX_SDCARD not a persona
,V/ConfigFetchTask( 1895): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WVEVSmpBsg3AtHcJcjWTdxQQ6ddTYgfFUtm2mt36S4pRHvyAaCrgfHcJOBYXy3lwoROF5smSIzB3-Rb6ioacjaL1t1STLwQMmZORCU2BpdOGdpr-D9YbkpnChRVYNaIn-oFtHBHD9Yv3dG_vR8ewHvp0Kqj-HcJ-wwvThQuzTt0NeRx4v7p98lQxhA16GqKKlsRd1MUN-zTHSUcSX8_Ne99mdL44E0NCUIe4zgfOuZ5pGrBig
,I/ActivityManager(  852): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6213 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityThread( 6187): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6187): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1971b8ea: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6187): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 6213): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6213): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6213): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/GoogleURLConnFactory( 1895): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 6213): TimaSignature is unavailable
,D/ActivityThread( 6213): Added TimaKeyStore provider
,D/ResourcesManager( 6213): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/System.out( 1895): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1895): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1895): (HTTPLog)-Thread-244-18223292: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ConfigFetchTask( 1895): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1895): fetch service done; releasing wakelock
,I/ConfigFetchService( 1895): stopping self
,D/ResourcesManager( 6187): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6235): MountEmulatedStorage()
E/Zygote  ( 6235): v2
I/libpersona( 6235): KNOX_SDCARD checking this for 10117
I/libpersona( 6235): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6235 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 5301:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,I/SELinux ( 6235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6235): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  852): failed to open /acct/uid_10004/pid_5301/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6235): TimaSignature is unavailable
,D/ActivityThread( 6235): Added TimaKeyStore provider
,I/ActivityManager(  852): Killing 5344:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,D/ResourcesManager( 6235): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 6187): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/ResourcesManager( 6235): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/Finsky  ( 6150): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/libprocessgroup(  852): failed to open /acct/uid_10044/pid_5344/cgroup.procs: No such file or directory
,I/Babel   ( 6235): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6235): MmsConfig.loadMmsSettings
I/Babel   ( 6235): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
I/Babel   ( 6235): MmsConfig.loadFromDatabase
D/ResourcesManager( 6235): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/AudioCapabilities( 6235): Unsupported mime audio/evrc
,E/Babel   ( 6235): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6235): MmsConfig.loadFromResources
,W/AudioCapabilities( 6235): Unsupported mime audio/qcelp
,E/Babel   ( 6235): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6235): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
W/VideoCapabilities( 6235): Unrecognized profile 2130706433 for video/avc
,W/Settings( 6235): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6235): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6235): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6235): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6235): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6235): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6235): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6235): Unsupported mime audio/evrc
,W/VideoCapabilities( 6235): Unsupported mime video/wvc1
,W/VideoCapabilities( 6235): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6235): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6235): Unsupported mime video/wvc1
,W/VideoCapabilities( 6235): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6235): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6235): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6235): Unsupported mime video/mp43
,W/VideoCapabilities( 6235): Unsupported mime video/sorenson
,I/VideoCapabilities( 6235): Unsupported profile 4 for video/mp4v-es
,E/SQLiteLog( 6235): (284) automatic index on conversation_participants_view(conversation_id)
,D/BootupListener( 1478): ACTION_DRIVELINK
,D/SettingsProvider(  852): name = drivelink_navigation
D/SettingsProvider(  852): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  852): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  852): selectionArgs: false
D/SettingsProvider(  852): selectionArgs: 1001
D/SecContentProvider(  852): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  852): ret = -1
,D/BootupListener( 1478): NAVI : com.google.android.apps.maps
D/SettingsProvider(  852): name = internet_call_settings_visibility
D/SettingsProvider(  852): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  852): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  852): selectionArgs: false
D/SettingsProvider(  852): selectionArgs: 1001
D/SecContentProvider(  852): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  852): ret = -1
,E/SQLiteLog( 6235): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6235): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6235): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6235): (284) automatic index on conversation_participants_view(conversation_id)
,I/art     (  852): Explicit concurrent mark sweep GC freed 21258(1484KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 5.642ms total 89.446ms
,I/ActivityManager(  852): Killing 5182:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,D/GCM     ( 1689): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1689): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/AlarmManager(  852): waitForAlarm result :4
,V/GmsCoreStatsServiceLauncher( 1895): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/Finsky  ( 6150): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/libprocessgroup(  852): failed to open /acct/uid_10126/pid_5182/cgroup.procs: No such file or directory
,D/WearableService( 5056): callingUid 10012, callindPid: 5056
,E/MDM     ( 1629): [171] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1895): Restart initialization of location
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4589): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4589): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4589): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/SMD     (  284): DCD ON
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1689): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 4589): RegionGroup for  is null
,D/ChimeraCfgMgr( 1895): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1895): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1895): [KidAccountFixer] No network connection
,W/Finsky  ( 6150): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/BluetoothManager( 4589): getConnectedDevices
,D/BluetoothManager( 4589): getConnectedDevices
,D/BluetoothManager( 4589): getConnectedDevices
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1689): Explicit concurrent mark sweep GC freed 11994(627KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 522us total 30.209ms
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 6299): MountEmulatedStorage()
I/libpersona( 6299): KNOX_SDCARD checking this for 10149
E/Zygote  ( 6299): v2
I/libpersona( 6299): KNOX_SDCARD not a persona
I/ActivityManager(  852): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6299 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/SELinux ( 6299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6299): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 6235): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TimaKeyStoreProvider( 6299): TimaSignature is unavailable
,D/ActivityThread( 6299): Added TimaKeyStore provider
,D/ResourcesManager( 6299): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 6299): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6299): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 6235): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6235): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6235): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 6315): MountEmulatedStorage()
E/Zygote  ( 6315): v2
I/libpersona( 6315): KNOX_SDCARD checking this for 10150
,I/libpersona( 6315): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6315 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 6315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/JNIHelp ( 6235): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/Finsky  ( 6150): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/TimaKeyStoreProvider( 6315): TimaSignature is unavailable
,D/ActivityThread( 6315): Added TimaKeyStore provider
,D/ResourcesManager( 6315): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6315): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6315): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityThread( 6235): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6235): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39983c55: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6235): Installed default security provider GmsCore_OpenSSL
,D/BluetoothAdapter( 5750): disable()
,E/BluetoothManagerService(  852): Bluetooth is already disabled. DO NOT disable again.
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/Babel_RequestWriter( 6235): error sending REQ[fc:12; creat:1448298954738; type:bev-109636906]; took 2 ms (error code == 101)
,D/WifiService(  852): New client listening to asynchronous messages
,I/WifiManager( 5750): packageName : com.example.hello
,D/SecContentProvider(  852): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  852): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  852): mCursor = null
,D/WifiService(  852): setWifiEnabled: false pid=5750, uid=10374
,E/WifiService(  852): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  852): name = wifi_on
,I/jxcore-log( 5750): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5750): 
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4589): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4589): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4589): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/AndroidRuntime( 6347): 
D/AndroidRuntime( 6347): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,E/Zygote  ( 6350): MountEmulatedStorage()
E/Zygote  ( 6350): v2
,I/libpersona( 6350): KNOX_SDCARD checking this for 10036
I/libpersona( 6350): KNOX_SDCARD not a persona
,D/AndroidRuntime( 6347): CheckJNI is OFF
,D/AndroidRuntime( 6347): setted country_code = Germany
,D/AndroidRuntime( 6347): setted countryiso_code = DE
,D/AndroidRuntime( 6347): setted sales_code = DBT
,I/ActivityManager(  852): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6350 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/AndroidRuntime( 6347): readGMSProperty: start
D/AndroidRuntime( 6347): readGMSProperty: already setted!!
,D/AndroidRuntime( 6347): readGMSProperty: end
D/AndroidRuntime( 6347): addProductProperty: start
,I/SELinux ( 6350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SELinux ( 6350): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6350): TimaSignature is unavailable
,D/ActivityThread( 6350): Added TimaKeyStore provider
,I/GLSUser ( 1689): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1689): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1689): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1689): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 6350): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/ContextImpl(  852): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Finsky  ( 6150): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6150): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6150): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6150): [1] DailyHygiene.reschedule: Scheduling new run in 283 minutes (failures=4)
,D/DeviceConnectionService( 1629): client connected with version: 7571000
,E/AffinityControl( 6347): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6347): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  852): START PACKAGE DELETE: observer{915705519}
D/PackageManager(  852): pkg{<packageName>}
D/PackageManager(  852): user{0}
D/PackageManager(  852): caller{2000}
D/PackageManager(  852): flags{3}
D/PersonaManagerService(  852): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  852): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  852): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  852): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  852): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  852): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  852): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  852): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  852): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  852): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  852): !@killApplicatoin: 10374, uninstall pkg
,I/ActivityManager(  852): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 24668(1458KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 18MB/30MB, paused 505us total 44.272ms
I/ActivityManager(  852): Killing 5750:com.example.hello/u0a374 (adj 0): stop com.example.hello
,W/ActivityManager(  852): Force removing ActivityRecord{193e525b u0 com.example.hello/.MainActivity t11}: app died, no saved state
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (5/7)
I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/7)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3284): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3284): getDatabaseLocked(b,b,pwd)...
,D/CustomFrequencyManagerService(  852): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  852): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/WifiService(  852): Client connection lost with reason: 4
,D/ResourcesManager( 6350): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  852): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  852): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/ResourcesManager( 6350): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6350): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6350): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/FocusedStackFrame(  852): Set to : 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
I/ActivityManager(  852): Force stopping com.example.hello appid=10374 user=0: pkg removed
D/LockPatternUtilsCache( 1169): value : false
,D/SurfaceWidgetView( 1488): destroyHardwareResources():53970086
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/Launcher( 1488): onRestart, Launcher: 699341773
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager( 6350): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6350): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6350): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6350): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Launcher( 1488): onStart, Launcher: 699341773
D/Launcher.HomeView( 1488): onStart
,D/Launcher( 1488): onResume, Launcher: 699341773
,D/SettingsProvider(  852): name = kids_home_mode
D/SettingsProvider(  852): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  852): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  852): selectionArgs: false
D/ConnectivityService(  852): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SettingsProvider(  852): selectionArgs: 10008
D/SecContentProvider(  852): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  852): ret = -1
D/Launcher.HomeView( 1488): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2230): [237392/6] Surface widget resume on instance = 1
,D/accuweather( 2230): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
,D/ResourcesManager(  852): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/Launcher( 1488): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/art     ( 4388): Explicit concurrent mark sweep GC freed 2863(161KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 324us total 27.712ms
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 6350): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/SamsungIME( 1861): mOCRHelper is null
,I/InputReader(  852): Reconfiguring input devices.  changes=0x00000010
,D/MenuAppsGridFragment( 1488): onResume
,W/GeofencerStateMachine( 1629): Ignoring removeGeofence because network location is disabled.
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/ResourcesManager( 6350): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6350): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ActivityManager(  852): handle home activity for 0
I/WallpaperManagerService(  852): switchPersonaWallpaper is called for personaId-0
D/ActivityManager(  852): post active user change for 0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2230): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/KnoxTimeoutHandler(  852): postActiveUserChange for user 0
D/accuweather( 2230): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
,D/SurfaceWidget.Renderer( 2230): [237392/6] SurfaceWidget drawing first frame
D/accuweather( 2230): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
,D/accuweather( 2230): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
D/accuweather( 2230): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
D/accuweather( 2230): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
D/accuweather( 2230): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/Zygote  ( 6380): MountEmulatedStorage()
,E/Zygote  ( 6380): v2
I/libpersona( 6380): KNOX_SDCARD checking this for 10071
I/libpersona( 6380): KNOX_SDCARD not a persona
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/ActivityManager(  852): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=6380 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,I/SELinux ( 6380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/RegisteredServicesCache( 1465): empty dynamic service
,I/SELinux ( 6380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
E/SELinux ( 6380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBarManagerService(  852): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SecContentProvider2(  852): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  852): mCursor = null
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/TimaKeyStoreProvider( 6380): TimaSignature is unavailable
,D/ActivityThread( 6380): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 1488): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,W/ResourcesManager( 1488): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1488): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1488): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 6380): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/ResourcesManager( 6380): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6380): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6380): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1488): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1488): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1488): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/Launcher( 1488): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/comsamsunglog( 6380): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 6380): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 6380): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 6380): [KK AccuPhone]>>> ==============================================================================================
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/InputMethodManagerService(  852): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/comsamsunglog( 6380): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 6380): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 6380): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 6380): [KK AccuPhone]>>> ==============================================================================================
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/InputMethodManagerService(  852): Got RemoteException sending setActive(false) notification to pid 5750 uid 10374
,D/SettingsProvider(  852): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  852): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  852): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  852): selectionArgs: false
D/SettingsProvider(  852): selectionArgs: 10071
D/SecContentProvider(  852): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  852): ret = -1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ContextImpl(  852): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MicrophoneInputStream( 1548): mic_starting gfk@221f27b2
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,V/AudioPolicyManager(  289): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
,V/AudioPolicyManager(  289): getDeviceForInputSource()input source 1999, device 80000004
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
V/audio_hw_primary(  289): adev_open_input_stream: enter
D/LockPatternUtilsCache( 1169): value : false
E/audio_hw_primary(  289): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  289): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  289): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  289): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  289): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  289): adev_open_input_stream: exit
,I/HotwordRecognitionRnr( 1548): Starting hotword detection.
,I/AudioFlinger(  289): AudioFlinger's thread 0xaf97e000 ready to run
V/audio_hw_primary(  289): in_standby: enter
V/audio_hw_primary(  289): in_standby: exit:  status(0)
,D/accuweather( 2230): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,V/audio_hw_primary(  289): in_standby: enter
V/audio_hw_primary(  289): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  852): isMicrophoneEnabled
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/AudioPolicyManager(  289): startInput() input 30
V/AudioPolicyManager(  289): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  289): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  289): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  289): DeviceVector::getDevicesFromType() for type 80000004 found 0xb295b3c0
,V/audio_hw_primary(  289): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  289): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  289): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  289): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1548): mic_started gfk@221f27b2
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/RCPManagerService(  852): PackageReceiver onReceive()
I/HarmonyEASService(  852): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  852): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/accuweather( 2230): [KK AccuPhone]>>> SM:442 [0:0] updateView iSA = false, mCI = 0, mSL = null , cls = 0 , cls = 1
D/accuweather( 2230): [KK AccuPhone]>>> SM:447 [0:0] bg transparency val = 0
,D/accuweather( 2230): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
D/accuweather( 2230): [KK AccuPhone]>>> SM:1044 [0:0] setLayoutContentEmptyMsg = 2131558522
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBarManagerService(  852): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/msm8974_platform(  289): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  289): start_input_stream: enter: usecase(7)
V/voice   (  289): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  289): start_input_stream: usecase(7)
D/PreProcess(  289): new SamsungRecord
D/PreProcess(  289): new NS
I/samsungRecord(  289): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  289): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  289): miccalib file can't created. (/data/snd/miccalib.txt)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/samsungRecord(  289): 1
D/SamsungRecord_NS(  289): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  289): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  289): select_devices: ENTER
V/audio_hw_primary(  289): select_devices: usecase(normal)
V/audio_hw_primary(  289): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  289): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  289): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  289): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  289): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  289): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  289): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  289): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  289): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  289): ACDB -> send_adm_topology
D/ACDB-LOADER(  289): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ACDB-LOADER(  289): ACDB -> send_asm_topology
D/ACDB-LOADER(  289): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  289): ACDB -> send_audtable
D/ACDB-LOADER(  289): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/        (  289): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  289): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  289): ACDB -> send_audvoltable
D/ACDB-LOADER(  289): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  289): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  289): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  289): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  289): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  289): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  289): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: DEC2 Volume
D/audio_route(  289): Setting mixer control: value: 106
D/accuweather( 2230): [KK AccuPhone]>>> U:1012 [0:0] icon = 99, isDay = true, type = 261
D/accuweather( 2230): [KK AccuPhone]>>> U:1187 [0:0] resID = 2130837848
,D/accuweather( 2230): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/BackupManagerService(  852): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  852): Receieved: android.intent.action.PACKAGE_REMOVED
,D/audio_route(  289): Setting mixer control: SLIM TX7 MUX, value: 9
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/audio_route(  289): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  289): Setting mixer control: value: 1
D/LockPatternUtilsCache( 1169): value : false
,V/EnterpriseBillingPolicy(  852): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  852): uID is 10374
V/EnterpriseBillingPolicy(  852): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  852): getProfileForApplication - enter
D/audio_route(  289): Setting mixer control: DEC2 MUX, value: 1
,V/EnterpriseBillingPolicyStorage(  852): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  852): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  852): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  852): getBillingProfileForVpnEngine - start - com.example.hello
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  289): enable_audio_route: apply mixer path: audio-record
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  289): Setting mixer control: value: 1
V/EnterpriseBillingPolicyStorage(  852): getBillingProfileForVpnEngine - end - null
,D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): enable_audio_route: exit
V/audio_hw_primary(  289): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  289): start_input_stream: exit
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/WallpaperManagerService(  852):  force update = false; persona id = 0; current user =0; current persona = 0
,D/TaskPersister(  852): removeObsoleteFile: deleting file=11_task.xml
D/KnoxTimeoutHandler(  852): handleActiveUserChange for user 0
,D/EnterpriseDeviceManagerService(  852): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  852): Admin package name: com.google.android.gms
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
I/Timeline( 1488): Timeline: Activity_idle id: android.os.BinderProxy@39983c55 time:50837
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
I/GAV2    ( 5850): Thread[GAThread,5,main]: No campaign data found.
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/SurfaceWidget.Renderer( 2230): [237392/6] SurfaceWidget drawing first frame
,D/accuweather( 2230): [KK AccuPhone]>>> SM:1072 [0:0] complete setLayoutContentEmptyMsg Content
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/HotwordWorker( 1548): onReady
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BitmapFactory( 1488): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic.png
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ActivityManager(  852): Killing 5455:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SurfaceWidget.Renderer( 2230): [237392/6] SurfaceWidget drawing first frame
,W/ResourcesManager(  852): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  852): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/CustomFrequencyManagerService(  852): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  852): mDVFSHelper.release()
D/CustomFrequencyManagerService(  852): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SurfaceWidget.Renderer( 2230): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2230): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/art     (  852): Explicit concurrent mark sweep GC freed 46955(3MB) AllocSpace objects, 6(96KB) LOS objects, 30% free, 36MB/52MB, paused 1.863ms total 379.358ms
,D/ResourcesManager(  852): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/libprocessgroup(  852): failed to open /acct/uid_10094/pid_5455/cgroup.procs: No such file or directory
,D/ResourcesManager(  852): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  852): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,I/Babel_RequestWriter( 6235): error sending REQ[fc:13; creat:1448298954738; type:bev-109636906]; took 0 ms (error code == 101)
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/PackageManager(  852): delete codoeFile: 
,D/PackageManager(  852): result of delete: 1{915705519}
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/AndroidRuntime( 6347): Shutting down VM
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  852): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  852): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  852): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  852): clearDefaults: com.example.hello
,I/CrashAnrDetector(  852): onPackageRemoved : com.example.hello
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline(  852): Timeline: Activity_windows_visible id: ActivityRecord{3d7e693f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:51051
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/CustomFrequencyManagerService(  852): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 852  tag : ACTIVITY_RESUME_BOOSTER@10
,E/SPPClientService( 5011): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6421): MountEmulatedStorage()
E/Zygote  ( 6421): v2
I/libpersona( 6421): KNOX_SDCARD checking this for 10038
I/libpersona( 6421): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=6421 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 5480:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,I/SELinux ( 6421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6421): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  852): failed to open /acct/uid_10103/pid_5480/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6421): TimaSignature is unavailable
,D/ActivityThread( 6421): Added TimaKeyStore provider
,D/ResourcesManager( 6421): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6421): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6421): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6421): PushLog.txt file is not deleted.
,D/SPPClientService( 6421): PushLog.txt file is not deleted.
D/SPPClientService( 6421): ============PushLog. stop!
,E/SharedPreferencesImpl( 6421): Couldn't rename file /data/data/com.sec.spp.push/shared_prefs/log_sender_pref.xml to backup file /data/data/com.sec.spp.push/shared_prefs/log_sender_pref.xml.bak
,E/SharedPreferencesImpl( 6421): Couldn't rename file /data/data/com.sec.spp.push/shared_prefs/log_sender_pref.xml to backup file /data/data/com.sec.spp.push/shared_prefs/log_sender_pref.xml.bak
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  852): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=6441 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  852): Killing 5500:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
E/Zygote  ( 6441): MountEmulatedStorage()
E/Zygote  ( 6441): v2
I/libpersona( 6441): KNOX_SDCARD checking this for 10038
I/libpersona( 6441): KNOX_SDCARD not a persona
,I/SELinux ( 6441): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6441): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  852): Removing device '/dev/input/event4' due to inotify event
,D/TimaKeyStoreProvider( 6441): TimaSignature is unavailable
D/ActivityThread( 6441): Added TimaKeyStore provider
,D/ResourcesManager( 6441): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  852): failed to open /acct/uid_10113/pid_5500/cgroup.procs: No such file or directory
,I/EventHub(  852): Removing device '/dev/input/event5' due to inotify event
,E/SPPClientService( 6441): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6441): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6441): PushLog.txt file is not deleted.
,D/SPPClientService( 6441): PushLog.txt file is not deleted.
D/SPPClientService( 6441): ============PushLog. stop!
,E/LNoti   ( 6441): [PhoneStatusChangeReceiver] This device doesn't register yet.
,I/EventHub(  852): Removing device '/dev/input/event6' due to inotify event
,I/EventHub(  852): Removing device '/dev/input/event7' due to inotify event
,I/PowerManagerService(  852): [PWL] On : 0 (51730 ms ago)
I/PowerManagerService(  852): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  852): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI.Notification' ACQUIRE_CAUSES_WAKEUP (uid=10059, pid=1169, ws=null) (elapsedTime=14962)
,I/EventHub(  852): Removing device '/dev/input/event8' due to inotify event
,I/EventHub(  852): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  852): Removing device '/dev/input/event10' due to inotify event
,I/ActivityManager(  852): Killing 4731:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,D/GCM     ( 1689): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1689): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1895): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/EventHub(  852): Removing device '/dev/input/event11' due to inotify event
,E/MDM     ( 1629): [154] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1895): Restart initialization of location
,W/libprocessgroup(  852): failed to open /acct/uid_10154/pid_4731/cgroup.procs: No such file or directory
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6461): MountEmulatedStorage()
E/Zygote  ( 6461): v2
I/libpersona( 6461): KNOX_SDCARD checking this for 1000
I/libpersona( 6461): KNOX_SDCARD not a persona
,I/ActivityManager(  852): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6461 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 294us total 15.701ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.955ms
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.856ms
,I/SELinux ( 6461): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 6461): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6461): TimaSignature is unavailable
,D/ActivityThread( 6461): Added TimaKeyStore provider
,D/ResourcesManager( 6461): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,W/ContextImpl( 6461): Unable to create files subdir /data/data/com.samsung.android.MtpApplication/cache
E/ActivityThread( 6461): Unable to setupGraphicsSupport due to missing cache directory
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,E/audit_log( 2037): File locking failed. error= Bad file number
,I/ActivityManager(  852): Process com.samsung.android.MtpApplication (pid 6461)(adj 0) has died(105,597)
,E/SMD     (  284): DCD ON
,E/audit_log( 2037): File locking failed. error= Bad file number
,D/MtpService( 1217): updating state; isCurrentUser=true, mMtpLocked=false
,I/ActivityManager(  852): Process com.android.settings (pid 1296)(adj 0) has died(116,597)
,D/WifiService(  852): Client connection lost with reason: 4
W/ActivityManager(  852): Scheduling restart of crashed service com.android.settings/.wifi.WifiCredService in 1000ms
W/ActivityManager(  852): Scheduling restart of crashed service com.android.settings/.wifi.hs20.Hs20UtilityService in 11000ms
,E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  852): checkUser: useridlist=null, currentuser=0

```
