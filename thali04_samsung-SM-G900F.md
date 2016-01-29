#### Test 57617811ecc172f_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/Compatibility( 7176): enabling receiver ResolveInfo{e0444f7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7176): enabling receiver ResolveInfo{12decf64 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7176): enabling receiver ResolveInfo{3766f5cd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7176): enabling receiver ResolveInfo{1f494e82 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7176): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
--------- beginning of system
W/ContextImpl( 6166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7197): MountEmulatedStorage()
E/Zygote  ( 7197): v2
I/libpersona( 7197): KNOX_SDCARD checking this for 10097
I/libpersona( 7197): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7197 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  903): Killing 6040:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
D/ResourcesManager( 1556): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SELinux ( 7197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/UpdateIcingCorporaServi( 1556): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
I/SELinux ( 7197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7197): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7197): TimaSignature is unavailable
D/ActivityThread( 7197): Added TimaKeyStore provider
W/libprocessgroup(  903): failed to open /acct/uid_10093/pid_6040/cgroup.procs: No such file or directory
D/ResourcesManager( 7197): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/DocsApplication( 7197): Installing DEX configuration.
D/DexInstaller( 7197): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7197): Provided clientMode=RELEASE, packageInfo=PackageInfo{37566fb8 com.google.android.apps.docs}
D/TAG     ( 7197): onCreate()
D/CrossAppStateProvider( 7197): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
E/SMD     (  294): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3263): Disconnected process message: 10
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7217): 
D/AndroidRuntime( 7217): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7217): CheckJNI is OFF
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 7217): setted country_code = Poland
D/AndroidRuntime( 7217): setted countryiso_code = PL
D/AndroidRuntime( 7217): setted sales_code = XEO
D/AndroidRuntime( 7217): readGMSProperty: start
D/AndroidRuntime( 7217): readGMSProperty: already setted!!
D/AndroidRuntime( 7217): readGMSProperty: end
D/AndroidRuntime( 7217): addProductProperty: start
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Zygote  ( 7229): MountEmulatedStorage()
I/ActivityManager(  903): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7229 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
E/Zygote  ( 7229): v2
I/libpersona( 7229): KNOX_SDCARD checking this for 10098
I/libpersona( 7229): KNOX_SDCARD not a persona
I/ActivityManager(  903): Killing 6059:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
I/SELinux ( 7229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAV2    ( 7197): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 7229): TimaSignature is unavailable
D/ActivityThread( 7229): Added TimaKeyStore provider
D/ResourcesManager( 7229): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/libprocessgroup(  903): failed to open /acct/uid_10102/pid_6059/cgroup.procs: No such file or directory
W/ResourcesManager( 7229): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/AffinityControl( 7217): AffinityControl: registerfunction enter
D/AndroidRuntime( 7217): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  903): inState():  stateMachine is null !!
V/ApplicationPolicy(  903): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  903): mDVFSHelper.acquire()
D/FocusedStackFrame(  903): Set to : 0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7266): MountEmulatedStorage()
E/Zygote  ( 7266): v2
I/libpersona( 7266): KNOX_SDCARD checking this for 10191
I/libpersona( 7266): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7266 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SELinux ( 7266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AndroidRuntime( 7217): Shutting down VM
E/SELinux ( 7266): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/[CarMode]( 7229): [DLApplication]-onCreate: Applicatino Started!
D/TimaKeyStoreProvider( 7266): TimaSignature is unavailable
D/ActivityThread( 7266): Added TimaKeyStore provider
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  903): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  903): Display changed displayId=0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SampleAppCoreManager( 7229): SampleAppCoreManager VACVersion '2.2.0.11867'
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SurfaceWidgetView( 1513): destroyHardwareResources():826181319
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/VlingoAndroidCore( 7229): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SQLiteSecureOpenHelper( 3537): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3537): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
D/ResourcesManager( 7266): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  257): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2282): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1513): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7284): MountEmulatedStorage()
E/Zygote  ( 7284): v2
I/libpersona( 7284): KNOX_SDCARD checking this for 10032
I/libpersona( 7284): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7284 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7284): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7284): TimaSignature is unavailable
D/ActivityThread( 7284): Added TimaKeyStore provider
D/ResourcesManager( 7284): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7284): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/PowerManagerService(  903): [PWL] Off : 15s ago
W/GAV2    ( 7197): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/WebViewFactory( 7266): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7266): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7266): Loading: webviewchromium
I/System.out( 7284): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7284): Inside WakeupProvider
I/LibraryLoader( 7266): Time to load native libraries: 1 ms (timestamps 6695-6696)
I/LibraryLoader( 7266): Expected native library version number "",actual native library version number ""
,E/DatabaseUtils( 7284): Writing exception to parcel
E/DatabaseUtils( 7284): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7284): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7284): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7284): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7284): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7284): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7284): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7284): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7284): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7284): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7284): 	at android.os.Binder.execTransact(Binder.java:446)
V/WebViewChromiumFactoryProvider( 7266): Binding Chromium to main looper Looper (main, tid 1) {3766f5cd}
I/LibraryLoader( 7266): Expected native library version number "",actual native library version number ""
I/chromium( 7266): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/System.err( 7229): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/BrowserStartupController( 7266): Initializing chromium process, renderers=0
W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
I/VlingoApplication( 7284): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/chromium( 7266): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7266): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium( 7266): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
W/System.err( 7229): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7229): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7229): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7229): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7229): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7229): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7229): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7229): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7229): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7229): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7229): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7229): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7229): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7229): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7229): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7229): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7229): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7229): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7229): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7229): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7229): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7229): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7229): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7229): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7229): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7229): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/Adreno-EGL( 7266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7266): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7266): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7266): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7266): Remote Branch: 
I/Adreno-EGL( 7266): Local Patches: 
I/Adreno-EGL( 7266): Reconstruct Branch: 
E/DatabaseUtils( 7284): Writing exception to parcel
E/DatabaseUtils( 7284): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7284): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7284): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7284): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7284): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7284): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7284): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7284): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7284): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7284): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7284): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7229): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7229): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7229): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7229): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7229): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7229): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7229): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7229): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7229): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7229): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7229): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7229): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7229): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7229): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7229): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7229): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7229): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7229): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7229): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7229): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7229): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7229): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7229): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7229): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7229): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7229): [DLApplication]-Init Called!:false
E/[CarMode]( 7229): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7229): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7229): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7229): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7229): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7229): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7229): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7229): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7229): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7229): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7229): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7229): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7229): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7229): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7229): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoAndroidCore( 7284): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
W/chromium( 7266): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7266): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/MessageDataHandler( 7229): initialize
D/[CarModeFW]( 7229): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7229): CDH-initiazlieCaches : after sync
W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7266): onDetachedFromWindow called when already detached. Ignoring
D/[CarModeFW]( 7229): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7229): CDH-ContactDataHandler initiazlieCaches time : 20
D/[CarModeFW]( 7229): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 7229): DrivingManager-initialize...
D/SystemWebViewEngine( 7266): CordovaWebView is running on device made by: samsung
I/SensorService(  903): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  903): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  903): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
D/VlingoApplication( 7284): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7284): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/Activity( 7266): performCreate Call secproduct feature valuefalse
D/Activity( 7266): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7266): Render dirty regions requested: true
D/ActivityManager(  903): post active user change for 0
D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/MediaPlayer( 7229): Need to enable context aware info
V/MediaPlayer-JNI( 7229): native_setup
V/MediaPlayer( 7229): constructor
V/MediaPlayer( 7229): setListener
E/MediaPlayer-JNI( 7229): QCMediaPlayer mediaplayer NOT present
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/[CarModeFW]( 7229): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7229): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7229): [DLServiceManager]-getOnDLLocationSuggestionListener..........
I/OpenGLRenderer( 7266): Initialized EGL, version 1.4
I/OpenGLRenderer( 7266): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7266): Enabling debug mode 0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1454063431800
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1454063431804
D/[CarModeFW]( 7229): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1454063431808
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1454063431809
D/[CarModeFW]( 7229): RecommendHandler-selection = type = '3'
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1454063431812
D/[CarMode]( 7229): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1454063431816
I/[CarMode]( 7229): [LogNotNull]-Package name is: com.google.android.apps.maps
D/TP/SmsProvider( 1487): query,matched:2, calling pid = 7229
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1487): match 2:Elapsed time : 2.745 ms
E/[CarMode]( 7229): [DLApplication]-Init End!:true
D/TP/SmsProvider( 1487): query,matched:2, calling pid = 7229
D/TP/SmsProvider( 1487): match 2:Elapsed time : 2.226 ms
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/Zygote  ( 7346): MountEmulatedStorage()
E/Zygote  ( 7346): v2
I/libpersona( 7346): KNOX_SDCARD checking this for 10003
I/libpersona( 7346): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7346 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 7346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[CarModeFW]( 7229): CDH-buildContactCacheWireFrame : cur len =0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/MessageDataHandler( 7229):  getInboxList smsCursor : 68
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/Timeline( 7266): Timeline: Activity_idle id: android.os.BinderProxy@2a46d994 time:87091
I/ActivityManager(  903): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7362 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
E/Zygote  ( 7362): MountEmulatedStorage()
E/Zygote  ( 7362): v2
I/libpersona( 7362): KNOX_SDCARD checking this for 10019
I/libpersona( 7362): KNOX_SDCARD not a persona
W/ActivityManager(  903): mDVFSHelper.release()
I/Timeline(  903): Timeline: Activity_windows_visible id: ActivityRecord{22cd78f0 u0 com.test.thalitest/.MainActivity t9} time:87099
D/[CarMode]( 7229): [DLApplication]-GooglePlayServices SUCCESS.
I/SELinux ( 7362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SELinux ( 7362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/TimaKeyStoreProvider( 7346): TimaSignature is unavailable
D/ActivityThread( 7346): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/SELinux ( 7362): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
W/IInputConnectionWrapper( 7266): showStatusIcon on inactive InputConnection
E/[CarMode]( 7229): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/[CarModeFW]( 7229): CDH-buildContactCacheWireFrame : cur len =0
I/UpdateManagerReceiver( 7229): Intent : android.intent.action.PACKAGE_ADDEDFri Jan 29 11:30:31 GMT+01:00 2016
D/[CarModeFW]( 7229): RecommendHandler-selection = type = '3'
D/TP/MmsProvider( 1487): Query uri=content://mms/inbox, match=2, calling pid = 7229
D/TP/MmsProvider( 1487): Query uri=content://mms, match=0, calling pid = 7229
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7362): TimaSignature is unavailable
D/ActivityThread( 7362): Added TimaKeyStore provider
E/Zygote  ( 7383): MountEmulatedStorage()
I/libpersona( 7383): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7383): v2
I/libpersona( 7383): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7383 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 7346): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/MessageDataHandler( 7229):  getInboxList mmsCursor : 137
D/ResourcesManager( 7362): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/JsMessageQueue( 7266): Set native->JS mode to OnlineEventsBridgeMode
I/MessageDataHandler( 7229): getUnreadMessageCount :0
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 215
I/ActivityManager(  903): Killing 5811:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
I/chromium( 7266): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7266): 
D/MessageDataHandler( 7229):  getInboxList mms,sms cursor join : 26
D/TimaKeyStoreProvider( 7383): TimaSignature is unavailable
D/ActivityThread( 7383): Added TimaKeyStore provider
D/[CarModeFW]( 7229): PushMessageService-onCreate
D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7229
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.427 ms
I/ActivityManager(  903): Killing 4754:com.android.calendar/u0a149 (adj 15): bgCount ##41
I/ActivityManager(  903): Killing 5277:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##42
I/ActivityManager(  903): Killing 6080:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##43
D/ResourcesManager( 7383): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/TP/MmsSmsProvider( 1487): query,matched:13, calling pid = 7229
D/TP/MmsSmsProvider( 1487): match 13:Elapsed time : 0.861 ms
D/[CarModeFW]( 7229): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7229): PushMessageService-registerPushMessageServiceListener
D/MessageDataHandler( 7229):  getInboxList address cursor : 14
D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 7229
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.823 ms
D/MessageDataHandler( 7229):  getInboxList thread cursor : 4
D/MessageDataHandler( 7229):  thread, addr result: 1
I/[CarModeFW]( 7229): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 270
I/[CarModeFW]( 7229): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 272
W/ContextImpl( 7383): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7400): MountEmulatedStorage()
D/UserAnalysis.PlaceProvider( 7346): PlaceProvider onCreate()
I/libpersona( 7400): KNOX_SDCARD checking this for 10111
E/Zygote  ( 7400): v2
I/libpersona( 7400): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7400 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UserAnalysis.SecureDbManager( 7346): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7346): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7346): Create SecureDbHelper
D/ResourcesManager( 7383): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/TimaKeyStoreProvider( 7400): TimaSignature is unavailable
D/ActivityThread( 7400): Added TimaKeyStore provider
E/FilterInstaller( 7383): There is no requred permission
D/IntelligenceServiceApplication( 7346): onCreate()
I/ActivityManager(  903): Killing 6244:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##41
D/ResourcesManager( 7400): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
I/SQLiteSecureOpenHelper( 7346): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7346): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7346): Open Place.db in secure mode
D/jxcore_app_log( 7266): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359654272
I/[CarModeFW]( 7229): -[snowdeer] Rec : Missed Call : 407
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 418
I/SQLiteSecureOpenHelper( 7346): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7346): ...getDatabaseLocked(b,b,pwd)
D/PackageIntentReceiver( 7400): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7400): Not GearManger package! 
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7419): MountEmulatedStorage()
I/libpersona( 7419): KNOX_SDCARD checking this for 10117
E/Zygote  ( 7419): v2
I/libpersona( 7419): KNOX_SDCARD not a persona
I/chromium( 7266): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  903): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7419 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  903): Killing 6278:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
I/SELinux ( 7419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7419): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7419): TimaSignature is unavailable
,D/ActivityThread( 7419): Added TimaKeyStore provider
,I/art     (  903): Explicit concurrent mark sweep GC freed 194047(12MB) AllocSpace objects, 2(3MB) LOS objects, 31% free, 35MB/51MB, paused 1.398ms total 97.486ms
,I/[CarModeFW]( 7229): -[snowdeer] Rec : Favorite : 126
,D/[CarModeFW]( 7229): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 7229): MyPlaceProvider-=============
,D/[CarModeFW]( 7229): MyPlaceProvider-=============
D/[CarModeFW]( 7229): MyPlaceProvider-=============
,D/[CarModeFW]( 7229): MyPlaceProvider-=============
D/ResourcesManager( 7419): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
D/[CarModeFW]( 7229): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7229): MyPlaceProvider-==============
D/[CarModeFW]( 7229): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7229): MyPlaceProvider-==============
D/[CarModeFW]( 7229): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7229): MyPlaceProvider-==============
D/[CarModeFW]( 7229): MyPlaceProvider-latitude is not valid
,W/ResourcesManager( 7419): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 547
,I/[CarModeFW]( 7229): -[snowdeer] Rec : CallLog : 21
,D/[CarMode]( 7229): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@1ba34044, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ac4258ea] LOCATIONS
,I/[CarModeFW]( 7229): -[snowdeer] Rec : Schedule : 12
,I/[CarModeFW]( 7229): -[snowdeer] Rec : During DL app : 2
,W/libprocessgroup(  903): failed to open /acct/uid_10149/pid_4754/cgroup.procs: No such file or directory
W/libprocessgroup(  903): failed to open /acct/uid_10112/pid_5811/cgroup.procs: No such file or directory
,W/libprocessgroup(  903): failed to open /acct/uid_10148/pid_5277/cgroup.procs: No such file or directory
W/libprocessgroup(  903): failed to open /acct/uid_10153/pid_6080/cgroup.procs: No such file or directory
I/[CarModeFW]( 7229): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7229): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 7229): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 575
I/[CarModeFW]( 7229): -[snowdeer] Rec : Location Sharing : 6
I/[CarModeFW]( 7229): -[snowdeer] Rec : POI : 0
,I/[CarModeFW]( 7229): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7229): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7229): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7229): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 7229): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 584
,D/MagazineService Version( 7419): Magazine-Administrator: 11
D/MagazineService Version( 7419): Magazine-Provider: 14
D/MagazineService Version( 7419): Magazine-Channel: 14
D/HeadlinesChannelApplication( 7419): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 7419): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/libprocessgroup(  903): failed to open /acct/uid_10035/pid_6244/cgroup.procs: No such file or directory
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7419): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7435): MountEmulatedStorage()
E/Zygote  ( 7435): v2
I/libpersona( 7435): KNOX_SDCARD checking this for 1000
I/libpersona( 7435): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7419): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/art     (  320): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 10.966ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.704ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.335ms
,I/SELinux ( 7435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Killing 6297:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##41
,W/libprocessgroup(  903): failed to open /acct/uid_10037/pid_6278/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7435): TimaSignature is unavailable
D/ActivityThread( 7435): Added TimaKeyStore provider
,D/ResourcesManager( 7435): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10037/pid_6297/cgroup.procs: No such file or directory
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7450): MountEmulatedStorage()
I/libpersona( 7450): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7450): v2
I/libpersona( 7450): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6459:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/SELinux ( 7450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7450): TimaSignature is unavailable
,D/ActivityThread( 7450): Added TimaKeyStore provider
,D/ResourcesManager( 7450): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AcmsPackageEventListener( 7450): Received: android.intent.action.PACKAGE_ADDED
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6459/cgroup.procs: No such file or directory
,W/ContextImpl( 7450): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7450): Enter Oncreate
D/AcmsServiceMonitor( 7450): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 7450): creating AcmsCore
D/AcmsCore( 7450): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7450): AcmsCore
,D/AcmsCore( 7450): init
,D/AcmsCore( 7450): Looper handler is not null
D/AcmsCore( 7450): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7450): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7450): Incrementing - Counter value: 1
D/AcmsCore( 7450): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 7450): onStartCommand
,D/AcmsCertificateMngr( 7450): AcmsCertificateMngr
D/AcmsService( 7450): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7450): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7450): Incrementing - Counter value: 2
,D/AcmsService( 7450): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7450): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 7450): AcmsRevocationMngr
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7468): MountEmulatedStorage()
I/libpersona( 7468): KNOX_SDCARD checking this for 10165
E/Zygote  ( 7468): v2
I/libpersona( 7468): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7468 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/System.out( 7284): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/AcmsService( 7450): Inside handle Intent
E/SELinux ( 7468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AcmsService( 7450): App added - package name: com.test.thalitest
D/AcmsCore( 7450): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7450): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7450): Incrementing - Counter value: 3
D/AcmsCore( 7450): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7450): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7450): Decrementing - Counter value: 2
,D/TimaKeyStoreProvider( 7468): TimaSignature is unavailable
,D/ActivityThread( 7468): Added TimaKeyStore provider
,D/ResourcesManager( 7468): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7468): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7468): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7484): MountEmulatedStorage()
I/libpersona( 7484): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7484): v2
I/libpersona( 7484): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7484 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
I/ActivityManager(  903): Killing 4805:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,I/SELinux ( 7484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7484): TimaSignature is unavailable
,D/ActivityThread( 7484): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10045/pid_4805/cgroup.procs: No such file or directory
,D/ResourcesManager( 7484): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7484): (284) automatic index on shooting_modes(title_id)
,D/Finsky  ( 6620): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 2441): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ActivityManager(  903): Killing 6181:com.google.android.talk/u0a116 (adj 15): bgCount ##41
,D/ChimeraCfgMgr( 2441): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2441): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2441): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10116/pid_6181/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2441): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2441): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2441): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2441): Submit a task: k
,D/ChimeraCfgMgr( 2441): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2441): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2441): Processing package: com.test.thalitest
,D/GassUtils( 2441): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
,D/k       ( 2441): Found info for package com.test.thalitest in db.
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7508): MountEmulatedStorage()
,E/Zygote  ( 7508): v2
I/libpersona( 7508): KNOX_SDCARD checking this for 10039
I/libpersona( 7508): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7508 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/jxcore-log( 7266): Initializing JXcore engine
,W/jxcore-log( 7266): JXcore engine is ready
,I/SELinux ( 7508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7508): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7508): TimaSignature is unavailable
,D/ActivityThread( 7508): Added TimaKeyStore provider
,E/SMD     (  294): DCD ON
,D/SecurityLogAgent:SEDenialService(  903): Got Modify Event and sending Denial Intent foraudit.log
E/auditd  ( 2158): In denial and Property audit_ondenial is set to 1 
D/ResourcesManager( 7508): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,W/BaseAppContext( 2441): Using Auth Proxy for data requests.
W/BaseAppContext( 2441): Using Auth Proxy for data requests.
,D/SecurityLogAgent:SEDenialService(  903): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/jxcore-log( 7266): Starting JXcore engine
,W/BaseAppContext( 2441): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 2441): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 2441): Using Auth Proxy for data requests.
,W/BaseAppContext( 2441): Using Auth Proxy for data requests.
W/BaseAppContext( 2441): Using Auth Proxy for data requests.
,W/BaseAppContext( 2441): Using Auth Proxy for data requests.
,W/jxcore-log( 7266): Platform android
W/jxcore-log( 7266): 
,W/jxcore-log( 7266): Process ARCH arm
W/jxcore-log( 7266): 
,I/ActivityManager(  903): Killing 6511:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,D/BootupListener( 1487): ACTION_DRIVELINK
,D/SettingsProvider(  903): name = drivelink_navigation
D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 1001
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  903): ret = -1
D/BootupListener( 1487): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  903): name = internet_call_settings_visibility
D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 1001
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  903): ret = -1
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7525): MountEmulatedStorage()
E/Zygote  ( 7525): v2
I/libpersona( 7525): KNOX_SDCARD checking this for 1000
I/libpersona( 7525): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7525 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7525): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7525): TimaSignature is unavailable
,D/ActivityThread( 7525): Added TimaKeyStore provider
,D/ResourcesManager( 7525): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7525):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7525):  SeDenialReceiver : File path = null
,I/ActivityManager(  903): Killing 6533:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  903): failed to open /acct/uid_10074/pid_6511/cgroup.procs: No such file or directory
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6533/cgroup.procs: No such file or directory
,I/jxcore-log( 7266): JXcore Cordova bridge is ready!
I/jxcore-log( 7266): 
,W/jxcore-log( 7266): JXcore engine is started
,D/AcmsKeyStoreHelper( 7450):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 7450): Key Store exist
I/AcmsKeyStoreHelper( 7450): Hence loading the keystore file
,I/jxcore-log( 7266): Toggling radios to true
I/jxcore-log( 7266): 
,D/BluetoothAdapter( 7266): enable()
,D/BluetoothAdapter( 7266): enable(): BT is already enabled..!
,D/WifiService(  903): New client listening to asynchronous messages
I/WifiManager( 7266): packageName : com.test.thalitest
,D/SecContentProvider(  903): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  903): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  903): mCursor = null
,D/WifiService(  903): setWifiEnabled: true pid=7266, uid=10191
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  903): Permission Denial: getCurrentUser() from pid=7266, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  903): Failed getting userId using ActivityManagerNative
W/WifiService(  903): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7266, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  903): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  903): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  903): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  903): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  903): name = wifi_on
,I/WifiService(  903): disconnect: pid=7266, uid=10191
,I/wpa_supplicant( 1304): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7266): Radios toggled
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): My device name is: samsung-SM-G900F
I/jxcore-log( 7266): 
,I/wpa_supplicant( 1304): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1304): wlan0: State: COMPLETED -> DISCONNECTED
,D/AcmsKeyStoreHelper( 7450):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7450): getKeyStoreForApplication success 
D/AcmsCore( 7450): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7450): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7450): Decrementing - Counter value: 1
D/AcmsCore( 7450): AcmsCore: ACMS_APP_INSTALLED
,I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1304): wlan0: State: DISCONNECTED -> DISCONNECTED
D/AcmsCore( 7450): This is NOT a valid MirrorLink app
D/AcmsCore( 7450): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7450): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7450): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7450): Counter value is 0: Stopping ACMS service
,E/WifiStateMachine(  903): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1304): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1304): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1304): Disconnected - do not scan
I/wpa_supplicant( 1304): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  903): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  903): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  903): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/AcmsServiceMonitor( 7450): getSvcCounter - Counter value: 0
D/AcmsService( 7450): Enter onDestroy
E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/AcmsService( 7450): cleanUp(): inside service clean up
D/AcmsCore( 7450): AcmsCore: inside DeInit
D/AcmsCore( 7450): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7450): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7450): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7450): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7450): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7450): getSvcCounter - Counter value: 0
E/WifiStateMachine(  903): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/AcmsService( 7450): killing acms process
E/native  (  903): do suspend true
I/Process ( 7450): Sending signal. PID: 7450 SIG: 9
,D/WifiP2pService(  903): InactiveState{ what=143375 }
,D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ActivityManager(  903): Process ACMS.Process (pid 7450)(adj 0) has died(50,582)
,V/NativeCrypto( 2224): Read error: ssl=0x9b53ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2224): SSL shutdown failed: ssl=0x9b53ae00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  903): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ConnectivityService(  903): updateNetworkInfo()
,D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): ignoring duplicate network state non-change
,D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  903): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1304): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1304): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1304): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1304): First Scan Start
,I/wpa_supplicant( 1304): Scan requested (ret=0) - scan timeout 30 seconds
,D/StatusBar.NetworkController( 1184): applyOpen
,E/WifiStateMachine(  903): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  903): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  903): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  903): do suspend true
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  903): InactiveState{ what=143375 }
D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  903): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Validated
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1316): Starting #6
,I/Hs20UtilService( 1316): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/ChimeraCfgMgr( 2441): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2441): Module APK com.google.android.play.games already loaded
,D/CommandListener(  284): Clearing all IP addresses on wlan0
D/ConnectivityService(  903): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  903): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/EntConnectivity(  903): Not allowed due to - mEnabled false
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine(  903): updateConfiguredNetworkExpiration - currTime: 1454063434262
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524292
D/WifiStateMachine(  903): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService(  903): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  903): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  903): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Disconnected - quitting
E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  903): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/CSLegacyTypeTracker(  903): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  903): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1487): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  903): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  903): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityManager.CallbackHandler( 2441): CM callback handler got msg 524292
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  903): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  903): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  903): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  903): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  903): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): updateIfacesLocked()
V/NetworkStats(  903): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  903): UpdateStatsForKnox
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService(  903): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  903): performPollLocked() took 6ms
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,I/Hs20UtilService( 1316): Starting #7
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,I/Hs20UtilService( 1316): Message received 5007
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1487): FileWriteThread : threadType = 3
,I/Icing   ( 2441): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,D/ResourcesManager( 2441): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/Icing   ( 2441): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  903): updateDataUsageMap
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  903): MasterInitialState.processMessage what=3
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  903): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  903): CLoinfo wifi false
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2282): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  903): No Active Data Connection
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6314): type=WIFI subType= reason=null isConnected=false
,I/SystemBroadcastReceiver( 6346): [#DCM#] [DCM_Performance] onReceive completed in time  435 microsec. 
,I/SystemBroadcastReceiver( 6346): [#DCM#] Calling notifyListeners. 
,I/DCMController( 6346): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 6346): [#DCM#] setIsConnectedForExtractors 
,I/PCWCLIENTTRACE_PushUtil( 7098): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7098): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7098): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7098): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3755): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3755): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7098): noConnectivity : true
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7569): MountEmulatedStorage()
,E/Zygote  ( 7569): v2
I/libpersona( 7569): KNOX_SDCARD checking this for 10002
I/libpersona( 7569): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7569 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7569): TimaSignature is unavailable
,D/ActivityThread( 7569): Added TimaKeyStore provider
,D/ResourcesManager( 7569): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  903): Killing 6574:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7592): MountEmulatedStorage()
I/libpersona( 7592): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7592): v2
I/libpersona( 7592): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7592): TimaSignature is unavailable
,D/ActivityThread( 7592): Added TimaKeyStore provider
,D/ResourcesManager( 7592): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_6574/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7592): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7608): MountEmulatedStorage()
,E/Zygote  ( 7608): v2
I/libpersona( 7608): KNOX_SDCARD checking this for 10010
I/libpersona( 7608): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7608 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7608): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1304): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1304): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1304): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1304): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/TimaKeyStoreProvider( 7608): TimaSignature is unavailable
,D/ActivityThread( 7608): Added TimaKeyStore provider
,E/WifiStateMachine(  903): [1,454,063,435,305 ms] noteScanEnd no scan source
,E/WifiStateMachine(  903): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@21ef1c43 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  903): setDetailed state send new extra info0x
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
I/CLocInfoService(  903): External Intent Received android.net.wifi.SCAN_RESULTS
,D/ResourcesManager( 7608): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  903): Killing 5902:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1304): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1304): Associated with C0.AA.48
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/FOTA_Client( 7608): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  903): mCursor = null
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7623): MountEmulatedStorage()
,E/Zygote  ( 7623): v2
I/libpersona( 7623): KNOX_SDCARD checking this for 10018
I/libpersona( 7623): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7623 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6146:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,I/wpa_supplicant( 1304): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  903): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,I/wpa_supplicant( 1304): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1304): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  903): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  903): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1304): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1304): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1304): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1304): Blacklist: Clear (temp) 
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  903): Network connection established
,D/WifiNative-HAL(  903): callSECApiVoid - ID [50]
E/WifiStateMachine(  903): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  903): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  903): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  903): Got NetworkAgent Messenger
D/ConnectivityService(  903): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903): NetworkAgent connected
E/WifiStateMachine(  903): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  903): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SELinux ( 7623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SELinux ( 7623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7623): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  903): failed to open /acct/uid_1000/pid_5902/cgroup.procs: No such file or directory
,E/WifiStateMachine(  903): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  903): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  903): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  284): Setting iface cfg
,E/WifiStateMachine(  903): Start Dhcp Watchdog 2
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,D/TimaKeyStoreProvider( 7623): TimaSignature is unavailable
,D/ActivityThread( 7623): Added TimaKeyStore provider
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/libprocessgroup(  903): failed to open /acct/uid_10167/pid_6146/cgroup.procs: No such file or directory
,D/ResourcesManager( 7623): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7623): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7623): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454063435470
,I/KLMS-2.4.503: ( 7623): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7623): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7623): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  903): Killing 6107:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7639): MountEmulatedStorage()
I/libpersona( 7639): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7639): v2
I/libpersona( 7639): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7639 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  903): do suspend false
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  903): InactiveState{ what=143375 }
,D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  903): mCursor = null
,I/SELinux ( 7639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7639): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7639): TimaSignature is unavailable
,D/ActivityThread( 7639): Added TimaKeyStore provider
,D/ResourcesManager( 7639): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10113/pid_6107/cgroup.procs: No such file or directory
,I/SO_AGENT( 7639): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5202): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7138): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7138): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7138): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7138): [SLFUCHKMGR] constructor called
,I/SA      ( 7138): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7138): [OR] == isSIMCardReady false ==
,I/SA      ( 7138): [SCU] == networkStateCheck == false
I/SA      ( 7138): [OR] onReceive END
,E/SPPClientService( 5202): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7656): MountEmulatedStorage()
,E/Zygote  ( 7656): v2
I/libpersona( 7656): KNOX_SDCARD checking this for 10070
I/libpersona( 7656): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7656 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 277us total 12.831ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 7.909ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 7.729ms
,I/SELinux ( 7656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  903): Killing 6346:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,E/SELinux ( 7656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7656): TimaSignature is unavailable
,D/ActivityThread( 7656): Added TimaKeyStore provider
,D/ResourcesManager( 7656): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7656): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7656): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7656): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup(  903): failed to open /acct/uid_10004/pid_6346/cgroup.procs: No such file or directory
,E/dhcpcd  ( 7671): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7671): version 5.5.6 starting
,E/dhcpcd  ( 7671): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/comsamsunglog( 7656): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7656): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7656): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7656): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7656): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7656): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7656): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7656): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  903): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 10070
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  903): ret = -1
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7656): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7656): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7656): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7656): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7656): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7656): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7656): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7656): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1338): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/dhcpcd  ( 7671): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7671): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7671): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7671): bssid match
,I/dhcpcd  ( 7671): wlan0: rebinding lease of 192.168.1.136
,D/accuweather( 7656): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
D/accuweather( 7656): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7683): MountEmulatedStorage()
,E/Zygote  ( 7683): v2
I/libpersona( 7683): KNOX_SDCARD checking this for 1000
I/libpersona( 7683): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7683 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6409:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7683): TimaSignature is unavailable
,D/ActivityThread( 7683): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10043/pid_6409/cgroup.procs: No such file or directory
,D/ResourcesManager( 7683): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7683): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7683): premStatus:2
,I/KnoxUsageLogPro( 7683): isEulaShown : false
,I/KnoxUsageLogPro( 7683): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
,E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD checking this for 10087
I/libpersona( 7700): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7700 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6823:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/ActivityThread( 7700): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10011/pid_6823/cgroup.procs: No such file or directory
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/GAV2    ( 7197): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  903): Killing 5919:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
,D/Headlines( 5455): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5455): getCountryCode(): countryCode = PL
,D/Headlines( 5455): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5455): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7718 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/HeadlinesCardManager( 5455): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5455): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5455): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5455): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5455): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7718): MountEmulatedStorage()
E/Zygote  ( 7718): v2
I/libpersona( 7718): KNOX_SDCARD checking this for 10127
I/libpersona( 7718): KNOX_SDCARD not a persona
,I/SELinux ( 7718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7718): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7718): TimaSignature is unavailable
,D/ActivityThread( 7718): Added TimaKeyStore provider
,D/ResourcesManager( 7718): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10157/pid_5919/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7718): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7718): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/SQLiteConnectionPool( 2441): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/SSRM:m  (  903): SIOP:: AP = 410, PST = 388, CUR = 450
,E/SMD     (  294): DCD ON
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7718): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7718): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7718): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7718): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7718): Loading: webviewchromium
,I/LibraryLoader( 7718): Time to load native libraries: 4 ms (timestamps 1758-1762)
I/LibraryLoader( 7718): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7718): Binding Chromium to main looper Looper (main, tid 1) {33813153}
,I/LibraryLoader( 7718): Expected native library version number "",actual native library version number ""
,I/chromium( 7718): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7718): Initializing chromium process, renderers=0
,W/art     ( 7718): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7718): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7718): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7718): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7718): Requires BLUETOOTH permission
,I/Adreno-EGL( 7718): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7718): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7718): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7718): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7718): Remote Branch: 
I/Adreno-EGL( 7718): Local Patches: 
I/Adreno-EGL( 7718): Reconstruct Branch: 
,I/NSApplication( 7718): Starting up...
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7779): MountEmulatedStorage()
,E/Zygote  ( 7779): v2
,I/libpersona( 7779): KNOX_SDCARD checking this for 10137
,I/libpersona( 7779): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7779 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,I/ActivityManager(  903): Killing 7063:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/SELinux ( 7779): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7779): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7779): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7779): TimaSignature is unavailable
,D/ActivityThread( 7779): Added TimaKeyStore provider
,D/ResourcesManager( 7779): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10014/pid_7063/cgroup.procs: No such file or directory
,W/ResourcesManager( 7779): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7779): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7779): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7779): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7779): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7779): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7795): MountEmulatedStorage()
,E/Zygote  ( 7795): v2
I/libpersona( 7795): KNOX_SDCARD checking this for 10162
I/libpersona( 7795): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7795 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager(  903): Killing 7082:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7795): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7795): TimaSignature is unavailable
,D/ActivityThread( 7795): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10015/pid_7082/cgroup.procs: No such file or directory
,D/ResourcesManager( 7795): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7795): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7795): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7795): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7795): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,E/Zygote  ( 7818): MountEmulatedStorage()
E/Zygote  ( 7818): v2
I/libpersona( 7818): KNOX_SDCARD checking this for 10077
I/libpersona( 7818): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7818 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,I/dhcpcd  ( 7671): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7795): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 7818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,I/SELinux ( 7818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7818): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7671): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7525): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7525): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7525): StateMachine : Current State = 1
,D/TimaKeyStoreProvider( 7818): TimaSignature is unavailable
D/ActivityThread( 7818): Added TimaKeyStore provider
,I/ActivityManager(  903): Killing 6489:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,D/SecurityLogAgent( 7525): StateMachine : Changed Current State = 1
,I/ActivityManager(  903): Killing 4871:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,I/art     (  903): Explicit concurrent mark sweep GC freed 55115(3MB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 35MB/51MB, paused 1.490ms total 107.975ms
,I/art     (  903): WaitForGcToComplete blocked for 15.433ms for cause HeapTrim
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7855): MountEmulatedStorage()
,E/Zygote  ( 7855): v2
I/libpersona( 7855): KNOX_SDCARD checking this for 10177
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7855 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7818): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/libprocessgroup(  903): failed to open /acct/uid_10033/pid_6489/cgroup.procs: No such file or directory
,W/libprocessgroup(  903): failed to open /acct/uid_10034/pid_4871/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,D/BadgeProvider( 7818): onCreate
,D/BadgeProvider( 7818): DatabaseHelper
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7818): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7818): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7818): sendNotify, [notify] : null
D/BadgeProvider( 7818): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7818): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7818): update, [UpdateCount] : 1
,D/Launcher.Model( 1513): reloadBadges entered.
,I/ActivityManager(  903): Killing 6024:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,I/iu.Environment( 2441): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2441): num queued entries: 0
,I/iu.UploadsManager( 2441): num updated entries: 0
,I/iu.SyncManager( 2441): NEXT; no task
,I/Hs20UtilService( 1316): Starting #8
,I/Hs20UtilService( 1316): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup(  903): failed to open /acct/uid_10041/pid_6024/cgroup.procs: No such file or directory
,E/WifiStateMachine(  903): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  903): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  903): do suspend true
,D/WifiP2pService(  903): InactiveState{ what=143375 }
,D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  903): WifiStateMachine DHCP successful
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  903): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  903): Not connected state, yet.
E/WifiStateMachine(  903): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
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
,I/Hs20UtilService( 1316): Starting #9
,I/Hs20UtilService( 1316): Message received 5007
,E/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  903): Now, connected state.
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine(  903): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService(  903): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  903): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  903): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  903): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  903): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  903): updateSourceRoutes : add src route for:192.168.1.136
V/        (  284): QcRouteController
,E/WifiStateMachine(  903): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  903): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        (  284): QcRouteController
I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  903): mBoosterFLAG : 0
I/WifiTrafficPoller(  903): current booster mode : FullMode
,D/WifiNative-HAL(  903): callSECApiVoid - ID [212]
,I/CLocInfoService(  903): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  903): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,I/WifiStateMachine(  903): REQUEST_POWER_SAVE_ON
,I/Hs20UtilService( 1316): Starting #10
,I/Hs20UtilService( 1316): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/        (  284): QcRouteController
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,V/        (  284): QcRouteController
,I/Hs20UtilService( 1316): Starting #11
,I/Hs20UtilService( 1316): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  903): callSECApi what=220
D/WifiStateMachine(  903): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,V/        (  284): QcRouteController
,D/PowerManagerService(  903): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=903
D/ConnectivityService(  903): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  903): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/ConnectivityService(  903): calling update connectivity
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): ignoring duplicate network state non-change
D/LockPatternUtilsCache( 1184): value : false
D/ConnectivityService(  903): ignoring duplicate network state non-change
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/ConnectivityService(  903): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/LockPatternUtilsCache( 1184): value : false
D/ConnectivityService(  903): calling update connectivity
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/ConnectivityService(  903): rematching NetworkAgentInfo [WIFI () - 503]
D/LockPatternUtilsCache( 1184): value : false
D/ConnectivityService(  903):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Validated
,D/ConnectivityService(  903): currentScore = 0, newScore = 60
,D/ConnectivityService(  903):    accepting network in place of null
D/ConnectivityService(  903): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1487): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  903): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  903): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/ConnectivityService(  903): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/EntConnectivity(  903): Not allowed due to - mEnabled false
,D/ConnectivityService(  903): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
V/NetworkStats(  903): updateIfacesLocked()
,V/NetworkStats(  903): performPollLocked(flags=0x1)
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
D/ConnectivityService(  903): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  903): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2441): CM callback handler got msg 524290
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NetworkStatsFactory(  903): UpdateStatsForKnox
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/NetworkStats(  903): performPollLocked() took 5ms
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 2441): CM callback handler got msg 524290
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
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
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  903): MasterInitialState.processMessage what=3
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  903): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  903): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  903): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  903): CLocinfo wifi true 
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2282): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2206): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2206): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3755): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3755): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6314): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7098): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7098): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7098): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7098): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2(  903): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  903): mCursor = null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7608): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7623): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7623): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454063438396
,I/KLMS-2.4.503: ( 7623): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7623): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7623): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7623): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7623): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7639): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5202): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7138): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7138): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7138): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7138): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7138): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7138): [SCU] == networkStateCheck == true
I/SA      ( 7138): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7138): isChinaCountryCode : false
I/SA      ( 7138): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7138): [OR] == networkStateCheck true ==
,I/SA      ( 7138): [OR] GetMyCountryZoneTask
,I/SA      ( 7138): [OR] onReceive END
,I/SA      ( 7138): [SRS] prepareGetMyCountryZone
,I/SA      ( 7138): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7138): [SSP] query invoked
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7656): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7656): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
I/SA      ( 7138): [TPMU] GetMccFromDB : null
,I/SA      ( 7138): [SCU] getMccFromPreferece mcc = 260
,I/KnoxUsageLogPro( 7683): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7683): premStatus:2
I/SA      ( 7138): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7683): isEulaShown : false
,I/KnoxUsageLogPro( 7683): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 7138): fail readDirectory() errno=2
,D/Headlines( 5455): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5455): getCountryCode(): countryCode = PL
,D/Headlines( 5455): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5455): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5455): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5455): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5455): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/HeadlinesCardManager( 5455): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5455): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7779): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7779): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7779): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7525): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7525): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7525): StateMachine : Current State = 1
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7525): StateMachine : Changed Current State = 1
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2441): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2441): num queued entries: 0
,I/iu.UploadsManager( 2441): num updated entries: 0
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.SyncManager( 2441): NEXT; no task
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WaitQueueForNetworkActivate( 7508): notifyNetworkActivated
,W/ContextImpl( 7508): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  903): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7266): 
,D/ConnectivityService(  903): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7508): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7508): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7508): exit::IDLE
D/InitializeManagerStateMachine( 7508): entry::NETWORK_CHECK
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7508): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7508): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7508): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7508): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7508): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7508): entry::SUCCESS
D/hcjo    ( 7508): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7508): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7508): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7508): exit::SUCCESS
D/InitializeManagerStateMachine( 7508): entry::IDLE
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7138): [RC New] Execute method=[GET] start
,I/SA      ( 7138): [RC New] Security=[true]
,I/System.out( 7138): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7138): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 7138): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7266): 
,E/SMD     (  294): DCD ON
,I/SA      ( 7138): [RC New] [v2liruge] api execute + 652
I/SA      ( 7138): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7138): AsyncTask #1 calls detatch()
,I/SA      ( 7138): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7138): [OCP] update openData : PL
,I/SA      ( 7138): [TPMU] getNetworkMcc : 
,I/SA      ( 7138): [SCU] saveMccToPreferece Start
I/SA      ( 7138): [SCU] RegionMCC : 260
I/SA      ( 7138): [SSP] query invoked
,I/SA      ( 7138): [TPMU] GetMccFromDB : null
,I/SA      ( 7138): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7138): [SCU] saveMccToPreferece End
,I/SA      ( 7138): [RC New] executeRequest [v2liruge] end. 700
I/SA      ( 7138): [RC New] Execute end
,I/SA      ( 7138): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7138): [OR] GetMyCountryZoneTask Success
,D/PackageManager(  903): [MSG] MCS_UNBIND
,I/ActivityManager(  903): Killing 5998:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,W/libprocessgroup(  903): failed to open /acct/uid_10047/pid_5998/cgroup.procs: No such file or directory
,E/WifiStateMachine(  903): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  903): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  903): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/ConnectivityService(  903): identical MTU - not setting
D/ConnectivityService(  903): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  903): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  284): QcRouteController
I/dhcpcd  ( 7671): wlan0: sending IPv6 Router Solicitation
,V/        (  284): QcRouteController
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
,D/Nat464Xlat(  903): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2441): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2441): CM callback handler got msg 524295
,I/WifiStateMachine(  903): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  903): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  257): id=15 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=15 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/PowerManagerService(  903): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 903) eventTime = 96369
,D/PowerManagerService(  903): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=903 (0x0)
,D/PowerManagerService(  903): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=903, ws=WorkSource{10058}) (elapsedTime=3475)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/GAV4    ( 7718): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7098): mConnectivityHandler : connected
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7098): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7098): [GetString-S]
,I/ReactiveServiceManager( 7098): Supported : 1
,D/QSEECOMAPI: (  903): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: (  903): App is not loaded in QSEE
,D/QSEECOMAPI: (  903): Loaded image: APP id = 3
,D/QSEECOMAPI: (  903): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  903): QSEECom_shutdown_app, app_id = 3
E/terrier (  903): handleString: Failed to handle string(-4)
E/terrier (  903): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7098): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7098): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7098): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7098): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7098): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7098): [ensureRegistration] - No Samsung account
,I/jxcore-log( 7266): Test app app.js loaded
I/jxcore-log( 7266): 
,I/chromium( 7266): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7266): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7266): BLE advertisement is supported
I/jxcore-log( 7266): 
,I/dhcpcd  ( 7671): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  294): DCD ON
,V/AlarmManager(  903): waitForAlarm result :4
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  903): [PWL] Off : 30s ago
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  903): SIOP:: AP = 390, PST = 387, CUR = 450
,I/dhcpcd  ( 7671): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7671): wlan0: no IPv6 Routers available
,V/AlarmManager(  903): waitForAlarm result :4
,D/Finsky  ( 6620): [1075] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6620): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  903): !@Sync 3
,E/SMD     (  294): DCD ON
,D/PreloadUpdateManagerStateMachine( 7508): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7508): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7508): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7508): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7508): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7508): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7508): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7508): entry::IDLE
,V/AlarmManager(  903): waitForAlarm result :4
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2224): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2224): Vacuum at: now=1454063451574 tag=VacuumService
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2224): Scheduling Phenotype for one-off execution 11589 seconds from now (1454063451851)
,D/GetConfigurationSnapshotOperation( 2224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2224): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2224): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2224): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 2224): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 2224): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2224): (HTTPLog)-Thread-301-793820796: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2224): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 2224, getuid(): 10011
,I/qtaguid ( 2224): Tagging socket 80 with tag 1000120100000000{268440065,0} uid -1, pid: 2224, getuid(): 10011
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2224): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 2224, getuid(): 10011
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2224): Tagging socket 75 with tag 1000120100000000{268440065,0} uid -1, pid: 2224, getuid(): 10011
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  903): SIOP:: AP = 340, PST = 381, CUR = 450
,D/FactoryTest( 6667): Not factory mode
,D/FactoryTest( 6667): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6667): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6667): still no open session command from host, so toast
,W/ContextImpl( 6667): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6667): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6667): Timeline: Activity_launch_request id:com.android.settings time:111806
,E/PersonaManagerService(  903): inState():  stateMachine is null !!
,V/ApplicationPolicy(  903): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  903): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/MTPRx   ( 6667): started activity for popup
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SQLiteSecureOpenHelper( 3537): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3537): getDatabaseLocked(b,b,pwd)...
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6667): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6667): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6667): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6667): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6667): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6667): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  903): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@33bfcd56 attribute=null, token = android.os.BinderProxy@38279175
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6667): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6667): dev.kiessupport is : TRUE
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{98920fb u0 com.android.settings/.SettingsReceiverActivity t10 f}
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/ActivityManager(  903): post active user change for 0
,D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/Activity( 6667): performCreate Call secproduct feature valuefalse
D/Activity( 6667): performCreate Call debug elastic valuetrue
,I/Timeline( 7266): Timeline: Activity_idle id: android.os.BinderProxy@2a46d994 time:112433
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ActivityManager(  903): mDVFSHelper.release()
,V/AlarmManager(  903): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 50s ago
,E/SMD     (  294): DCD ON
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,D/BatteryService(  903): stay LED for fully charged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/SSRM:m  (  903): SIOP:: AP = 320, PST = 369, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/BatteryService(  903): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  903): SIOP:: AP = 300, PST = 356, CUR = 450
,E/Watchdog(  903): !@Sync 4
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  903): stay LED for fully charged
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  903): SIOP:: AP = 300, PST = 346, CUR = 450
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 75s ago
,E/SMD     (  294): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  903): SIOP:: AP = 290, PST = 339, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  903): stay LED for fully charged
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/SSRM:m  (  903): SIOP:: AP = 290, PST = 334, CUR = 450
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ClearcutLoggerApiImpl( 2224): disconnect managed GoogleApiClient
,E/Watchdog(  903): !@Sync 5
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  903): SIOP:: AP = 290, PST = 329, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 105s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,D/BatteryService(  903): stay LED for fully charged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/SSRM:m  (  903): SIOP:: AP = 290, PST = 322, CUR = 450
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  903): SIOP:: AP = 270, PST = 308, CUR = 450
,E/Watchdog(  903): !@Sync 6
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  903): SIOP:: AP = 270, PST = 296, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  903): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  903): stay LED for fully charged
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3263): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3263): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  903): [PWL] Off : 140s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  903): SIOP:: AP = 270, PST = 289, CUR = 450
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/jxcore-log( 7266): --= Surplus to requirements =--
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): ****TEST TOOK:  ms ****
I/jxcore-log( 7266): 
,I/jxcore-log( 7266): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7266): 
,D/AndroidRuntime( 8046): 
D/AndroidRuntime( 8046): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8046): CheckJNI is OFF
,D/AndroidRuntime( 8046): setted country_code = Poland
D/AndroidRuntime( 8046): setted countryiso_code = PL
D/AndroidRuntime( 8046): setted sales_code = XEO
D/AndroidRuntime( 8046): readGMSProperty: start
D/AndroidRuntime( 8046): readGMSProperty: already setted!!
D/AndroidRuntime( 8046): readGMSProperty: end
D/AndroidRuntime( 8046): addProductProperty: start
,E/AffinityControl( 8046): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8046): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  903): START PACKAGE DELETE: observer{97339305}
D/PackageManager(  903): pkg{<packageName>}
D/PackageManager(  903): user{0}
D/PackageManager(  903): caller{2000}
D/PackageManager(  903): flags{3}
D/PersonaManagerService(  903): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  903): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  903): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  903): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  903): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  903): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  903): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  903): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  903): getApplicationUninstallationEnabled
D/ApplicationPolicy(  903): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  903): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
I/ActivityManager(  903): Killing 7266:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  903):   Force finishing activity ActivityRecord{22cd78f0 u0 com.test.thalitest/.MainActivity t9}
,D/FocusedStackFrame(  903): Set to : 0
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,I/SurfaceFlinger(  257): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
I/SurfaceFlinger(  257): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/WifiService(  903): Client connection lost with reason: 4
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,I/art     ( 6387): Explicit concurrent mark sweep GC freed 28664(1590KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 435us total 27.358ms
,I/art     ( 2441): Explicit concurrent mark sweep GC freed 7768(375KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 21MB/35MB, paused 524us total 44.283ms
,I/art     ( 1556): Explicit concurrent mark sweep GC freed 165(18KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 499us total 19.037ms
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  903): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1513): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1513): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1513): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1513): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,E/SamsungIME( 1879): mOCRHelper is null
,W/ResourcesManager( 1513): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1513): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 2224): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7623): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7623): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1454063563966
,I/KLMS-2.4.503: ( 7623): MainReciver(): PACKAGE_REMOVED
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7623): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/art     (  903): Explicit concurrent mark sweep GC freed 66422(4MB) AllocSpace objects, 44(704KB) LOS objects, 31% free, 35MB/51MB, paused 4.116ms total 124.484ms
,I/art     (  903): WaitForGcToComplete blocked for 50.684ms for cause Explicit
D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SecContentProvider2(  903): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  903): mCursor = null
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/RegisteredServicesCache( 1479): empty dynamic service
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/EnterpriseDeviceManagerService(  903): Package has changed for user 0
D/EnterpriseDeviceManagerService(  903): Admin package name: com.google.android.gms
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,E/Zygote  ( 8074): MountEmulatedStorage()
I/libpersona( 8074): KNOX_SDCARD checking this for 10103
E/Zygote  ( 8074): v2
I/libpersona( 8074): KNOX_SDCARD not a persona
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ActivityManager(  903): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8074 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/SELinux ( 8074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SELinux ( 8074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider( 8074): TimaSignature is unavailable
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 8074): Added TimaKeyStore provider
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Books/Books.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/RCPManagerService(  903): PackageReceiver onReceive()
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1184): value : false
,I/HarmonyEASService(  903): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/art     (  903): Explicit concurrent mark sweep GC freed 10350(504KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 3.227ms total 175.329ms
,D/KnoxMUMContainerPolicy(  903): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/BackupManagerService(  903): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  903): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  903): uID is 10191
V/EnterpriseBillingPolicy(  903): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  903): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  903): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  903): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  903): getBillingProfileForVpnEngine - end - null
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/TaskPersister(  903): removeObsoleteFile: deleting file=9_task.xml
,D/SurfaceWidgetView( 1513): destroyHardwareResources():826181319
,V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  903): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager( 8074): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/Launcher( 1513): onRestart, Launcher: 368630767
,D/Launcher( 1513): onStart, Launcher: 368630767
D/Launcher.HomeView( 1513): onStart
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2282): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2282): [237392/6] SurfaceWidget drawing first frame
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SurfaceFlinger(  257): id=16 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14451( 8074): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8074): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8074): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8074): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 8074): ElmAgentService : onCreate()
,D/elm:14451( 8074): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8074): MainReceiver.listeningToPackageRemoved()
D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/elm:14451( 8074): MDMBridge.getInstance()
D/elm:14451( 8074): MDMBridge.getAllLicenseInfoFromSDK()
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 8094): MountEmulatedStorage()
E/Zygote  ( 8094): v2
I/libpersona( 8094): KNOX_SDCARD checking this for 10016
I/libpersona( 8094): KNOX_SDCARD not a persona
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 7266 uid 10191
,D/elm:14451( 8074): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/ActivityManager(  903): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8094 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 8094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
E/SELinux ( 8094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
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
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/elm:14451( 8074): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider( 8094): TimaSignature is unavailable
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ActivityThread( 8094): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,W/ResourcesManager(  903): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/ActivityManager(  903): Killing 5710:com.android.mms/u0a49 (adj 15): bgCount ##41
W/ResourcesManager(  903): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  903): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/PackageManager(  903): delete codoeFile: 
,I/Timeline(  903): Timeline: Activity_windows_visible id: ActivityRecord{105e07b3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:219511
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1184): value : false
,D/PackageManager(  903): result of delete: 1{97339305}
,D/ResourcesManager( 8094): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/LockPatternUtilsCache( 1184): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1184): value : false
,D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/AndroidRuntime( 8046): Shutting down VM
,D/CountryDetector(  903): No listener is left
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8094): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8094): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8094): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/PCWCLIENTTRACE_PushUtil( 7098): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7098): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7098): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7098): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  ( 8112): MountEmulatedStorage()
E/Zygote  ( 8112): v2
I/libpersona( 8112): KNOX_SDCARD checking this for 10033
I/libpersona( 8112): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8112 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 7159:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  903): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  903): onPackageRemoved : com.test.thalitest
,I/SELinux ( 8112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  903): failed to open /acct/uid_10049/pid_5710/cgroup.procs: No such file or directory
E/SELinux ( 8112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8112): TimaSignature is unavailable
,D/ActivityThread( 8112): Added TimaKeyStore provider
,W/libprocessgroup(  903): failed to open /acct/uid_10050/pid_7159/cgroup.procs: No such file or directory
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 8112): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8112): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8112): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8112): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8112): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8112): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk,
,W/ResourcesManager( 8112): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8112): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk,
,W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk,
,W/ResourcesManager( 8112): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.,
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk,
,W/ResourcesManager( 8112): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk,
,W/ResourcesManager( 8112): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk,
,W/ResourcesManager( 8112): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8112): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8112): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8129): MountEmulatedStorage()
E/Zygote  ( 8129): v2
I/libpersona( 8129): KNOX_SDCARD checking this for 10034
I/libpersona( 8129): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8129 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 8129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  903): Killing 7176:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,E/SELinux ( 8129): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  320): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 2.496ms total 30.723ms
,D/TimaKeyStoreProvider( 8129): TimaSignature is unavailable
,D/ActivityThread( 8129): Added TimaKeyStore provider
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.865ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 8ms
,D/ResourcesManager( 8129): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  903): failed to open /acct/uid_10057/pid_7176/cgroup.procs: No such file or directory
,F/libc    ( 8129): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78794fce in tid 8129 (oid.app.shealth)
,E/audit_log( 2158): File locking failed. error= Bad file number
,E/audit_log( 2158): File locking failed. error= Bad file number
,I/ActivityManager(  903): Process com.sec.android.app.shealth (pid 8129)(adj 0) has died(217,560)
,F/libc    ( 5202): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77402e6e in tid 5202 (om.sec.spp.push)
,F/libc    ( 5202): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2158): File locking failed. error= Bad file number
,I/Zygote  (  320): Process 8129 exited due to signal (7)
,I/EventHub(  903): Removing device '/dev/input/event4' due to inotify event
,I/ActivityManager(  903): Process com.sec.spp.push (pid 5202)(adj 0) has died(222,560)
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8149): MountEmulatedStorage()
I/libpersona( 8149): KNOX_SDCARD checking this for 10037
E/Zygote  ( 8149): v2
I/libpersona( 8149): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8149 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Zygote  (  320): Process 5202 exited due to signal (7)
I/EventHub(  903): Removing device '/dev/input/event5' due to inotify event
,I/SELinux ( 8149): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,I/EventHub(  903): Removing device '/dev/input/event6' due to inotify event
,E/SELinux ( 8149): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8149): TimaSignature is unavailable
,D/ActivityThread( 8149): Added TimaKeyStore provider
,D/ResourcesManager( 8149): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/        ( 8149): Zip: read 65557 failed: I/O error
W/zipro   ( 8149): Error opening archive /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk: I/O Error
D/asset   ( 8149): failed to open Zip archive '/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk'
,W/ContextImpl( 8149): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8149): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  903): Removing device '/dev/input/event7' due to inotify event
,W/        ( 8149): Zip: read 65557 failed: I/O error
,W/        ( 8149): Zip: read 65557 failed: I/O error
,D/ResourcesManager( 8149): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,F/libc    ( 8149): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa188c93d in tid 8149 (moteNotiProcess)
,F/libc    ( 8149): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2158): File locking failed. error= Bad file number
,I/ActivityManager(  903): Process com.sec.spp.push:RemoteNotiProcess (pid 8149)(adj 0) has died(221,560)
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8164): MountEmulatedStorage()
E/Zygote  ( 8164): v2
I/libpersona( 8164): KNOX_SDCARD checking this for 10041
I/libpersona( 8164): KNOX_SDCARD not a persona
,I/EventHub(  903): Removing device '/dev/input/event8' due to inotify event
,I/Zygote  (  320): Process 8149 exited due to signal (7)
,I/ActivityManager(  903): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8164 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 8164): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
E/SELinux ( 8164): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8164): TimaSignature is unavailable
,D/ActivityThread( 8164): Added TimaKeyStore provider
,I/EventHub(  903): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager( 8164): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/        ( 8164): Zip: read 65557 failed: I/O error
W/zipro   ( 8164): Error opening archive /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk: I/O Error
D/asset   ( 8164): failed to open Zip archive '/system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk'
W/ContextImpl( 8164): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 8164): Unable to setupGraphicsSupport due to missing cache directory
D/ResourcesManager( 8164): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,F/libc    ( 8164): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73706aae in tid 8164 (sdk.samsunglink)
F/libc    ( 8164): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2158): File locking failed. error= Bad file number
,I/ActivityManager(  903): Process com.samsung.android.sdk.samsunglink (pid 8164)(adj 0) has died(221,560)
,I/SA      ( 7138): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7138): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10191 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/EventHub(  903): Removing device '/dev/input/event10' due to inotify event
,F/libc    ( 1814): Fatal signal 7 (SIGBUS), code 2, fault addr 0x776f8e10 in tid 1877 (ContactsProvide)
,F/libc    ( 1814): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2158): File locking failed. error= Bad file number
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8184): MountEmulatedStorage()
I/libpersona( 8184): KNOX_SDCARD checking this for 10047
E/Zygote  ( 8184): v2
I/libpersona( 8184): KNOX_SDCARD not a persona
I/Zygote  (  320): Process 8164 exited due to signal (7)
,I/ActivityManager(  903): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8184 uid=10047 gids={50047, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 8184): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,I/EventHub(  903): Removing device '/dev/input/event11' due to inotify event
E/SELinux ( 8184): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Process android.process.acore (pid 1814)(adj 0) has died(225,561)
,W/ActivityManager(  903): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,D/TimaKeyStoreProvider( 8184): TimaSignature is unavailable
,D/ActivityThread( 8184): Added TimaKeyStore provider
,I/Zygote  (  320): Process 1814 exited due to signal (7)
,D/ResourcesManager( 8184): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8184): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8184): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8184): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8184): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8184): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 8184): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8184): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8184): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 8184): Unable to create files subdir /data/data/com.sec.android.gallery3d/cache
E/ActivityThread( 8184): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8184): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb5019000 in tid 8184 (droid.gallery3d)
,F/libc    ( 8184): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2158): File locking failed. error= Bad file number
,I/ActivityManager(  903): Process com.sec.android.gallery3d (pid 8184)(adj 0) has died(225,561)
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8199): MountEmulatedStorage()
E/Zygote  ( 8199): v2
I/libpersona( 8199): KNOX_SDCARD checking this for 10049
I/libpersona( 8199): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8199 uid=10049 gids={50049, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/Zygote  (  320): Process 8184 exited due to signal (7)
,I/SELinux ( 8199): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 8199): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8199): TimaSignature is unavailable
,D/ActivityThread( 8199): Added TimaKeyStore provider
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/ResourcesManager( 8199): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8199): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8199): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8199): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8199): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8199): Unable to create files subdir /data/data/com.android.mms/cache
E/ActivityThread( 8199): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8199): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb5023000 in tid 8199 (com.android.mms)
F/libc    ( 8199): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2158): File locking failed. error= Bad file number
,I/ActivityManager(  903): Process com.android.mms (pid 8199)(adj 0) has died(225,561)
,I/TactileAssist(  903): enable value -1
,I/TactileAssist(  903): internal enable value -1
I/TactileAssist(  903): intensity value -1
I/TactileAssist(  903): saveAppList value true
,I/TactileAssist(  903): List of disabled apps :
,E/SharedPreferencesImpl(  903): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0

```
