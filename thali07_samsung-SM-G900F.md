#### Test 50242285e707819_thali07_samsung-SM-G900F Logs


```
--------- beginning of system
I/ActivityManager(  855): Waited long enough for: ServiceRecord{61a79cc u0 com.samsung.android.providers.context/.ContextService}
--------- beginning of main
I/Gmail   ( 5494): getAccountsCursor
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  855): waitForAlarm result :4
,D/BatteryService(  855): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  855): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  855): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  855):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  855): Plugged
I/MotionRecognitionService(  855): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/HomeSyncInstallReceiver( 1467): This pkg do not need BT addr. Do nothing
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
I/NotifUtils( 5494): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
E/Zygote  ( 5559): MountEmulatedStorage()
E/Zygote  ( 5559): v2
I/libpersona( 5559): KNOX_SDCARD checking this for 10015
I/libpersona( 5559): KNOX_SDCARD not a persona
I/ActivityManager(  855): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5559 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 5559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5559): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5559): TimaSignature is unavailable
I/NotifUtils( 5494): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
D/ActivityThread( 5559): Added TimaKeyStore provider
I/NotifUtils( 5494): Showing notification with unreadCount of 7 and unseenCount of 7
D/ResourcesManager( 5559): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
W/ContextImpl( 3725): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1796 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
I/DBG_DM  ( 3479): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(522/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/DBG_DM  ( 3479): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(526/onReceive)] status  = 1
I/Process ( 3725): Sending signal. PID: 3725 SIG: 9
E/DBG_DM  ( 3479): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(537/onReceive)] Device is ok
I/ActivityManager(  855): Waited long enough for: ServiceRecord{2d14c32a u0 com.android.settings/.wifi.WifiCredService}
I/DBG_DM  ( 3479): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.android.launcher2.Launcher
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5579): MountEmulatedStorage()
E/Zygote  ( 5579): v2
I/libpersona( 5579): KNOX_SDCARD checking this for 10016
I/libpersona( 5579): KNOX_SDCARD not a persona
I/ActivityManager(  855): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=5579 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Process com.sec.android.app.sysscope (pid 3725)(adj 0) has died(57,680)
I/SELinux ( 5579): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  855): Killing 4441:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
I/SELinux ( 5579): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5579): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  855): Waited long enough for: ServiceRecord{93e7f6 u0 com.android.settings/.wifi.hs20.Hs20UtilityService}
D/TimaKeyStoreProvider( 5579): TimaSignature is unavailable
D/ActivityThread( 5579): Added TimaKeyStore provider
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_4441/cgroup.procs: No such file or directory
D/ResourcesManager( 5579): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
W/ResourcesManager( 5579): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5579): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/GroupCast_FileTools( 5579): [getDirectoryForImageResized : 295] cleaning!!
W/System.err( 5579): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 5579): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 5579): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5579): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5579): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5579): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5579): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5579): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5579): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5579): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5579): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5579): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5579): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5579): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5579): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5597): MountEmulatedStorage()
E/Zygote  ( 5597): v2
I/libpersona( 5597): KNOX_SDCARD checking this for 1000
I/libpersona( 5597): KNOX_SDCARD not a persona
I/ActivityManager(  855): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5597 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  855): Killing 4465:com.LocalFota/u0a120 (adj 15): bgCount ##41
I/SELinux ( 5597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5597): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5571): 
D/AndroidRuntime( 5571): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5571): CheckJNI is OFF
D/AndroidRuntime( 5571): setted country_code = Germany
D/AndroidRuntime( 5571): setted countryiso_code = DE
D/AndroidRuntime( 5571): setted sales_code = DBT
D/AndroidRuntime( 5571): readGMSProperty: start
D/AndroidRuntime( 5571): readGMSProperty: already setted!!
D/AndroidRuntime( 5571): readGMSProperty: end
D/AndroidRuntime( 5571): addProductProperty: start
I/DBG_DM  ( 3479): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 13 sec
D/TimaKeyStoreProvider( 5597): TimaSignature is unavailable
D/ActivityThread( 5597): Added TimaKeyStore provider
W/libprocessgroup(  855): failed to open /acct/uid_10120/pid_4465/cgroup.procs: No such file or directory
I/PeopleDatabaseHelper( 1887): cleanUpNonGplusAccounts done.
D/ResourcesManager( 5597): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ConnectivityService(  855): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3479): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/ConnectivityService(  855): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3479): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
E/DBG_DM  ( 3479): [llIlIIIIlllIlllllIll(232/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
I/DBG_DM  ( 3479): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.android.launcher2.Launcher
I/PCWCLIENTTRACE_LOG( 5597): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5597): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5597): new DMDBOpenHelper instance
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
I/PCWCLIENTTRACE_PushUtil( 5597): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5597): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5597): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5597): [onReceive] - android.intent.action.PACKAGE_ADDED
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5613): MountEmulatedStorage()
E/Zygote  ( 5613): v2
I/libpersona( 5613): KNOX_SDCARD checking this for 10034
I/libpersona( 5613): KNOX_SDCARD not a persona
I/ActivityManager(  855): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5613 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  855): Killing 4503:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
I/SELinux ( 5613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5613): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  855): Killing 4535:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 5613): TimaSignature is unavailable
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_4503/cgroup.procs: No such file or directory
D/ActivityThread( 5613): Added TimaKeyStore provider
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
E/AffinityControl( 5571): AffinityControl: registerfunction enter
W/libprocessgroup(  855): failed to open /acct/uid_10138/pid_4535/cgroup.procs: No such file or directory
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/AndroidRuntime( 5571): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  855): inState():  stateMachine is null !!
V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  855): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  855): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  855): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 855  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  855): mDVFSHelper.acquire()
D/FocusedStackFrame(  855): Set to : 0
D/Launcher.HomeView( 1479): onPause
D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 5571): Shutting down VM
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/FeatureConfig( 5613): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/libpersona( 5643): KNOX_SDCARD checking this for 10374
D/LockPatternUtilsCache( 1170): value : false
I/libpersona( 5643): KNOX_SDCARD not a persona
E/Zygote  ( 5643): MountEmulatedStorage()
E/Zygote  ( 5643): v2
I/ActivityManager(  855): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5643 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/art     (  313): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 11.396ms
I/SurfaceFlinger(  249): id=12 createSurf (1x1),1 flag=404, Starting com.example.hello
E/SELinux ( 5643): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 260us total 9.586ms
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
W/ResourcesManager( 5613): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 8.874ms
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  855): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ResourcesManager( 5613): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 5643): TimaSignature is unavailable
D/ActivityThread( 5643): Added TimaKeyStore provider
I/MicrophoneInputStream( 1558): mic_close gfk@d3a6d2f
V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  855): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/ResourcesManager( 5613): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/Launcher.HomeView( 1479): onStop
W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/AudioPolicyManager(  287): stopInput() input 26
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2215): [237392/6] Surface widget pause on instance = 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2215): [237392/6] Surface widget visibility changed visibility = false on instance = 1
V/audio_hw_primary(  287): in_standby: enter
D/accuweather( 2215): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2215): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2215): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/ResourcesManager( 5613): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/HotwordRecognitionRnr( 1558): Hotword detection finished
I/HotwordRecognitionRnr( 1558): Stopping hotword detection.
D/SurfaceWidgetView( 1479): destroyHardwareResources():176798378
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  855): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/ResourcesManager( 5613): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  855): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2215): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2215): [KK AccuPhone]>>> SM:538 [0:0] onPause
W/ResourcesManager( 5613): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 5643): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/audio_hw_primary(  287): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  287): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  287): disable_audio_route: reset mixer path: audio-record
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  287): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): disable_audio_route: exit
V/audio_hw_primary(  287): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: DEC2 Volume
D/audio_route(  287): Setting mixer control: value: 0
D/audio_route(  287): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  287): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  287): Setting mixer control: value: 0
D/audio_route(  287): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): stop_input_stream: exit: status(0)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioPolicyManager(  287): releaseInput() 26
V/AudioPolicyManager(  287): closeInput(26)
V/audio_hw_primary(  287): adev_close_input_stream
V/audio_hw_primary(  287): in_standby: enter
V/audio_hw_primary(  287): in_standby: exit:  status(0)
E/audio_hw_primary(  287): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  287): releaseInput() exit
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Launcher( 1479): onTrimMemory. Level: 20
W/ResourcesManager( 5613): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/SurfaceWidgetView( 1479): destroyHardwareResources():176798378
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 5613): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 5613): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5613): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 5613): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5613): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 5613): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 5613): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ResourcesManager( 5613): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 5613): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager( 5613): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/WebViewFactory( 5643): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5643): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/ResourcesManager( 5613): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 5613): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/LibraryLoader( 5643): Loading: webviewchromium
I/LibraryLoader( 5643): Time to load native libraries: 3 ms (timestamps 1843-1846)
I/LibraryLoader( 5643): Expected native library version number "",actual native library version number ""
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/WebViewChromiumFactoryProvider( 5643): Binding Chromium to main looper Looper (main, tid 1) {318a78f2}
I/LibraryLoader( 5643): Expected native library version number "",actual native library version number ""
I/chromium( 5643): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5643): Initializing chromium process, renderers=0
W/art     ( 5643): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/chromium( 5643): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 5643): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5643): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5643): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/Adreno-EGL( 5643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5643): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5643): Build Date: 03/03/15 Tue
I/Adreno-EGL( 5643): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 5643): Remote Branch: 
I/Adreno-EGL( 5643): Local Patches: 
I/Adreno-EGL( 5643): Reconstruct Branch: 
D/BluetoothAdapter( 5643): 100363075: getState() :  mService = null. Returning STATE_OFF
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/chromium( 5643): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5643): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/art     ( 5643): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5643): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SA      ( 5006): [PMR] Received action : android.intent.action.PACKAGE_ADDED
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
I/SA      ( 5006): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 5006): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10374 extra.user_handle.:0 ]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SystemWebViewEngine( 5643): CordovaWebView is running on device made by: samsung
I/ActivityManager(  855): Killing 4550:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/art     ( 5643): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5643): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Mms/FreeMessageReceiver( 5170): onReceive, action : android.intent.action.PACKAGE_ADDED
W/libprocessgroup(  855): failed to open /acct/uid_10012/pid_4550/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5686): MountEmulatedStorage()
E/Zygote  ( 5686): v2
D/Mms/FreeMessageReceiverService( 5170): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
I/libpersona( 5686): KNOX_SDCARD checking this for 10051
I/libpersona( 5686): KNOX_SDCARD not a persona
D/Mms/FreeMessageReceiverService( 5170): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager(  855): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5686 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 5686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5686): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 5686): TimaSignature is unavailable
V/BitmapFactory( 5494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
D/ActivityThread( 5686): Added TimaKeyStore provider
D/Activity( 5643): performCreate Call secproduct feature valuefalse
D/Activity( 5643): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/OpenGLRenderer( 5643): Render dirty regions requested: true
D/ActivityManager(  855): post active user change for 0
D/KnoxTimeoutHandler(  855): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  855): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5686): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/NotifUtils( 5494): Account: 61035162 vibrate: false
I/NotifUtils( 5494): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
W/ResourcesManager( 5686): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5686): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/SurfaceFlinger(  249): id=13 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OpenGLRenderer( 5643): Initialized EGL, version 1.4
I/OpenGLRenderer( 5643): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 5643): Enabling debug mode 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SecContentProvider2(  855): uri = 14 selection = getSealedState
D/SecContentProvider2(  855): mCursor = null
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|1729800001|null|10114
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
I/ValidateNoPeople(  855): Executing: validation for: 0|com.google.android.gm|1729800001|null|10114
V/AudioPolicyManager(  287): getOutputsForDevice device 0002 -> 0002
I/AudioService(  855): getStreamVolume 5 index 110
D/LightsService(  855): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 855) 
D/LightsService(  855): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  855): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  855): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 1170): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/SQLiteLog( 1777): (284) automatic index on sqlite_sq_AF228B00(STAT_DATA_ID)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  855): Displayed com.example.hello/.MainActivity: +700ms
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KnoxNotification( 1170): ----- inflateViews : modified KnoxViewLocal -----
I/art     (  855): Explicit concurrent mark sweep GC freed 18386(1249KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 1.247ms total 108.114ms
D/InputMethodManagerService(  855): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/SecContentProvider2(  855): uri = 14 selection = getSealedState
D/SecContentProvider2(  855): mCursor = null
D/PersonaManager( 1170): PersonaID is invalid or persona doesn't exists. : 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PhoneStatusBar( 1170): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@10783f92
D/SecContentProvider2(  855): uri = 14 selection = getSealedState
D/SecContentProvider2(  855): mCursor = null
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
D/MyFiles ( 5686): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|-2100714965|null|10114
D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/TactileAssist(  855): enable value -1
I/TactileAssist(  855): internal enable value -1
I/TactileAssist(  855): intensity value -1
I/TactileAssist(  855): saveAppList value true
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ValidateNoPeople(  855): final affinity: 0.0
I/ValidateNoPeople(  855): Executing: validation for: 0|com.google.android.gm|-2100714965|null|10114
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/TactileAssist(  855): List of disabled apps :
I/TactileAssist(  855): de.zalando.mobile
E/installd(  290): system dir 0 : /system/app/
E/installd(  290): system dir 1 : /system/priv-app/
E/installd(  290): system dir 2 : /vendor/app/
E/installd(  290): system dir 3 : /oem/app/
I/Timeline( 5643): Timeline: Activity_idle id: android.os.BinderProxy@264f02a2 time:42409
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2(  855): uri = 14 selection = getSealedState
D/SecContentProvider2(  855): mCursor = null
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5723): MountEmulatedStorage()
I/libpersona( 5723): KNOX_SDCARD checking this for 10058
E/Zygote  ( 5723): v2
I/libpersona( 5723): KNOX_SDCARD not a persona
I/ActivityManager(  855): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5723 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
I/chromium( 5643): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5643): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/SELinux ( 5723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 5723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
E/SELinux ( 5723): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|-913293406|null|10114
I/ValidateNoPeople(  855): final affinity: 0.0
D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
I/ValidateNoPeople(  855): final affinity: 0.0
D/SecContentProvider2(  855): uri = 14 selection = getSealedState
D/SecContentProvider2(  855): mCursor = null
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/CustomFrequencyManagerService(  855): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 855  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  855): mDVFSHelper.release()
I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{d7cd5b3 u0 com.example.hello/.MainActivity t11} time:42491
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/CustomFrequencyManagerService(  855): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 855  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 5723): TimaSignature is unavailable
D/ActivityThread( 5723): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PackageManager(  855): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|-865450363|null|10114
I/ValidateNoPeople(  855): final affinity: 0.0
D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (6/8)
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (-2/8)
D/SecContentProvider2(  855): uri = 14 selection = getSealedState
D/SecContentProvider2(  855): mCursor = null
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
E/Adreno-ES20( 5643): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5643): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/ResourcesManager( 5723): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 5723): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
D/JsMessageQueue( 5643): Set native->JS mode to OnlineEventsBridgeMode
I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|-633420634|null|10114
I/ValidateNoPeople(  855): final affinity: 0.0
D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  855): uri = 14 selection = getSealedState
D/SecContentProvider2(  855): mCursor = null
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
,D/Compatibility( 5723): onReceive() it will make start service
,D/Compatibility( 5723): onHandleIntent()
,D/Compatibility( 5723): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10374, android.intent.extra.user_handle=0}]
,D/Compatibility( 5723): found: 2
,D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,D/Compatibility( 5723): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5723): skipping ResolveInfo{3bdafc66 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|438982678|null|10114
I/ValidateNoPeople(  855): final affinity: 0.0
,D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
D/Compatibility( 5723): considering ResolveInfo{1208bba7 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5723): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5723): enabling receiver ResolveInfo{210ef854 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/art     ( 1170): Explicit concurrent mark sweep GC freed 36002(1644KB) AllocSpace objects, 3(319KB) LOS objects, 30% free, 35MB/51MB, paused 438us total 99.413ms
,D/Compatibility( 5723): enabling receiver ResolveInfo{80183fd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5723): enabling receiver ResolveInfo{318a78f2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/SecContentProvider2(  855): uri = 14 selection = getSealedState
,D/SecContentProvider2(  855): mCursor = null
I/UpdateIcingCorporaServi( 1558): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
,D/Compatibility( 5723): enabling receiver ResolveInfo{5fb6b43 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 5528): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,D/Compatibility( 5723): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|1919793178|null|10114
I/ValidateNoPeople(  855): final affinity: 0.0
D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
E/Zygote  ( 5745): MountEmulatedStorage()
I/libpersona( 5745): KNOX_SDCARD checking this for 10086
E/Zygote  ( 5745): v2
I/libpersona( 5745): KNOX_SDCARD not a persona
I/ActivityManager(  855): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=5745 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5745): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  855): uri = 14 selection = getSealedState
,D/SecContentProvider2(  855): mCursor = null
D/SecContentProvider2(  855): KnoxCustomManagerService offline: service is not available
,D/TimaKeyStoreProvider( 5745): TimaSignature is unavailable
,D/ActivityThread( 5745): Added TimaKeyStore provider
,I/chromium( 5643): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5643): 
,D/ResourcesManager( 5745): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 1887): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ApplicationPolicy(  855): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  855): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  855): Validating: 0|com.google.android.gm|2046740944|null|10114
,I/ValidateNoPeople(  855): final affinity: 0.0
D/WindowManager(  855): showStatusBarByNotification() mOpenByNotification=false
,I/ActivityManager(  855): Killing 4573:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  855): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 855  tag : ACTIVITY_RESUME_BOOSTER@10
,D/jxcore_app_log( 5643): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358540544
,D/JX-Cordova( 5643): jxcore cordova android initializing
,W/libprocessgroup(  855): failed to open /acct/uid_10143/pid_4573/cgroup.procs: No such file or directory
,D/PushModule( 5745): [PushClientApplication] (main) PushClientApplication.onCreate()
I/PushModule( 5745): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 5745): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 5745): [1][isApplicationInstalled] com.android.mms was installed
,W/jxcore-log( 5643): Initializing JXcore engine
W/jxcore-log( 5643): JXcore engine is ready
,W/jxcore-log( 5643): Starting JXcore engine
,W/ContextImpl( 5745): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  855): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 5745): [1][a] ChatONV isn't installed.
,D/ChatON  ( 5745): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5768): MountEmulatedStorage()
E/Zygote  ( 5768): v2
I/libpersona( 5768): KNOX_SDCARD checking this for 10098
I/libpersona( 5768): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5768 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 4402:com.android.vending/u0a30 (adj 15): bgCount ##41
,E/auditd  ( 2026): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  855): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  855): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,I/SELinux ( 5768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5768): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5768): TimaSignature is unavailable
,D/ActivityThread( 5768): Added TimaKeyStore provider
,D/ResourcesManager( 5768): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/libprocessgroup(  855): failed to open /acct/uid_10030/pid_4402/cgroup.procs: No such file or directory
,W/jxcore-log( 5643): Platform android
W/jxcore-log( 5643): 
,W/jxcore-log( 5643): Process ARCH arm
W/jxcore-log( 5643): 
,I/jxcore-log( 5643): JXcore Cordova bridge is ready!
I/jxcore-log( 5643): 
,W/jxcore-log( 5643): JXcore engine is started
,D/DocsApplication( 5768): Installing DEX configuration.
,D/ResourcesManager( 1558): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/UpdateIcingCorporaServi( 1558): UpdateCorporaTask done [took 492 ms] updated apps [took 492 ms] 
,D/DexInstaller( 5768): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 5768): Provided clientMode=RELEASE, packageInfo=PackageInfo{1944dcc1 com.google.android.apps.docs}
,E/jxcore-log( 5643): >> samsung-SM-G900F
E/jxcore-log( 5643): 
,I/jxcore-log( 5643): Total memory 1787449344
I/jxcore-log( 5643): 
,I/jxcore-log( 5643): Free memory 45260800
I/jxcore-log( 5643): 
I/jxcore-log( 5643): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5643): 
I/jxcore-log( 5643): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5643): 
,I/jxcore-log( 5643): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5643): 
,I/jxcore-log( 5643): Size 1080 1920
I/jxcore-log( 5643): 
,I/jxcore-log( 5643): Screen Brightness 134
I/jxcore-log( 5643): 
,E/jxcore-log( 5643): Dummy Error Log.
E/jxcore-log( 5643): 
,D/TAG     ( 5768): onCreate()
,D/CrossAppStateProvider( 5768): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/SMD     (  280): DCD ON
,E/Watchdog(  855): !@Sync 1
,D/SettingsProvider(  855): name = audio_safe_volume_state
,I/jxcore-log( 5643): getBuffer is called!!!!
I/jxcore-log( 5643): 
,D/PackageManager(  855): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  855): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  855): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 1479): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/RegisteredServicesCache( 1467): empty dynamic service
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,V/BitmapFactory( 1479): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_settings_icon.png
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/SecContentProvider2(  855): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  855): mCursor = null
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,D/BackupManagerService(  855): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  855): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,E/Zygote  ( 5803): MountEmulatedStorage()
E/Zygote  ( 5803): v2
I/libpersona( 5803): KNOX_SDCARD checking this for 10099
I/libpersona( 5803): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=5803 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 4594:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux ( 5803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/SELinux ( 5803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BackupManagerService(  855): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/GAV2    ( 5768): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5803): TimaSignature is unavailable
,V/BackupManagerService(  855): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/ActivityThread( 5803): Added TimaKeyStore provider
V/BackupManagerService(  855): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@21e3d54f
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 5803): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,W/ResourcesManager( 5803): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  855): failed to open /acct/uid_10017/pid_4594/cgroup.procs: No such file or directory
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/GmsNetworkLocationProvi( 1601): DISABLE
,I/GCoreNlp( 1601): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/[CarMode]( 5803): [DLApplication]-onCreate: Applicatino Started!
,D/LocationProviderProxy(  855): applying state to connected service
,D/LocationProviderProxy(  855): applying state to connected service
,D/SampleAppCoreManager( 5803): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 5803): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5828): MountEmulatedStorage()
E/Zygote  ( 5828): v2
I/libpersona( 5828): KNOX_SDCARD checking this for 10033
I/libpersona( 5828): KNOX_SDCARD not a persona
,I/SELinux ( 5828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  855): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=5828 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5828): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5828): TimaSignature is unavailable
,D/ActivityThread( 5828): Added TimaKeyStore provider
,D/ResourcesManager( 5828): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 5828): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 5768): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/System.out( 5828): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 5828): Inside WakeupProvider
,E/DatabaseUtils( 5828): Writing exception to parcel
E/DatabaseUtils( 5828): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5828): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5828): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5828): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5828): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5828): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5828): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5828): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5828): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5828): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5828): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 5803): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 5828): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,W/System.err( 5803): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5803): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 5803): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 5803): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 5803): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 5803): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 5803): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 5803): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5803): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5803): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5803): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5803): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5803): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 5828): Writing exception to parcel
E/DatabaseUtils( 5828): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5828): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5828): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5828): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5828): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5828): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5828): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5828): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5828): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5828): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5828): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 5803): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 5803): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5803): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 5803): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 5803): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 5803): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5803): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5803): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5803): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5803): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5803): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 5803): [DLApplication]-Init Called!:false
E/[CarMode]( 5803): [DLApplication]-Init Started!:true
I/[CarModeFW]( 5803): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 5803): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 5803): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 5803): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 5803): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 5803): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 5803): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 5803): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 5803): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 5803): ### android.os.Looper::loop(145)
I/[CarModeFW]( 5803): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 5803): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 5803): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 5803): ### com.android.internal.os.ZygoteInit::main(1194)
D/BluetoothAdapter( 5828): 230533939: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5828): 230533939: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5828): 230533939: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 5828): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
I/MessageDataHandler( 5803): initialize
D/[CarModeFW]( 5803): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 5803): CDH-initiazlieCaches : after sync
,D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 5803): CDH-ContactDataHandler initiazlieCaches time : 15
D/[CarModeFW]( 5803): CDH-initiazlieCaches : end sync
D/BluetoothAdapter( 5803): 919326625: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5803): 919326625: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 5803): DrivingManager-initialize...
I/SensorService(  855): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  855): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  855): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/VlingoApplication( 5828): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 5828): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 5803): Need to enable context aware info
,V/MediaPlayer-JNI( 5803): native_setup
V/MediaPlayer( 5803): constructor
,V/MediaPlayer( 5803): setListener
,E/MediaPlayer-JNI( 5803): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 5803): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 5803): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 5803): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1449498934738
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1449498934738
,D/[CarMode]( 5803): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1449498934738
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1449498934738
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1449498934738
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1449498934739
,D/TP/SmsProvider( 1473): query,matched:2, calling pid = 5803
,D/TP/SmsProvider( 1473): query,matched:2, calling pid = 5803
,D/TP/SmsProvider( 1473): match 2:Elapsed time : 0.098 ms
D/TP/SmsProvider( 1473): match 2:Elapsed time : 0.736 ms
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
I/[CarMode]( 5803): [LogNotNull]-Package name is: com.google.android.apps.maps
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5861): MountEmulatedStorage()
E/Zygote  ( 5861): v2
I/libpersona( 5861): KNOX_SDCARD checking this for 10003
I/libpersona( 5861): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=5861 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/[CarMode]( 5803): [DLApplication]-Init End!:true
,I/SELinux ( 5861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 5803):  getInboxList smsCursor : 40
,I/SELinux ( 5861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5861): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsProvider( 1473): Query uri=content://mms/inbox, match=2, calling pid = 5803
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5876): MountEmulatedStorage()
E/Zygote  ( 5876): v2
I/libpersona( 5876): KNOX_SDCARD checking this for 10020
I/libpersona( 5876): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=5876 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 5876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TimaKeyStoreProvider( 5861): TimaSignature is unavailable
E/SELinux ( 5876): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/ActivityThread( 5861): Added TimaKeyStore provider
D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsProvider( 1473): Query uri=content://mms, match=0, calling pid = 5803
,D/MessageDataHandler( 5803):  getInboxList mmsCursor : 60
,D/TimaKeyStoreProvider( 5876): TimaSignature is unavailable
,D/ActivityThread( 5876): Added TimaKeyStore provider
,D/[CarModeFW]( 5803): RecommendHandler-selection = type = '3'
,D/[CarMode]( 5803): [DLApplication]-GooglePlayServices SUCCESS.
,E/[CarMode]( 5803): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/MessageDataHandler( 5803): getUnreadMessageCount :0
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 113
,D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
,D/ResourcesManager( 5861): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/MessageDataHandler( 5803):  getInboxList mms,sms cursor join : 17
D/[CarModeFW]( 5803): RecommendHandler-selection = type = '3'
,I/UpdateManagerReceiver( 5803): Intent : android.intent.action.PACKAGE_ADDEDMon Dec 07 15:35:34 GMT+01:00 2015
,D/TP/MmsSmsProvider( 1473): query,matched:0, calling pid = 5803
V/TP/MmsSmsProvider( 1473): getSimpleConversations entered.
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1473): match 0:Elapsed time : 1.996 ms
D/ResourcesManager( 5876): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,E/Zygote  ( 5892): MountEmulatedStorage()
E/Zygote  ( 5892): v2
I/libpersona( 5892): KNOX_SDCARD checking this for 1000
I/libpersona( 5892): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5892 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 4876:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,I/SELinux ( 5892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5892): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 5803): PushMessageService-onCreate
,I/ActivityManager(  855): Killing 4673:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,D/UserAnalysis.PlaceProvider( 5861): PlaceProvider onCreate()
,I/ActivityManager(  855): Killing 4956:com.android.email/u0a163 (adj 15): bgCount ##42
,I/ActivityManager(  855): Killing 4946:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##43
,D/TP/MmsSmsProvider( 1473): query,matched:13, calling pid = 5803
,D/TP/MmsSmsProvider( 1473): match 13:Elapsed time : 1.571 ms
,D/[CarModeFW]( 5803): PushMessageManager-onServiceConnected
,D/[CarModeFW]( 5803): PushMessageService-registerPushMessageServiceListener
,D/TimaKeyStoreProvider( 5892): TimaSignature is unavailable
,D/ActivityThread( 5892): Added TimaKeyStore provider
,D/MessageDataHandler( 5803):  getInboxList address cursor : 32
,D/ResourcesManager( 5892): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/FaceInterface( 5321): startFaceScan() : going on
D/FaceInterface( 5321): startFaceScan() is called.
,D/ContentApp( 1225): startScan() is called.
,W/ContextImpl( 5892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,D/FaceValue( 1225): mSleepTime: 800
,D/FaceValue( 1225): mMaxThreadNum: 2
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1225): startScan() is end.
,W/libprocessgroup(  855): failed to open /acct/uid_10037/pid_4876/cgroup.procs: No such file or directory
,D/ContentApp( 1225): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1225): isNeedToRestore : start
,E/Zygote  ( 5909): MountEmulatedStorage()
E/Zygote  ( 5909): v2
I/libpersona( 5909): KNOX_SDCARD checking this for 10112
I/libpersona( 5909): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5909 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecureDbManager( 5861): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5861): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 5861): Create SecureDbHelper
,I/SELinux ( 5909): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5909): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5909): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 5892): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/FaceInterface( 5321): startFaceScan() : going on
,D/FaceInterface( 5321): startFaceScan() is called.
,E/FilterInstaller( 5892): There is no requred permission
,D/ContentApp( 1225): startScan() is called.
D/ContentApp( 1225): face_restore mRestartScanner 1 FINISHED_TYPE: 3
D/ContentApp( 1225): startScan() is end.
,I/ActivityManager(  855): Killing 5051:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,I/art     (  855): Explicit concurrent mark sweep GC freed 35759(2002KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 3.184ms total 103.750ms
,D/TimaKeyStoreProvider( 5909): TimaSignature is unavailable
D/ActivityThread( 5909): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 5861): onCreate()
,I/SQLiteSecureOpenHelper( 5861): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 5861): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 5861): Open Place.db in secure mode
D/TP/MmsSmsProvider( 1473): query,matched:0, calling pid = 5803
V/TP/MmsSmsProvider( 1473): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1473): match 0:Elapsed time : 0.835 ms
,D/MessageDataHandler( 5803):  getInboxList thread cursor : 126
,D/MessageDataHandler( 5803):  thread, addr result: 4
I/[CarModeFW]( 5803): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 331
I/[CarModeFW]( 5803): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 331
,D/ResourcesManager( 5909): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/SQLiteSecureOpenHelper( 5861): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 5861): ...getDatabaseLocked(b,b,pwd)
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 355
,D/ResourcesManager( 4386): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/libprocessgroup(  855): failed to open /acct/uid_10046/pid_4673/cgroup.procs: No such file or directory
,D/ContentApp( 1225): face_restore mRestartScanner 2 FINISHED_TYPE: 3
D/FaceScanner( 1225): isNeedToRestore : start
D/PackageIntentReceiver( 5909): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5909): Not GearManger package! 
W/libprocessgroup(  855): failed to open /acct/uid_10163/pid_4956/cgroup.procs: No such file or directory
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_4946/cgroup.procs: No such file or directory
,D/[CarModeFW]( 5803): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 5803): MyPlaceProvider-=============
D/[CarModeFW]( 5803): MyPlaceProvider-=============
D/[CarModeFW]( 5803): MyPlaceProvider-=============
,D/[CarModeFW]( 5803): MyPlaceProvider-=============
D/[CarModeFW]( 5803): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 5803): MyPlaceProvider-==============
D/[CarModeFW]( 5803): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5803): MyPlaceProvider-==============
,D/[CarModeFW]( 5803): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5803): MyPlaceProvider-==============
D/[CarModeFW]( 5803): MyPlaceProvider-latitude is not valid
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5927): MountEmulatedStorage()
E/Zygote  ( 5927): v2
I/libpersona( 5927): KNOX_SDCARD checking this for 10118
I/libpersona( 5927): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=5927 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 4627:com.android.calendar/u0a150 (adj 15): bgCount ##41
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Missed Call : 265
,I/art     (  313): Explicit concurrent mark sweep GC freed 8748(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 308us total 13.674ms
,W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.955ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.419ms
,I/SELinux ( 5927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5927): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  855): failed to open /acct/uid_10149/pid_5051/cgroup.procs: No such file or directory
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 418
,D/[CarMode]( 5803): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ff9ad3f, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@8f6539c9] LOCATIONS
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Favorite : 48
,D/TimaKeyStoreProvider( 5927): TimaSignature is unavailable
,D/ActivityThread( 5927): Added TimaKeyStore provider
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  855): failed to open /acct/uid_10150/pid_4627/cgroup.procs: No such file or directory
,E/Zygote  ( 5942): MountEmulatedStorage()
E/Zygote  ( 5942): v2
I/libpersona( 5942): KNOX_SDCARD checking this for 10046
I/libpersona( 5942): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5942 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5942): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 5803): -[snowdeer] Rec : CallLog : 44
,D/ResourcesManager( 5927): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 5927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5942): TimaSignature is unavailable
,D/ActivityThread( 5942): Added TimaKeyStore provider
,I/ActivityManager(  855): Killing 4280:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,D/ResourcesManager( 5942): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 5942): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SSRM:m  (  855): SIOP:: AP = 460, PST = 428, CUR = 300
,D/MagazineService Version( 5927): Magazine-Administrator: 11
,D/MagazineService Version( 5927): Magazine-Provider: 14
,I/CalendarProvider2( 5942): CalendarProvider2.onCreate() called
,D/MagazineService Version( 5927): Magazine-Channel: 14
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5958): MountEmulatedStorage()
E/Zygote  ( 5958): v2
I/libpersona( 5958): KNOX_SDCARD checking this for 10118
I/libpersona( 5958): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=5958 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 5927): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5927): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,I/SELinux ( 5958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  855): failed to open /acct/uid_10117/pid_4280/cgroup.procs: No such file or directory
,E/SELinux ( 5958): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 5927): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 5972): MountEmulatedStorage()
,E/Zygote  ( 5972): v2
I/libpersona( 5972): KNOX_SDCARD checking this for 1000
I/libpersona( 5972): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 5927): [onHandleIntent] Send broadcast to (com.example.hello).
,I/ActivityManager(  855): Waited long enough for: ServiceRecord{519abdc u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/SELinux ( 5972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TimaKeyStoreProvider( 5958): TimaSignature is unavailable
,I/SELinux ( 5972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ActivityThread( 5958): Added TimaKeyStore provider
E/SELinux ( 5972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  855): Killing 5086:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 5459): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/TimaKeyStoreProvider( 5972): TimaSignature is unavailable
D/ResourcesManager( 5958): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
D/ActivityThread( 5972): Added TimaKeyStore provider
,W/ResourcesManager( 5958): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 5972): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/HeadlinesChannelApplication( 5958): [onCreate]
,D/Headlines( 5958): Breath.onCreate
,D/HeadlinesCardManager( 5958): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5958): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 5958): CardProvider Library : 14
,D/MagazineService::CardProviderContentProvider( 5927): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 5927): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5958): registerCardProvider: provider already exists.
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_5086/cgroup.procs: No such file or directory
,I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 761
,D/Headlines( 5958): HeadlinesDataCenter ctor
D/Headlines( 5958): HeadlinesDataCenter. mLocale = en_US
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Schedule : 285
,I/[CarModeFW]( 5803): -[snowdeer] Rec : During DL app : 1
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 5803): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 768
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,D/HeadlinesChannelUtil( 5958): getCountryCode(): countryCode = DE
,D/HeadlinesCardManager( 5958): HeadlinesCardManager : constructor welcome :YES
,E/Zygote  ( 5995): MountEmulatedStorage()
,E/Zygote  ( 5995): v2
I/libpersona( 5995): KNOX_SDCARD checking this for 1000
I/libpersona( 5995): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5995): TimaSignature is unavailable
,D/ActivityThread( 5995): Added TimaKeyStore provider
,D/ResourcesManager( 5995): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 5995): Received: android.intent.action.PACKAGE_ADDED
,E/Zygote  ( 6011): MountEmulatedStorage()
,E/Zygote  ( 6011): v2
I/libpersona( 6011): KNOX_SDCARD checking this for 10135
I/libpersona( 6011): KNOX_SDCARD not a persona
,W/ContextImpl( 5995): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6011 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 5120:com.sec.factory/1000 (adj 15): bgCount ##41
,I/SELinux ( 6011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6011): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 5995): Enter Oncreate
,D/AcmsServiceMonitor( 5995): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5995): creating AcmsCore
,D/AcmsCore( 5995): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5995): AcmsCore
,D/AcmsCore( 5995): init
,D/AcmsCore( 5995): Looper handler is not null
I/GAV2    ( 5494): Thread[GAThread,5,main]: No campaign data found.
D/AcmsCore( 5995): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 5995): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5995): Incrementing - Counter value: 1
D/AcmsCore( 5995): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 5995): onStartCommand
D/AcmsCertificateMngr( 5995): AcmsCertificateMngr
,D/AcmsRevocationMngr( 5995): AcmsRevocationMngr
D/TimaKeyStoreProvider( 6011): TimaSignature is unavailable
,D/ActivityThread( 6011): Added TimaKeyStore provider
,D/AcmsService( 5995): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5995): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5995): Incrementing - Counter value: 2
D/AcmsService( 5995): Incremented Counter Value : onStartCommand
,D/ActivityThread( 5995): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ResourcesManager( 6011): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_5120/cgroup.procs: No such file or directory
W/ResourcesManager( 6011): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/System.out( 5828): INFO:Resource not found:/Common.properties Using default values
,D/AcmsService( 5995): Inside handle Intent
,D/AcmsService( 5995): App added - package name: com.example.hello
D/AcmsCore( 5995): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5995): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5995): Incrementing - Counter value: 3
D/AcmsCore( 5995): Incremented Counter Value: postToAcmsCoreHandler =>2
,D/AcmsService( 5995): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5995): Decrementing - Counter value: 2
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:85000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:85000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 85.0 degC
,I/ThermalEngine(  307): ACTION: OPT_CURR_REQ 1
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6044): MountEmulatedStorage()
E/Zygote  ( 6044): v2
I/libpersona( 6044): KNOX_SDCARD checking this for 10166
I/libpersona( 6044): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=6044 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GLSActivity( 1672): [ac] getting account id
,D/TimaKeyStoreProvider( 6044): TimaSignature is unavailable
,D/ActivityThread( 6044): Added TimaKeyStore provider
,I/GLSUser ( 1672): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/ResourcesManager( 6044): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 6044): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 6044): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6060): MountEmulatedStorage()
E/Zygote  ( 6060): v2
I/libpersona( 6060): KNOX_SDCARD checking this for 10170
I/libpersona( 6060): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6060 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 6060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6060): TimaSignature is unavailable
,D/ActivityThread( 6060): Added TimaKeyStore provider
,D/ResourcesManager( 6060): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 6060): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6078): MountEmulatedStorage()
E/Zygote  ( 6078): v2
I/libpersona( 6078): KNOX_SDCARD checking this for 10030
I/libpersona( 6078): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6078 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 4882:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,I/SELinux ( 6078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6078): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6078): TimaSignature is unavailable
,D/ActivityThread( 6078): Added TimaKeyStore provider
,W/libprocessgroup(  855): failed to open /acct/uid_10078/pid_4882/cgroup.procs: No such file or directory
,D/ResourcesManager( 6078): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/CalendarProvider2( 5942): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  855): Killing 5219:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/Finsky  ( 6078): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/libprocessgroup(  855): failed to open /acct/uid_10025/pid_5219/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 74.0 degC
,I/ThermalEngine(  307): ACTION: OPT_CURR_REQ 0
,E/SMD     (  280): DCD ON
,D/Finsky  ( 6078): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6114): MountEmulatedStorage()
E/Zygote  ( 6114): v2
I/libpersona( 6114): KNOX_SDCARD checking this for 10012
I/libpersona( 6114): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6114 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6114): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PowerManagerService(  855): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  855): Nap time (uid 1000)...
I/PowerManagerService(  855): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  855): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController(  855): getFinalBrightness : 1 -> 1
D/PowerManagerService(  855): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  855): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  855): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  855): setDeviceInteractive: 0
,D/InputManager-JNI(  855): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/InputManager-JNI(  855): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  855): handleSandman : startDream()
,D/InputManager-JNI(  855): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  855): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  855): handleSandman : startDreaming, but isDreaming false
,D/SContextService(  855): 	.unregisterCallback : 1, client=
D/SContextService(  855): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2139ebf5, Service = Auto Rotation, used = 1
,I/PowerManagerService(  855): Sleeping (uid 1000)...
D/PowerManagerService(  855): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  855): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  855): [input device light] handleInputDeviceLightOff
,D/TimaKeyStoreProvider( 6114): TimaSignature is unavailable
,W/Settings( 6078): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ActivityThread( 6114): Added TimaKeyStore provider
W/Settings( 6078): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,W/CAE     (  855): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  855): stop(ContextProvider.java:149)
,V/CAE     (  855): clear(AutoRotationRunner.java:182)
V/CAE     (  855): disable(AutoRotationRunner.java:171)
,I/CAE     (  855): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  855): SendSensorHubData: send data = -78, 7, 0, 0
,D/ResourcesManager( 6114): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  855): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  855): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
I/Adreno-EGL(  855): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  855): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  855): Build Date: 03/03/15 Tue
I/Adreno-EGL(  855): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  855): Remote Branch: 
I/Adreno-EGL(  855): Local Patches: 
I/Adreno-EGL(  855): Reconstruct Branch: 
,W/ResourcesManager( 6114): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6114): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/CAE     (  855): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  855): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  855): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  855): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  855): removeSContextService() : service = Auto Rotation
,D/SContextService(  855): ===== SContext Service List =====
D/SContextManager(  855):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@284afbd0, service=Auto Rotation
,D/KeyguardViewMediator( 1170): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1170): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1170): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1170): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3323): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3323): getDatabaseLocked(b,b,pwd)...
,I/CAE     (  855): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): timeout : 5000
,I/CAE     (  855): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  855): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
,D/SensorHubManager(  855): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  855): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/KeyguardViewMediator( 1170): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1170): handleNotifyScreenOff
,D/MotionRecognitionService(  855):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  855):  handler : SCREEN_ON end
,D/DisplayPowerController(  855): ColorFade: onAnimationStart
D/DisplayPowerController(  855): getFinalBrightness : 8 -> 0
,I/MultiDex( 6114): VM with version 2.1.0 has multidex support
I/MultiDex( 6114): install
,D/lights  (  855): lcd : 0 +
,D/DisplayPowerController(  855): getFinalBrightness : 8 -> 0
,I/MultiDex( 6114): VM has multidex support, MultiDex support library is disabled.
D/NotificationService(  855): ACTION_SCREEN_ON
D/LightsService(  855): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 855) 
,D/LightsService(  855): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  855): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  855): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ActivityManager(  855): Killing 5239:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=on
V/voice   (  287): voice_set_parameters: enter: screen_state=on
V/voice   (  287): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  287): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  287): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  287): adev_set_parameters: exit
,I/WifiNative-HAL(  855): startHal
,E/wifi    (  855): getStaticLongField sWifiHalHandle 0x950a67fc
D/wifi    (  855): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x102362
I/WifiNative-HAL(  855): Could not start hal
D/WifiStateMachine(  855): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  855): handleScreenStateChanged Exit: true
,I/SecExternalDisplayIntents_Java(  855): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
E/WifiStateMachine(  855): setSuspendOptimizations: 4 false
,E/WifiStateMachine(  855): mSuspendOptNeedsDisabled 4
,D/lights  (  855): lcd : 0 -
,D/Finsky  ( 6078): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/IpRemoteDisplayController(  855): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController(  855): Bridge Server is not available
,D/PackageBroadcastService( 1887): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1887): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/Finsky  ( 6078): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6078): [1] 2.run: Finished loading 1 libraries.
,W/libprocessgroup(  855): failed to open /acct/uid_10172/pid_5239/cgroup.procs: No such file or directory
,I/ConfigFetchService( 1887): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1887): launchTask
,D/PersonaManagerService(  855): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  855): MSG_ACTION_SCREEN_ON called
,D/Finsky  ( 6078): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PeopleContactsSync( 1887): CP2 sync disabled
,D/ChimeraCfgMgr( 1887): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/JNIHelp ( 6114): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Vision  ( 1887): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1887): Failed to find package metadata for com.example.hello
,D/Vision  ( 1887): No vision deps
,D/ResourcesManager( 1887): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
I/NfcService( 1467): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,E/Zygote  ( 6151): MountEmulatedStorage()
I/libpersona( 6151): KNOX_SDCARD checking this for 10040
E/Zygote  ( 6151): v2
I/libpersona( 6151): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6151 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/NfcService( 1467): call the applyRotuiing
,V/ConfigFetchTask( 1887): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UlE2AO6GNhfMd-QY61KSURC72ULmoP6v5H7TijaBctZZzh5yeWVV7oQd_ypLDW6kH-ACxfvm76Xpbhbb9rrITBeVO4GafXB3lG-e9YIzBDAhX0LdqGaU84ds9pVtBJu9xDy9SXK89kViYww2uTSk_WkTqsNMKFvUOkDtDTzZ95C-XO0tWsWH_BpqXZDdnfUriRUrj8HdeEDm9gOOXbslk2gmQx0n4HN5TXh0hZrWpIZtLoWv4
,I/SELinux ( 6151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6151): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/AcmsKeyStoreHelper( 5995):  getKeyStoreForApplication Enter
,D/DisplayPowerState(  855): !@ ColorFade entry
,D/DisplayPowerController(  855): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  855): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  855): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  855): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  855): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,W/ActivityThread( 6114): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6114): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e59f5bd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6114): Installed default security provider GmsCore_OpenSSL
E/LightSensor(  855): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/TimaKeyStoreProvider( 6151): TimaSignature is unavailable
,D/ActivityThread( 6151): Added TimaKeyStore provider
,D/SensorManager(  855): unregisterListener ::   
E/Sensors (  855): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  855): unregisterListener ::   
,I/GoogleURLConnFactory( 1887): Using platform SSLCertificateSocketFactory
,D/DisplayPowerController(  855): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  855): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  855): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  855): Display changed displayId=0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
,D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 6151): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/accuweather( 2215): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/accuweather( 2215): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2215): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2215): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2215): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2215): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/AcmsKeyStoreHelper( 5995): Key Store exist
I/AcmsKeyStoreHelper( 5995): Hence loading the keystore file
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SamsungIME( 1829): getNextShiftState() cursorCapsMode : 0
,D/SurfaceWidget.Renderer( 2215): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2215): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2215): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2215): [237392/6] SurfaceWidget drawing first frame
,I/SystemBroadcastReceiver( 5261): [#DCM#] [DCM_Performance] onReceive completed in time  1321 microsec. 
,I/SystemBroadcastReceiver( 5261): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 5261): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 5261): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/ConnectivityService(  855): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  855): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 855) 
,D/LightsService(  855): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,E/LightSensor(  855): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  855): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  855): turn on LED for charging
,I/CAE     (  855): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  855): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  855): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  855): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,D/SSRM:m  (  855): SIOP:: AP = 470, PST = 433, CUR = 300
D/X       (  855): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  855): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 5261): [#DCM#] [DCM_Performance] onReceive completed in time  64 microsec. 
,I/SystemBroadcastReceiver( 5261): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 5261): [#DCM#] onReceive action = EVENT_SIOP
,I/CAE     (  855): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 35, 37,
D/SensorHubManager(  855): SendSensorHubData: send data = -63, 14, 14, 35, 37
D/Sensorhubs(  297): sendContextData: -63, 14, 14, 35, 37
,D/ContentApp( 1225):  LEVEL : 0
,I/System.out( 1887): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1887): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1887): (HTTPLog)-Thread-243-280290456: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager(  855): Killing 5341:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,D/MotionRecognitionService(  855):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  855):  handler : SCREEN_OFF end 
,D/NotificationService(  855): ACTION_SCREEN_OFF
,I/SettingSearchManagerReceiver( 1473): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,I/SettingSearchManagerReceiver( 1473): addSearchInfoDB
I/WifiNative-HAL(  855): startHal
E/wifi    (  855): getStaticLongField sWifiHalHandle 0x950a67fc
D/wifi    (  855): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x1023a6
I/WifiNative-HAL(  855): Could not start hal
D/WifiStateMachine(  855): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  855): handleScreenStateChanged Exit: false
,D/LightsService(  855): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 855) 
D/LightsService(  855): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x12 | SvcLED(id=4) set On
,E/WifiStateMachine(  855): setSuspendOptimizations: 4 true
E/WifiStateMachine(  855): mSuspendOptNeedsDisabled 0
D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  287): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  287): adev_set_parameters: exit
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,W/ConfigFetchTask( 1887): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/libpersona( 6178): KNOX_SDCARD checking this for 10168
I/ConfigFetchService( 1887): fetch service done; releasing wakelock
I/libpersona( 6178): KNOX_SDCARD not a persona
I/ConfigFetchService( 1887): stopping self
E/Zygote  ( 6178): MountEmulatedStorage()
E/Zygote  ( 6178): v2
I/ActivityManager(  855): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6178 uid=10168 gids={50168, 9997} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 281us total 15.211ms
,I/SecExternalDisplayIntents_Java(  855): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  855): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  855): Bridge Server is not available
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 447us total 9.634ms
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  855): Excessive delay in setPowerMode(): 279ms
,D/PowerManagerService(  855): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  855): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL(  855): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  855): Invalid hint ID.
,I/QCOM PowerHAL(  855): Got set_interactive hint
,D/AcmsKeyStoreHelper( 5995):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5995): getKeyStoreForApplication success 
,D/AcmsCore( 5995): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 11.188ms
D/AcmsServiceMonitor( 5995): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5995): Decrementing - Counter value: 1
,D/AcmsCore( 5995): AcmsCore: ACMS_APP_INSTALLED
,I/SELinux ( 6178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/PowerManagerService(  855): [PWL] Off : 0s ago
I/PowerManagerService(  855): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/SELinux ( 6178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/PowerManagerService(  855): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  855): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=855, ws=WorkSource{10117}) (elapsedTime=17584)
I/PowerManagerService(  855): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1887, ws=null) (elapsedTime=13660)
I/PowerManagerService(  855): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2739)
I/PowerManagerService(  855): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2738)
I/PowerManagerService(  855): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  855): [PWL]     mDisplayReady : false
I/PowerManagerService(  855): [PWL]   PowerManagerService.Broadcasts: ref count=1
,E/SELinux ( 6178): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  855): failed to open /acct/uid_10002/pid_5341/cgroup.procs: No such file or directory
,D/DisplayPowerController(  855): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  855): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  855): [PWL] sb release: PowerManagerService.Display
D/AcmsCore( 5995): This is NOT a valid MirrorLink app
D/AcmsCore( 5995): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5995): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 5995): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5995): Counter value is 0: Stopping ACMS service
D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1170): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/AcmsServiceMonitor( 5995): getSvcCounter - Counter value: 0
D/AcmsService( 5995): Enter onDestroy
I/AcmsService( 5995): cleanUp(): inside service clean up
D/AcmsCore( 5995): AcmsCore: inside DeInit
D/AcmsCore( 5995): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5995): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5995): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5995): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5995): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5995): getSvcCounter - Counter value: 0
D/AcmsService( 5995): killing acms process
I/Process ( 5995): Sending signal. PID: 5995 SIG: 9
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1170): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  855): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  855): MSG_ACTION_SCREEN_OFF called
,D/TimaKeyStoreProvider( 6178): TimaSignature is unavailable
,D/ActivityThread( 6178): Added TimaKeyStore provider
,D/NfcService( 1467): call the applyRotuiing
,I/ActivityManager(  855): Process ACMS.Process (pid 5995)(adj 0) has died(83,571)
,D/ResourcesManager( 6178): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
,D/ResourcesManager( 6114): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/SettingSearchManagerReceiver( 1473): endInsert
,D/AssistantMenuSettingSearch( 5528): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5528): Make Setting DB
,D/STATUSBAR-PhoneStatusBar( 1170):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1170): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1170): dismissHelpPopup 
,D/accuweather( 2215): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2215): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2215): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ResourcesManager( 6114): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  855): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  855): waitForAlarm result :4
,D/LightsService(  855): [SvcLED]  onSensorChanged::light value = 1
,E/LightSensor(  855): Light old sensor_state 8704, new sensor_state : 8192 en : 0
I/SystemBroadcastReceiver( 5261): [#DCM#] [DCM_Performance] onReceive completed in time  136 microsec. 
,I/SystemBroadcastReceiver( 5261): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 5261): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 5261): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/SensorManager(  855): unregisterListener ::   
D/lights  (  855): led_pattern : 3 +
,D/lights  (  855): led_pattern : 3 -
D/LightsService(  855): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,W/ActivityManager(  855): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  855): SIOP:: AP = 470, PST = 438, CUR = 300
,W/ActivityManager(  855): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  855): [PWL] sb release: PowerManagerService.Broadcasts
,W/ContextImpl( 5528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
,I/art     (  855): Explicit concurrent mark sweep GC freed 34168(2MB) AllocSpace objects, 6(96KB) LOS objects, 30% free, 36MB/52MB, paused 1.388ms total 116.810ms
,D/Finsky  ( 6078): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6204): MountEmulatedStorage()
E/Zygote  ( 6204): v2
I/libpersona( 6204): KNOX_SDCARD checking this for 10117
I/libpersona( 6204): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6204 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/Finsky  ( 6078): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/SELinux ( 6204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6204): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6204): TimaSignature is unavailable
,D/ActivityThread( 6204): Added TimaKeyStore provider
,D/ResourcesManager( 6204): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Finsky  ( 6078): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1672): Explicit concurrent mark sweep GC freed 11557(625KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 447us total 39.745ms
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:a  (  855): DeviceInfo:: 000000000000
D/SSRM:a  (  855): SettingsAirViewInfo:: 000000000
,W/Finsky  ( 6078): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Babel   ( 6204): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6204): MmsConfig.loadMmsSettings
I/Babel   ( 6204): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
I/Babel   ( 6204): MmsConfig.loadFromDatabase
,E/Babel   ( 6204): canonicalizeMccMnc: invalid mccmnc 
,W/AudioCapabilities( 6204): Unsupported mime audio/evrc
,D/ResourcesManager( 6204): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/Babel   ( 6204): MmsConfig.loadFromResources
,W/AudioCapabilities( 6204): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6204): Unrecognized profile 2130706433 for video/avc
,E/Babel   ( 6204): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6204): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,W/Settings( 6204): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6204): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6204): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6204): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6204): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6204): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6204): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6204): Unsupported mime audio/evrc
,W/VideoCapabilities( 6204): Unsupported mime video/wvc1
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6204): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6204): Unsupported mime video/wvc1
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6204): Unsupported mime video/mp43
,W/VideoCapabilities( 6204): Unsupported mime video/sorenson
,I/VideoCapabilities( 6204): Unsupported profile 4 for video/mp4v-es
,D/BluetoothAdapter( 5643): disable()
,E/BluetoothManagerService(  855): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService(  855): New client listening to asynchronous messages
,I/WifiManager( 5643): packageName : com.example.hello
,D/SecContentProvider(  855): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  855): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  855): mCursor = null
,D/WifiService(  855): setWifiEnabled: false pid=5643, uid=10374
,E/WifiService(  855): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider(  855): name = wifi_on
E/SQLiteLog( 6204): (284) automatic index on conversation_participants_view(conversation_id)
,I/jxcore-log( 5643): ****TEST TOOK:  5039  ms ****
I/jxcore-log( 5643): 
,I/jxcore-log( 5643): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5643): 
,E/SQLiteLog( 6204): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6204): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6204): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6204): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  855): Killing 5261:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/GCM     ( 1672): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1672): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1887): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/AndroidRuntime( 6250): 
D/AndroidRuntime( 6250): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6250): CheckJNI is OFF
,D/AndroidRuntime( 6250): setted country_code = Germany
D/AndroidRuntime( 6250): setted countryiso_code = DE
D/AndroidRuntime( 6250): setted sales_code = DBT
D/AndroidRuntime( 6250): readGMSProperty: start
D/AndroidRuntime( 6250): readGMSProperty: already setted!!
,D/AndroidRuntime( 6250): readGMSProperty: end
D/AndroidRuntime( 6250): addProductProperty: start
,W/libprocessgroup(  855): failed to open /acct/uid_10004/pid_5261/cgroup.procs: No such file or directory
,D/WearableService( 5031): callingUid 10012, callindPid: 5031
,E/MDM     ( 1601): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1887): Restart initialization of location
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4490): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4490): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4490): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 4490): RegionGroup for  is null
,D/BluetoothManager( 4490): getConnectedDevices
,D/BluetoothManager( 4490): getConnectedDevices
,D/BluetoothManager( 4490): getConnectedDevices
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AffinityControl( 6250): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6250): Calling main entry com.android.commands.pm.Pm
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PackageManager(  855): START PACKAGE DELETE: observer{130262067}
D/PackageManager(  855): pkg{<packageName>}
D/PackageManager(  855): user{0}
D/PackageManager(  855): caller{2000}
D/PackageManager(  855): flags{3}
D/PersonaManagerService(  855): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  855): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  855): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  855): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  855): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  855): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  855): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  855): deletePackage- pkg:com.example.hello, edmuserId:-1
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ApplicationPolicy(  855): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  855): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  855): !@killApplicatoin: 10374, uninstall pkg
,I/ActivityManager(  855): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  855): Killing 5643:com.example.hello/u0a374 (adj 0): stop com.example.hello
,I/ActivityManager(  855):   Force finishing activity ActivityRecord{d7cd5b3 u0 com.example.hello/.MainActivity t11}
,D/FocusedStackFrame(  855): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WifiService(  855): Client connection lost with reason: 4
,W/PackageSettings(  855): Skipping PackageSetting{1a62649 com.test.thalitest/10367} due to missing metadata
,I/ActivityManager(  855): Force stopping com.example.hello appid=10374 user=0: pkg removed
,D/ConnectivityService(  855): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 4386): Explicit concurrent mark sweep GC freed 2846(160KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 326us total 15.718ms
,I/art     ( 5892): Explicit concurrent mark sweep GC freed 8499(395KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 302us total 29.201ms
,D/ResourcesManager(  855): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager( 1479): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,E/SamsungIME( 1829): mOCRHelper is null
,W/GeofencerStateMachine( 1601): Ignoring removeGeofence because network location is disabled.
,W/ResourcesManager( 1479): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1479): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1479): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/InputReader(  855): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1479): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1479): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1479): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Finsky  ( 6078): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/Finsky  ( 6078): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4490): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4490): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4490): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Finsky  ( 6078): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6078): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/DeviceConnectionService( 1601): client connected with version: 7571000
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/SecContentProvider2(  855): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  855): mCursor = null
,D/ResourcesManager( 6204): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/RegisteredServicesCache( 1467): empty dynamic service
,D/GCM     ( 1672): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ChimeraCfgMgr( 1887): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ChimeraCfgMgr( 1887): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/RCPManagerService(  855): PackageReceiver onReceive()
,I/HarmonyEASService(  855): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  855): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  855): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  855): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  855): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,I/Kids    ( 1887): [KidAccountFixer] No network connection
V/EnterpriseBillingPolicy(  855): uID is 10374
V/EnterpriseBillingPolicy(  855): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  855): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  855): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  855): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  855): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage(  855): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage(  855): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager( 6204): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6204): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6204): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6279): MountEmulatedStorage()
E/Zygote  ( 6279): v2
I/libpersona( 6279): KNOX_SDCARD checking this for 10036
I/libpersona( 6279): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6279 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TaskPersister(  855): removeObsoleteFile: deleting file=11_task.xml
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 24994(1473KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 18MB/30MB, paused 596us total 47.997ms
,I/SELinux ( 6279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6279): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService(  855): Package has changed for user 0
D/EnterpriseDeviceManagerService(  855): Admin package name: com.google.android.gms
,I/GAV2    ( 5768): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 6279): TimaSignature is unavailable
,D/ActivityThread( 6279): Added TimaKeyStore provider
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,V/JNIHelp ( 6204): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 6279): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/art     (  855): Explicit concurrent mark sweep GC freed 43342(3MB) AllocSpace objects, 8(128KB) LOS objects, 30% free, 36MB/52MB, paused 3.143ms total 347.485ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetView( 1479): destroyHardwareResources():176798378
,V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  855): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  855): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Launcher( 1479): onRestart, Launcher: 652279276
,D/Launcher( 1479): onStart, Launcher: 652279276
D/Launcher.HomeView( 1479): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2215): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2215): [237392/6] SurfaceWidget drawing first frame
W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Books/Books.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  855): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/StatusBarManagerService(  855): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/ActivityThread( 6204): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6204): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@54b9a94: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/ProviderInstaller( 6204): Installed default security provider GmsCore_OpenSSL
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/InputMethodManagerService(  855): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  855): Got RemoteException sending setActive(false) notification to pid 5643 uid 10374
,W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/PackageManager(  855): delete codoeFile: 
,I/Babel_RequestWriter( 6204): error sending REQ[fc:8; creat:1449484559807; type:bev-5360381]; took 1 ms (error code == 101)
,D/PackageManager(  855): result of delete: 1{130262067}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 6250): Shutting down VM
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{3fa6400b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:49270
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  855): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  855): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager( 6279): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 6279): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 6279): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 6279): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ResourcesManager( 6279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(  855): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  855): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 6279): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
,W/Resources(  855): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  855): clearDefaults: com.example.hello
,I/CrashAnrDetector(  855): onPackageRemoved : com.example.hello
,W/ResourcesManager( 6279): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6279): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,E/SMD     (  280): DCD ON
,I/EventHub(  855): Removing device '/dev/input/event4' due to inotify event
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6324): MountEmulatedStorage()
E/Zygote  ( 6324): v2
I/libpersona( 6324): KNOX_SDCARD checking this for 10149
I/libpersona( 6324): KNOX_SDCARD not a persona
,I/EventHub(  855): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  855): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6324 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 5302:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/SELinux ( 6324): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6324): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6324): TimaSignature is unavailable
,D/ActivityThread( 6324): Added TimaKeyStore provider
,I/EventHub(  855): Removing device '/dev/input/event6' due to inotify event
,D/ResourcesManager( 6324): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 6324): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6324): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/ContextImpl( 6324): Unable to create files subdir /data/data/com.sec.android.widgetapp.SPlannerAppWidget/cache
E/ActivityThread( 6324): Unable to setupGraphicsSupport due to missing cache directory
,W/libprocessgroup(  855): failed to open /acct/uid_10044/pid_5302/cgroup.procs: No such file or directory
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,D/AndroidRuntime( 6324): Shutting down VM
,F/libc    ( 6324): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73397151 in tid 6324 (lannerAppWidget)
,E/audit_log( 2026): File locking failed. error= Bad file number
E/audit_log( 2026): File locking failed. error= Bad file number
,E/Zygote  ( 6343): MountEmulatedStorage()
E/Zygote  ( 6343): v2
I/libpersona( 6343): KNOX_SDCARD checking this for 10150
I/libpersona( 6343): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6343 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/lowmemorykiller(  246): Error writing /proc/6324/oom_score_adj; errno=22
,I/ActivityManager(  855): Killing 5135:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,I/EventHub(  855): Removing device '/dev/input/event7' due to inotify event
,I/SELinux ( 6343): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 6343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Zygote  (  313): Process 6324 exited due to signal (7)
,I/ActivityManager(  855): Process com.sec.android.widgetapp.SPlannerAppWidget (pid 6324)(adj 9) has died(118,581)
,I/EventHub(  855): Removing device '/dev/input/event8' due to inotify event
,D/TimaKeyStoreProvider( 6343): TimaSignature is unavailable
,D/ActivityThread( 6343): Added TimaKeyStore provider
,D/ResourcesManager( 6343): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6343): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6343): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6343): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl( 6343): Unable to create files subdir /data/data/com.android.calendar/cache
,E/ActivityThread( 6343): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 6343): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0dd728b in tid 6343 (ndroid.calendar)
,F/libc    ( 6343): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2026): File locking failed. error= Bad file number
,I/EventHub(  855): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager(  855): Process com.android.calendar (pid 6343)(adj 0) has died(119,581)
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6359): MountEmulatedStorage()
,E/Zygote  ( 6359): v2
I/libpersona( 6359): KNOX_SDCARD checking this for 10150
I/libpersona( 6359): KNOX_SDCARD not a persona
,I/ActivityManager(  855): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.TaskAlertReceiver: pid=6359 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/Zygote  (  313): Process 6343 exited due to signal (7)
,I/EventHub(  855): Removing device '/dev/input/event10' due to inotify event
,W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/EventHub(  855): Removing device '/dev/input/event11' due to inotify event
,I/SELinux ( 6359): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,W/libprocessgroup(  855): failed to open /acct/uid_10126/pid_5135/cgroup.procs: No such file or directory
,E/SELinux ( 6359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6359): TimaSignature is unavailable
,D/ActivityThread( 6359): Added TimaKeyStore provider
,D/ResourcesManager( 6359): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6359): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl( 6359): Unable to create files subdir /data/data/com.android.calendar/cache
E/ActivityThread( 6359): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 6359): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0dd228b in tid 6359 (ndroid.calendar)
F/libc    ( 6359): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2026): File locking failed. error= Bad file number
,I/ActivityManager(  855): Process com.android.calendar (pid 6359)(adj 0) has died(119,581)
,F/libc    ( 4987): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e1ae74 in tid 4987 (om.sec.spp.push)
,F/libc    ( 4987): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2026): File locking failed. error= Bad file number
,I/Zygote  (  313): Process 6359 exited due to signal (7)
,I/ActivityManager(  855): Process com.sec.spp.push (pid 4987)(adj 0) has died(124,582)
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  855): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6374): MountEmulatedStorage()
E/Zygote  ( 6374): v2
I/libpersona( 6374): KNOX_SDCARD checking this for 10038
I/libpersona( 6374): KNOX_SDCARD not a persona
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  855): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=6374 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Zygote  (  313): Process 4987 exited due to signal (7)
,I/SELinux ( 6374): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6374): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6374): TimaSignature is unavailable
,D/ActivityThread( 6374): Added TimaKeyStore provider
,D/ResourcesManager( 6374): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 6374): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 6374): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 6374): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa1609756 in tid 6374 (emoteDlcProcess)
F/libc    ( 6374): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2026): File locking failed. error= Bad file number

```
