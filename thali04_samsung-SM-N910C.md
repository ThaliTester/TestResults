#### Test 6012434713fea37_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
D/MyFiles (10028): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
E/installd( 2860): system dir 0 : /system/app/
E/installd( 2860): system dir 1 : /system/priv-app/
E/installd( 2860): system dir 2 : /vendor/app/
E/installd( 2860): system dir 3 : /oem/app/
I/TactileAssist( 3524): enable value -1
I/TactileAssist( 3524): internal enable value -1
I/TactileAssist( 3524): intensity value -1
I/TactileAssist( 3524): saveAppList value true
I/TactileAssist( 3524): List of disabled apps :
--------- beginning of system
D/PackageManager( 3524): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10046): MountEmulatedStorage()
E/Zygote  (10046): v2
I/SELinux (10046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10046): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/libpersona(10046): KNOX_SDCARD checking this for 10059
I/libpersona(10046): KNOX_SDCARD not a persona
I/ActivityManager( 3524): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10046 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9378:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 788us total 11.746ms
D/TimaKeyStoreProvider(10046): TimaSignature is unavailable
D/ActivityThread(10046): Added TimaKeyStore provider
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 443us total 8.880ms
D/ResourcesManager(10046): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager(10046): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 664us total 8.855ms
D/Compatibility(10046): onReceive() it will make start service
D/Compatibility(10046): onHandleIntent()
D/Compatibility(10046): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10688, android.intent.extra.user_handle=0}]
D/Compatibility(10046): found: 2
D/Compatibility(10046): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10046): skipping ResolveInfo{5148a57 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10046): considering ResolveInfo{22f9944 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10046): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10046): enabling receiver ResolveInfo{3d8f2a2d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/UpdateIcingCorporaServi( 4034): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/Compatibility(10046): enabling receiver ResolveInfo{209cdb62 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility(10046): enabling receiver ResolveInfo{3d6d74f3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility(10046): enabling receiver ResolveInfo{282f05b0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility(10046): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/Zygote  (10066): MountEmulatedStorage()
E/Zygote  (10066): v2
I/SELinux (10066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/libpersona(10066): KNOX_SDCARD checking this for 1000
I/libpersona(10066): KNOX_SDCARD not a persona
I/ActivityManager( 3524): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=10066 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9394:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/TimaKeyStoreProvider(10066): TimaSignature is unavailable
D/ResourcesManager( 4034): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ActivityThread(10066): Added TimaKeyStore provider
D/ResourcesManager(10066): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
W/ContextImpl(10066): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2994 
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10084): MountEmulatedStorage()
E/Zygote  (10084): v2
I/libpersona(10084): KNOX_SDCARD checking this for 10101
I/libpersona(10084): KNOX_SDCARD not a persona
I/SELinux (10084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10084): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10084 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9409:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(10084): TimaSignature is unavailable
D/ActivityThread(10084): Added TimaKeyStore provider
D/ResourcesManager( 8120): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ResourcesManager(10084): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/UpdateIcingCorporaServi( 4034): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
D/DocsApplication(10084): Installing DEX configuration.
D/DexInstaller(10084): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper(10084): Provided clientMode=RELEASE, packageInfo=PackageInfo{336f17d6 com.google.android.apps.docs}
D/TAG     (10084): onCreate()
D/CrossAppStateProvider(10084): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/AndroidRuntime(10082): 
D/AndroidRuntime(10082): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10082): CheckJNI is OFF
D/AndroidRuntime(10082): readGMSProperty: start
D/AndroidRuntime(10082): readGMSProperty: already setted!!
D/AndroidRuntime(10082): readGMSProperty: end
D/AndroidRuntime(10082): addProductProperty: start
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/AffinityControl(10082): AffinityControl: registerfunction enter
D/AndroidRuntime(10082): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3524): mDVFSHelper.acquire()
D/FocusedStackFrame( 3524): Set to : 0
D/Launcher.HomeView( 4000): onPause
D/Launcher( 4000): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime(10082): Shutting down VM
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  (10109): MountEmulatedStorage()
I/libpersona(10109): KNOX_SDCARD checking this for 10688
E/Zygote  (10109): v2
I/libpersona(10109): KNOX_SDCARD not a persona
I/SELinux (10109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10109): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10109 uid=10688 gids={50688, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SurfaceFlinger( 2851): id=11 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider(10109): TimaSignature is unavailable
D/ActivityThread(10109): Added TimaKeyStore provider
D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 4000): updateVisibility : ActivityRecord{3267b818 token=android.os.BinderProxy@35f08dea {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3524): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/MicrophoneInputStream( 4034): mic_close gfk@2daa2120
V/ActivityManager( 3524): Display changed displayId=0
D/Launcher.HomeView( 4000): onStop
V/ActivityThread( 4000): updateVisibility : ActivityRecord{3267b818 token=android.os.BinderProxy@35f08dea {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
V/AudioPolicyManager( 2856): stopInput() input 19
V/AudioPolicyManager( 2856): releaseInput() 19
V/AudioPolicyManager( 2856): closeInput(19)
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
I/HotwordRecognitionRnr( 4034): Stopping hotword detection.
I/HotwordRecognitionRnr( 4034): Hotword detection finished
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AudioHardwareTinyALSA( 2856): Entering AudioStreamInALSA standby mode
I/AudioHardwareTinyALSA( 2856): Close mHandle:b00a9600
D/Launcher( 4000): onTrimMemory. Level: 20
D/ResourcesManager(10109): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/AudioHardwareTinyALSA( 2856): closeInputStream +
D/TinyUCM ( 2856): Disable Input dev(0x80000004)
D/TinyUCM ( 2856): set channel: None
D/AudioHardwareTinyALSA( 2856): Entering AudioStreamInALSA standby mode
V/AudioPolicyManager( 2856): releaseInput() exit
D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/GAV2    (10084): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/WebViewFactory(10109): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10109): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
E/Zygote  (10133): MountEmulatedStorage()
I/libpersona(10133): KNOX_SDCARD checking this for 10102
E/Zygote  (10133): v2
I/libpersona(10133): KNOX_SDCARD not a persona
I/SELinux (10133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/com.sec.android.app.automotive.carmode.framework.manager.update.UpdateManagerReceiver: pid=10133 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
E/SELinux (10133): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/LibraryLoader(10109): Loading: webviewchromium
I/LibraryLoader(10109): Time to load native libraries: 2 ms (timestamps 1706-1708)
I/LibraryLoader(10109): Expected native library version number "",actual native library version number ""
D/TimaKeyStoreProvider(10133): TimaSignature is unavailable
D/ActivityThread(10133): Added TimaKeyStore provider
V/WebViewChromiumFactoryProvider(10109): Binding Chromium to main looper Looper (main, tid 1) {1f606d4f}
I/LibraryLoader(10109): Expected native library version number "",actual native library version number ""
I/chromium(10109): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/ResourcesManager(10133): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager(10133): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/BrowserStartupController(10109): Initializing chromium process, renderers=0
W/art     (10109): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10109): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10109): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10109): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10109): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10109): 393661660: getState() :  mService = null. Returning STATE_OFF
,E/[CarMode](10133): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager(10133): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(10133): mContext is not null
,I/VlingoAndroidCore(10133): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,W/chromium(10109): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10109): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,E/Zygote  (10183): MountEmulatedStorage()
I/libpersona(10183): KNOX_SDCARD checking this for 10034
E/Zygote  (10183): v2
I/libpersona(10183): KNOX_SDCARD not a persona
I/SELinux (10183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10183): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=10183 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10183): TimaSignature is unavailable
,D/ActivityThread(10183): Added TimaKeyStore provider
,W/art     (10109): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10109): onDetachedFromWindow called when already detached. Ignoring
,D/ResourcesManager(10183): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/SystemWebViewEngine(10109): CordovaWebView is running on device made by: samsung
,W/art     (10109): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10109): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10109): performCreate Call secproduct feature valuefalse
D/Activity(10109): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10109): Render dirty regions requested: true
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,I/System.out(10183): Inside WakeupProvider
,E/DatabaseUtils(10183): Writing exception to parcel
E/DatabaseUtils(10183): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(10183): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(10183): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(10183): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(10183): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(10183): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(10183): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(10183): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(10183): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(10183): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(10183): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err(10133): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err(10133): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10133): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(10133): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10133): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10133): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10133): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10133): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10133): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10133): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(10133): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(10133): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(10133): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(10133): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(10133): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(10133): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10133): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(10133): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10133): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10133): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10133): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10133): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10133): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10133): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils(10183): Writing exception to parcel
E/DatabaseUtils(10183): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(10183): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(10183): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(10183): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(10183): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(10183): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(10183): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(10183): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(10183): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(10183): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(10183): 	at android.os.Binder.execTransact(Binder.java:446)
I/SurfaceFlinger( 2851): id=12 createSurf (1x1),1 flag=404, NainActivit
I/VlingoApplication(10183): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
W/System.err(10133): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(10133): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10133): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(10133): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10133): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10133): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10133): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10133): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10133): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10133): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(10133): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(10133): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(10133): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(10133): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10133): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(10133): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10133): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10133): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10133): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10133): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10133): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10133): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode](10133): [DLApplication]-Init Called!:false
W/[CarMode](10133): [CommonUtil]-=========================================
W/[CarMode](10133): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](10133): [CommonUtil]-=========================================
E/[CarMode](10133): [DLApplication]-Init Started!:true
I/[CarModeFW](10133): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](10133): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](10133): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](10133): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](10133): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](10133): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](10133): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](10133): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](10133): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](10133): ### android.os.Looper::loop(145)
I/[CarModeFW](10133): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](10133): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](10133): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](10133): ### com.android.internal.os.ZygoteInit::main(1194)
I/OpenGLRenderer(10109): Initialized EGL, version 1.4
I/OpenGLRenderer(10109): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279827696 
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
D/OpenGLRenderer(10109): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10109): Enabling debug mode 0
D/mali_winsys(10109): new_window_surface returns 0x3000,  [1440x2560]-format:1
D/BluetoothAdapter(10183): 497498848: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(10183): 497498848: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(10183): 497498848: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore(10183): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
,I/MessageDataHandler(10133): initialize
D/[CarModeFW](10133): CDH-initiazlieCaches : before sync
D/[CarModeFW](10133): CDH-initiazlieCaches : after sync
D/BluetoothAdapter(10133): 930560310: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(10133): 930560310: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW](10133): DrivingManager-initialize...
I/SensorService( 3524): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3524): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3524): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3524): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3524): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
D/[CarModeFW](10133): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW](10133): CDH-ContactDataHandler initiazlieCaches time : 26
D/[CarModeFW](10133): CDH-initiazlieCaches : end sync
,D/VlingoApplication(10183): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication(10183): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow(10183): initQueue()
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3524): Displayed com.test.thalitest/.MainActivity: +434ms
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/Timeline(10109): Timeline: Activity_idle id: android.os.BinderProxy@3d8f2a2d time:71984
,I/MediaPlayer(10133): Need to enable context aware info
V/MediaPlayer-JNI(10133): native_setup
V/MediaPlayer(10133): constructor
,V/MediaPlayer(10133): setListener
,D/[CarModeFW](10133): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW](10133): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode](10133): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457574310995
D/[CarMode](10133): [DLServiceManager]-updateLocationList
D/[CarMode](10133): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457574310995
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457574310995
D/[CarModeFW](10133): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457574310996
,D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457574310997
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457574310997
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457574310997
F/DLApplication(10133): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
I/[CarMode](10133): [LogNotNull]-Package name is: com.here.app.maps
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 3984): query,matched:2, calling pid = 10133
D/TP/SmsProvider( 3984): match 2:Elapsed time : 1.477 ms
D/[CarModeFW](10133): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 11
D/[CarModeFW](10133): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 15
E/Zygote  (10233): MountEmulatedStorage()
E/Zygote  (10233): v2
I/libpersona(10233): KNOX_SDCARD checking this for 10047
I/libpersona(10233): KNOX_SDCARD not a persona
D/[CarModeFW](10133): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 19
I/SELinux (10233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=10233 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (10233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10233): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/[CarMode](10133): [DLApplication]-Init End!:true
D/[CarMode](10133): [TAG]-phone sound mode is: 0
V/[CarMode](10133): [DLApplication]-savePreviousGpsState
D/MessageDataHandler(10133):  getInboxList smsCursor : 25
D/[CarModeFW](10133): CalllogDataHandler-getCalllogList : cur len = 0
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 29
D/TP/SmsProvider( 3984): query,matched:2, calling pid = 10133
,D/TP/SmsProvider( 3984): match 2:Elapsed time : 0.889 ms
D/TP/MmsProvider( 3984): Query uri=content://mms/inbox, match=2, calling pid = 10133
V/[CarMode](10133): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/JsMessageQueue(10109): Set native->JS mode to OnlineEventsBridgeMode
D/MessageDataHandler(10133):  getInboxList mmsCursor : 12
,D/MessageDataHandler(10133):  getInboxList mms,sms cursor join : 3
,D/TimaKeyStoreProvider(10233): TimaSignature is unavailable
,D/ActivityThread(10233): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3984): query,matched:0, calling pid = 10133
V/TP/MmsSmsProvider( 3984): getSimpleConversations entered.
,D/[CarMode](10133): [DLApplication]-GooglePlayServices SUCCESS.
D/TP/MmsProvider( 3984): Query uri=content://mms, match=0, calling pid = 10133
E/[CarMode](10133): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/TP/MmsSmsProvider( 3984): match 0:Elapsed time : 1.589 ms
,I/[CarMode](10133): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode](10133): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,I/MessageDataHandler(10133): getUnreadMessageCount :0
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 55
,D/TP/MmsSmsProvider( 3984): query,matched:13, calling pid = 10133
,I/UpdateManagerReceiver(10133): Intent : android.intent.action.PACKAGE_ADDEDThu Mar 10 02:45:11 GMT+01:00 2016
,D/ResourcesManager(10233): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,D/TP/MmsSmsProvider( 3984): match 13:Elapsed time : 2.760 ms
W/ResourcesManager(10233): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/DialogFlow(10133): initQueue()
,E/Zygote  (10248): MountEmulatedStorage()
E/Zygote  (10248): v2
I/libpersona(10248): KNOX_SDCARD checking this for 1000
I/libpersona(10248): KNOX_SDCARD not a persona
,I/SELinux (10248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/chromium(10109): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10109): 
,I/SELinux (10248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=10248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10248): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9542:com.sec.android.app.music:service/u0a44 (adj 13): bgCount ##31
,I/ActivityManager( 3524): Killing 9504:com.samsung.dcm:DCMService/u0a4 (adj 13): bgCount ##32
I/ActivityManager( 3524): Killing 9424:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##33
,I/SurfaceFlinger( 2851): id=8 Removed Mauncher (4/9)
,I/SurfaceFlinger( 2851): id=8 Removed Mauncher (-2/9)
,W/GAV2    (10084): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 3524): Killing 9216:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
,I/CalendarProvider2(10233): CalendarProvider2.onCreate() called
,D/MessageDataHandler(10133):  getInboxList address cursor : 42
,D/TP/MmsSmsProvider( 3984): query,matched:0, calling pid = 10133
V/TP/MmsSmsProvider( 3984): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3984): match 0:Elapsed time : 1.939 ms
,D/MessageDataHandler(10133):  getInboxList thread cursor : 7
,D/MessageDataHandler(10133):  thread, addr result: 6
I/[CarModeFW](10133): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 112
I/[CarModeFW](10133): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 112
,D/TimaKeyStoreProvider(10248): TimaSignature is unavailable
,D/ActivityThread(10248): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger( 2851): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger( 2851): id=11 Removed uhalitest (-2/8)
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 209642(13MB) AllocSpace objects, 2(3MB) LOS objects, 24% free, 48MB/64MB, paused 1.349ms total 103.344ms
,D/ResourcesManager(10248): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/jxcore_app_log(10109): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1359522048
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(10109): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(10109):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(10109):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(10109):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(10109):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(10109): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c21f4b added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109): setBluetoothMacAddress: E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(10109): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10109): setIdentityString: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(10109): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(10109): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Bluetooth MAC address: E0:DB:10:14:E2:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bde5be6 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel(10109): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10109): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,D/WifiService( 3524): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10109): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(10109): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10109): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10109): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,W/ContextImpl(10248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10274): MountEmulatedStorage()
E/Zygote  (10274): v2
I/libpersona(10274): KNOX_SDCARD checking this for 10121
I/libpersona(10274): KNOX_SDCARD not a persona
,I/System.out(10183): INFO:Resource not found:/Common.properties Using default values
,D/ResourcesManager(10248): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/ActivityManager( 3524): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=10274 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux (10274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/chromium(10109): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SELinux (10274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/FilterInstaller(10248): installFilters
,I/Icing   ( 4500): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,E/FilterInstaller(10248): There is no requred permission
,D/[CarModeFW](10133): LocationDataHandler-No schedules found.
,D/TimaKeyStoreProvider(10274): TimaSignature is unavailable
,D/ActivityThread(10274): Added TimaKeyStore provider
,D/[CarModeFW](10133): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10274): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,E/Zygote  (10294): MountEmulatedStorage()
E/Zygote  (10294): v2
I/libpersona(10294): KNOX_SDCARD checking this for 10003
I/libpersona(10294): KNOX_SDCARD not a persona
,I/SELinux (10294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/PackageIntentReceiver(10274): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(10274): Not GearManger package! 
,I/ActivityManager( 3524): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=10294 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,I/SELinux (10294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10294): TimaSignature is unavailable
,E/Zygote  (10309): MountEmulatedStorage()
E/Zygote  (10309): v2
I/libpersona(10309): KNOX_SDCARD checking this for 1000
I/libpersona(10309): KNOX_SDCARD not a persona
I/SELinux (10309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SELinux (10309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10309): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=10309 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(10294): Added TimaKeyStore provider
,I/ActivityManager( 3524): Killing 8753:com.google.android.gm/u0a122 (adj 15): bgCount ##31
I/ActivityManager( 3524): Killing 8633:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,D/ResourcesManager(10294): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/TimaKeyStoreProvider(10309): TimaSignature is unavailable
D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@2
,D/ActivityThread(10309): Added TimaKeyStore provider
W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{38799a82 u0 com.test.thalitest/.MainActivity t27} time:72375
D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@6
,D/UserAnalysis.PlaceProvider(10294): PlaceProvider onCreate()
,D/ResourcesManager(10309): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/UserAnalysis.SecureDbManager(10294): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(10294): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(10294): Create SecureDbHelper
,D/IntelligenceServiceApplication(10294): onCreate()
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10327): MountEmulatedStorage()
E/Zygote  (10327): v2
I/libpersona(10327): KNOX_SDCARD checking this for 1000
I/libpersona(10327): KNOX_SDCARD not a persona
,I/SELinux (10327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10327 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9457:com.google.android.music:main/u0a135 (adj 15): bgCount ##31
,I/SELinux (10327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10327): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW](10133): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](10133): MyPlaceProvider-=============
D/[CarModeFW](10133): MyPlaceProvider-=============
,D/[CarModeFW](10133): MyPlaceProvider-=============
D/[CarModeFW](10133): MyPlaceProvider-=============
D/[CarModeFW](10133): MyPlaceProvider-=============
D/[CarModeFW](10133): MyPlaceProvider-=============
D/[CarModeFW](10133): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](10133): MyPlaceProvider-==============
,D/[CarModeFW](10133): MyPlaceProvider-==============
D/[CarModeFW](10133): MyPlaceProvider-==============
D/[CarModeFW](10133): MyPlaceProvider-==============
D/[CarModeFW](10133): MyPlaceProvider-==============
I/art     ( 2882): Explicit concurrent mark sweep GC freed 8790(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 5.536ms total 17.075ms
,D/[CarModeFW](10133): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457574311471 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW](10133): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(10133): loadLocationDestinationList is null
D/[CarModeFW](10133): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 476
,D/TimaKeyStoreProvider(10327): TimaSignature is unavailable
,D/ActivityThread(10327): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 496us total 9.996ms
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 613us total 11.030ms
,I/Icing   ( 4500): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,D/ResourcesManager(10327): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AcmsPackageEventListener(10327): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl(10327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10345): MountEmulatedStorage()
E/Zygote  (10345): v2
I/libpersona(10345): KNOX_SDCARD checking this for 10147
I/libpersona(10345): KNOX_SDCARD not a persona
,I/SELinux (10345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10345 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (10345): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9003:com.android.vending/u0a31 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/9003/oom_score_adj; errno=22
,D/AcmsService(10327): Enter Oncreate
D/AcmsServiceMonitor(10327): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10327): creating AcmsCore
D/AcmsCore(10327): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10327): AcmsCore
,D/AcmsCore(10327): init
D/AcmsCore(10327): Looper handler is not null
D/AcmsCore(10327): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10327): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10327): Incrementing - Counter value: 1
D/AcmsCore(10327): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(10327): onStartCommand
D/AcmsService(10327): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(10327): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10327): Incrementing - Counter value: 2
D/AcmsService(10327): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr(10327): AcmsCertificateMngr
,D/ActivityThread(10327): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr(10327): AcmsRevocationMngr
,D/TimaKeyStoreProvider(10345): TimaSignature is unavailable
,D/ActivityThread(10345): Added TimaKeyStore provider
,D/ResourcesManager(10345): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(10345): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService(10327): Inside handle Intent
D/AcmsService(10327): App added - package name: com.test.thalitest
D/AcmsCore(10327): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10327): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10327): Incrementing - Counter value: 3
D/AcmsCore(10327): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(10327): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(10327): Decrementing - Counter value: 2
,D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@6
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 8369): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10382): MountEmulatedStorage()
E/Zygote  (10382): v2
I/libpersona(10382): KNOX_SDCARD checking this for 10183
I/libpersona(10382): KNOX_SDCARD not a persona
,I/SELinux (10382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=10382 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10382): TimaSignature is unavailable
,D/ActivityThread(10382): Added TimaKeyStore provider
,D/ResourcesManager(10382): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,V/AlarmManager( 3524): waitForAlarm result :8
,E/SQLiteLog(10382): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10399): MountEmulatedStorage()
E/Zygote  (10399): v2
I/libpersona(10399): KNOX_SDCARD checking this for 10190
I/libpersona(10399): KNOX_SDCARD not a persona
,I/SELinux (10399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10399 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10399): TimaSignature is unavailable
,D/ActivityThread(10399): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10399): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10399): onReceive()
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10399): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils(10399): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10399): Widget is not attached.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10418): MountEmulatedStorage()
I/libpersona(10418): KNOX_SDCARD checking this for 10010
E/Zygote  (10418): v2
I/libpersona(10418): KNOX_SDCARD not a persona
,I/SELinux (10418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10418): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.facebook.system for broadcast com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver: pid=10418 uid=10010 gids={50010, 9997} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9600:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10418): TimaSignature is unavailable
,D/ActivityThread(10418): Added TimaKeyStore provider
,E/Watchdog( 3524): !@Sync 2
,D/ResourcesManager(10418): creating new AssetManager and set to /data/app/com.facebook.system-1/base.apk
,I/ActivityManager( 3524): Killing 9796:com.sec.android.app.camera/u0a168 (adj 15): bgCount ##31
,D/PackageBroadcastService( 4500): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 4500): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4500): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4500): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4500): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4500): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4500): Submit a task: k
,D/ChimeraCfgMgr( 4500): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 4500): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 4500): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/GassUtils( 4500): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4500): Found info for package com.test.thalitest in db.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10442): MountEmulatedStorage()
E/Zygote  (10442): v2
I/libpersona(10442): KNOX_SDCARD checking this for 10031
I/libpersona(10442): KNOX_SDCARD not a persona
,I/SELinux (10442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10442): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10442 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10442): TimaSignature is unavailable
,D/ActivityThread(10442): Added TimaKeyStore provider
,D/ResourcesManager(10442): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/AlarmManager( 3524): waitForAlarm result :8
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  (10442): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/jxcore-log(10109): Initializing JXcore engine
W/jxcore-log(10109): JXcore engine is ready
,D/Finsky  (10442): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/auditd  ( 4527): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3524): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3524): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/Settings(10442): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10442): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/jxcore-log(10109): Starting JXcore engine
,I/System.out(10442): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(10442): (HTTPLog)-Static: isShipBuild true
I/System.out(10442): (HTTPLog)-Thread-1423-448192786: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(10442): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/Ads     (10442): Skipping gmscore version check
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (10486): MountEmulatedStorage()
E/Zygote  (10486): v2
I/libpersona(10486): KNOX_SDCARD checking this for 10114
I/libpersona(10486): KNOX_SDCARD not a persona
,I/SELinux (10486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10486): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.feed.platformads.AppInstallReceiver: pid=10486 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/CalendarProvider2(10233): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/Finsky  (10442): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10442): [1] Libraries$2.run: Finished loading 1 libraries.
,W/jxcore-log(10109): Platform android
W/jxcore-log(10109): 
I/ActivityManager( 3524): Killing 9811:com.sec.android.widgetapp.digitalclock/u0a97 (adj 15): bgCount ##31
W/jxcore-log(10109): Process ARCH arm
W/jxcore-log(10109): 
,D/TimaKeyStoreProvider(10486): TimaSignature is unavailable
,D/ActivityThread(10486): Added TimaKeyStore provider
,D/Finsky  (10442): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ResourcesManager(10486): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/Finsky  (10442): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  (10442): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 3524): Killing 9826:com.sec.android.widgetapp.dualclockdigital/u0a105 (adj 15): bgCount ##31
,W/ResourcesManager(10486): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AppStateLoggerExceptionHandler(10486): Installed uncaught exception handler for app state logging
D/AppStateLogger(10486): Attempting to open app state logging file
D/AppStateLogger(10486): Successfully opened app state logging file: /data/data/com.facebook.katana/app_state_logs/51608fba-7d5b-10c3-825a-444db3f9cc69.txt
D/ACRA    (10486): ACRA is enabled for com.facebook.katana, intializing...
V/fb-UnpackingSoSource(10486): locked dso store /data/data/com.facebook.katana/lib-main
I/fb-UnpackingSoSource(10486): dso store is up-to-date: /data/data/com.facebook.katana/lib-main
V/fb-UnpackingSoSource(10486): releasing dso store lock for /data/data/com.facebook.katana/lib-main
V/fb-UnpackingSoSource(10486): locked dso store /data/data/com.facebook.katana/lib-assets
I/fb-UnpackingSoSource(10486): dso store is up-to-date: /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource(10486): releasing dso store lock for /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource(10486): locked dso store /data/data/com.facebook.katana/lib-xzs
I/fb-UnpackingSoSource(10486): dso store is up-to-date: /data/data/com.facebook.katana/lib-xzs
V/fb-UnpackingSoSource(10486): releasing dso store lock for /data/data/com.facebook.katana/lib-xzs
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/art     (10486): Thread[1,tid=10486,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.katana-2/lib/arm/libfbjni.so"
V/appstatelogger(10486): Registered App State Logger stream with Breakpad
V/MemoryEnlargementHack(10486): largeHeap already enabled in manifest
V/DexLibLoader(10486): DLL.loadAll betaBuild:false flags:0x00000004
V/dalvik-internals(10486): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals(10486): hooked signal using trap ()
V/dalvik-internals(10486): hooked sysv_signal using trap ()
V/dalvik-internals(10486): hooked bsd_signal using trap ()
V/dalvik-internals(10486): hooked sigaction using jump ()
V/dalvik-internals(10486): hooked _ZN3art6mirror5Class19FindInterfaceMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals(10486): hooked _ZN3art6mirror5Class25FindDeclaredVirtualMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals(10486): hooked _ZN3art6mirror5Class17FindVirtualMethodEPKNS0_8DexCacheEj using jump ()
D/DexLibLoader(10486): patched ART 5.0.x miranda bug
V/DexLibLoader(10486): opening dex store /data/data/com.facebook.katana/dex
V/DexLibLoader(10486): Secondary program dex metadata: [.root_relative]
V/DexLibLoader(10486): Secondary program dex metadata: [.locators]
V/DexLibLoader(10486): Secondary program dex metadata: [classes2.dex 102b05d6536f178eac593d7d65578de2ddd6825a secondary.dex01.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes3.dex 857a97620767f7e63fa9c0527067cd6c7a002041 secondary.dex02.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes4.dex 9935231bfc9137654b613e0c3ad23e5d3c069eb5 secondary.dex03.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes5.dex 08fa37bfdbdd915e303997b9b9eee7d09b51c215 secondary.dex04.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes6.dex 82b91dbe59da3b655a867a417fbb83d9fc617838 secondary.dex05.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes7.dex a8a078ec908ddaee0545b2315081ac33b68f213a secondary.dex06.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes8.dex 294c9ad6031509e29eb40eb619940d45eeb3c245 secondary.dex07.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes9.dex 43850a0126da4bbcbaf22e20c7357a75cf3a71aa secondary.dex08.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes10.dex 3c65d9974656bb0f434d5d9e03c6534a2f64b58a secondary.dex09.Canary]
V/DexLibLoader(10486): Secondary program dex metadata: [classes11.dex 5501f6915e13d4353ae2cf4cb583284b418d46c4 secondary.dex10.Canary]
V/DexLibLoader(10486): read status:9 check:faceb007faceb00e
V/DexLibLoader(10486): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader(10486): verified deps file
I/DexLibLoader(10486): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
V/MultiDexClassLoader(10486): installing MultiDexClassLoader before application classloader
D/MultiDexClassLoader(10486): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10486): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader(10486): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10486): Setup multi dex took 1 ms.
V/DexLibLoader(10486): optimization needed: no
D/MemoryReductionHack(10486): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
I/jxcore-log(10109): JXcore Cordova bridge is ready!
I/jxcore-log(10109): 
W/jxcore-log(10109): JXcore engine is started
I/org.thaliproject.p2p.ThaliPermissions(10109): execute: REQUEST_ACCESS_COARSE_LOCATION
I/GMPM    (10486): App measurement is starting up
E/GMPM    (10486): getGoogleAppId failed with status: 10
E/GMPM    (10486): Uploading is not possible. App measurement disabled
W/StaticBindingVerifier(10486): Verify
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/LightSharedPreferencesImpl(10486): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(10486): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10486): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(10486): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(10486): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl(10486): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl(10486): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(10486): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl(10486): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl(10486): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(10486): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(10486): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl(10486): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(10486): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10486): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(10486): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(10486): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(10486): 	... 10 more
D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4244, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-531, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1089
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/art     ( 3524): Explicit concurrent mark sweep GC freed 20272(1210KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.554ms total 84.018ms
D/WifiService( 3524): New client listening to asynchronous messages
W/fb4a(:<default>):UserScope(10486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope(10486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope(10486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
V/xAnalytics(10486): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics(10486): JNI_OnLoad XAnalyticsNative entered
V/xAnalytics(10486): JNI_OnLoad XAnalyticsNative complete
V/xAnalytics(10486): tigon: 0x0 - xanalytics: 0xffffffff93314280
V/xAnalytics(10486): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
V/xAnalytics(10486): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     (10486): Attempt to remove local handle scope entry from IRT, ignoring
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (10547): MountEmulatedStorage()
I/libpersona(10547): KNOX_SDCARD checking this for 10110
E/Zygote  (10547): v2
I/libpersona(10547): KNOX_SDCARD not a persona
I/SELinux (10547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10547): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=10547 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9856:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(10547): TimaSignature is unavailable
D/ActivityThread(10547): Added TimaKeyStore provider
D/ResourcesManager(10547): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Icing   ( 4500): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
V/fb-UnpackingSoSource(10547): locked dso store /data/data/com.facebook.appmanager/lib-main
I/fb-UnpackingSoSource(10547): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(10547): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(10547): locked dso store /data/data/com.facebook.appmanager/lib-assets
I/fb-UnpackingSoSource(10547): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(10547): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(10547): locked dso store /data/data/com.facebook.appmanager/lib-xzs
I/fb-UnpackingSoSource(10547): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource(10547): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
D/ACRA    (10547): ACRA is enabled for com.facebook.appmanager, intializing...
V/DexLibLoader(10547): DLL.loadAll betaBuild:true flags:0x00000001
V/dalvik-internals(10547): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals(10547): hooked signal using trap ()
V/dalvik-internals(10547): hooked sysv_signal using trap ()
V/dalvik-internals(10547): hooked bsd_signal using trap ()
V/dalvik-internals(10547): hooked sigaction using jump ()
V/DexLibLoader(10547): opening dex store /data/data/com.facebook.appmanager/dex
V/DexLibLoader(10547): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
V/DexLibLoader(10547): read status:9 check:faceb007faceb00e
V/DexLibLoader(10547): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader(10547): verified deps file
I/DexLibLoader(10547): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
V/MultiDexClassLoader(10547): installing MultiDexClassLoader before application classloader
D/MultiDexClassLoader(10547): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader(10547): Setup multi dex took 1 ms.
V/DexLibLoader(10547): optimization needed: no
D/ResourcesManager( 4500): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/GMPM    (10547): App measurement is starting up
,E/GMPM    (10547): getGoogleAppId failed with status: 10
,E/GMPM    (10547): Uploading is not possible. App measurement disabled
,W/cn      (10547): Verify
I/Icing   ( 4500): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10576): MountEmulatedStorage()
I/libpersona(10576): KNOX_SDCARD checking this for 10013
E/Zygote  (10576): v2
I/libpersona(10576): KNOX_SDCARD not a persona
I/SELinux (10576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10576): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=10576 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/appmanager(:<default>):LightSharedPreferencesImpl(10547): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl(10547): 	... 10 more
,W/appmanager(:<default>):b(10547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(10547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(10576): TimaSignature is unavailable
,D/ActivityThread(10576): Added TimaKeyStore provider
,D/ResourcesManager(10576): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,V/AlarmManager( 3524): waitForAlarm result :4
,D/Finsky  (10442): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3524): SIOP:: AP = 340, PST = 326, CUR = -531
,I/System.out(10442): Thread-1412(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10442): Thread-1412(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10442): Thread-1412(ApacheHTTPLog):isShipBuild true
I/System.out(10442): Thread-1412(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,I/System.out(10442): Thread-1412 calls detatch()
,W/Finsky  (10442): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10442): Thread-1413 calls detatch()
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10607): MountEmulatedStorage()
I/libpersona(10607): KNOX_SDCARD checking this for 10014
E/Zygote  (10607): v2
I/libpersona(10607): KNOX_SDCARD not a persona
,I/SELinux (10607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10607): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=10607 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/appmanager(:<default>):QuickExperimentControllerImpl(10547): Exposure of experiment com.facebook.http.g.c@1ac054f5 occurred when no user was logged in
,D/TimaKeyStoreProvider(10607): TimaSignature is unavailable
I/art     (10547): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
I/art     (10547): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,I/System.out(10442): Thread-1412 calls detatch()
D/ActivityThread(10607): Added TimaKeyStore provider
,W/Finsky  (10442): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10607): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/System.out(10547): Thread-1436(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10547): Thread-1436(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10547): Thread-1436(ApacheHTTPLog):isShipBuild true
I/System.out(10547): Thread-1436(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10110
,I/System.out(10547): P[5]_NetworkDispatch1 calls detatch()
W/ResourcesManager(10607): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10607): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/appmanager(:<default>):ae(10547): Got java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname while executing fetchSessionlessGKInfo, retrying on a safe network stack
,I/System.out(10547): P[5]_NetworkDispatch1 calls detatch()
,E/Zygote  (10629): MountEmulatedStorage()
E/Zygote  (10629): v2
I/libpersona(10629): KNOX_SDCARD checking this for 10173
I/libpersona(10629): KNOX_SDCARD not a persona
,I/SELinux (10629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/appmanager(:<default>):p(10547): Sessionless gatekeeper fetch with SingleMethodRunner failed
E/appmanager(:<default>):p(10547): java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname
E/appmanager(:<default>):p(10547): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:427)
E/appmanager(:<default>):p(10547): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
E/appmanager(:<default>):p(10547): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1288)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:700)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:691)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:514)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:492)
E/appmanager(:<default>):p(10547): 	at android.net.http.AndroidHttpClient.execute(AndroidHttpClient.java:302)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:477)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.c(FbHttpRequestProcessor.java:398)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.b(FbHttpRequestProcessor.java:342)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:328)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:256)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:1183)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ai.run(FbHttpRequestProcessor.java:1204)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p(10547): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/appmanager(:<default>):p(10547): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/appmanager(:<default>):p(10547): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
E/appmanager(:<default>):p(10547): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=10629 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9876:com.google.android.partnersetup/u0a17 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10629): TimaSignature is unavailable
,D/ActivityThread(10629): Added TimaKeyStore provider
,D/ResourcesManager(10629): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/TaskCloserActivity(10629): TaskCloserActivity enter()
,V/TaskCloserActivity(10629): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/ActivityManager( 3524): Killing 9894:com.sec.android.service.health/u0a19 (adj 15): bgCount ##31
,D/BootupListener( 3984): ACTION_DRIVELINK
,D/SettingsProvider( 3524): name = drivelink_navigation
,D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
D/BootupListener( 3984): NAVI : com.here.app.maps
,D/SettingsProvider( 3524): name = internet_call_settings_visibility
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
,D/SettingsProvider( 3524): selectionArgs: 1001
D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
D/BootupListener( 3984): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/NtpTrustedTime( 3524): forceRefresh() from cache miss
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/NtpTrustedTime( 3524): forceRefresh Fail.
,E/Zygote  (10659): MountEmulatedStorage()
I/libpersona(10659): KNOX_SDCARD checking this for 10022
E/Zygote  (10659): v2
I/libpersona(10659): KNOX_SDCARD not a persona
,I/SELinux (10659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=10659 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/SELinux (10659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 481us total 11.231ms
,D/TimaKeyStoreProvider(10659): TimaSignature is unavailable
,D/ActivityThread(10659): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 461us total 9.530ms
,D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(10659): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10659): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10659): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/MultiDex(10607): VM with version 2.1.0 has multidex support
I/MultiDex(10607): install
I/MultiDex(10607): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 769us total 14.832ms
,V/JNIHelp (10607): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppStateLogger(10486): Successfully dumped app state to log file
,I/LocationWidgetApplication(10659): onCreate() : start
,D/LocationWidgetApplication(10659): countryCode = POLAND
,D/LocationWidgetUtils(10659): getUpcommingInstances() start: 1457574313526, end: 1458169199999
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/LocationWidgetUtils(10659): getUpcommingInstances() DB begin time >= start:1457574313526, DB begin time <= end:1458169199999
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,W/ActivityThread(10607): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10607): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f497bca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10607): Installed default security provider GmsCore_OpenSSL
D/AcmsKeyStoreHelper(10327):  getKeyStoreForApplication Enter
,E/Zygote  (10678): MountEmulatedStorage()
I/libpersona(10678): KNOX_SDCARD checking this for 10163
E/Zygote  (10678): v2
I/libpersona(10678): KNOX_SDCARD not a persona
,I/SELinux (10678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=10678 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,I/SELinux (10678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10678): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/AcmsKeyStoreHelper(10327): Key Store exist
,I/AcmsKeyStoreHelper(10327): Hence loading the keystore file
,D/ChimeraCfgMgr(10607): Reading stored module config
,D/ChimeraCfgMgr(10607): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/TimaKeyStoreProvider(10678): TimaSignature is unavailable
,D/ActivityThread(10678): Added TimaKeyStore provider
,D/ResourcesManager(10678): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(10678): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10678): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/Zygote  (10697): MountEmulatedStorage()
E/Zygote  (10697): v2
I/libpersona(10697): KNOX_SDCARD checking this for 10164
I/libpersona(10697): KNOX_SDCARD not a persona
I/SELinux (10697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=10697 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (10697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 9909:com.sec.pcw.device/1000 (adj 15): bgCount ##31
D/AcmsKeyStoreHelper(10327):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(10327): getKeyStoreForApplication success 
D/AcmsCore(10327): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(10327): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10327): Decrementing - Counter value: 1
D/AcmsCore(10327): AcmsCore: ACMS_APP_INSTALLED
D/TimaKeyStoreProvider(10697): TimaSignature is unavailable
D/ActivityThread(10697): Added TimaKeyStore provider
D/AcmsCore(10327): This is NOT a valid MirrorLink app
D/AcmsCore(10327): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(10327): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10327): Decrementing - Counter value: 0
D/AcmsServiceMonitor(10327): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor(10327): getSvcCounter - Counter value: 0
D/AcmsService(10327): Enter onDestroy
I/AcmsService(10327): cleanUp(): inside service clean up
D/AcmsCore(10327): AcmsCore: inside DeInit
D/AcmsCore(10327): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(10327): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(10327): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(10327): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(10327): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(10327): getSvcCounter - Counter value: 0
D/AcmsService(10327): killing acms process
I/Process (10327): Sending signal. PID: 10327 SIG: 9
D/ResourcesManager(10697): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(10697): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10697): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10697): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10697): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/CAR.SERVICE(10607): Connecting to CarCallService...
,I/art     (10607): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils(10607): Install completed successfully. count=14 extracted=0
I/art     (10607): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE(10607): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager( 3524): Killing 9338:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,D/CAR.TEL.Service(10607): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter(10607): Creating a new PhoneAdapter instance
,W/ActivityManager( 3524): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(10607): setListener: com.google.android.gms.car.dn@306fbd21
W/ActivityManager( 3524): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter(10607): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service(10607): Starting CarCallService with initial phone null
,D/CAR.SERVICE(10607): Package validated; name: com.android.vending
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager( 3524): Process ACMS.Process (pid 10327)(adj 0) has died(70,1165)
,I/splitIntent( 3524): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3524): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,V/Finsky  (10442): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/ActivityManager( 3524): Killing 8841:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,D/AuthorizationBluetoothService( 4292): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/WearableService( 4292): callingUid 10014, callindPid: 4292
,D/LocationInitializer( 4500): Restart initialization of location
E/MDM     ( 4292): [266] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 4292): No location to return for getLastLocation()
W/FusedLocationProvider( 4292): location=null
,I/splitIntent( 3524): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/LocationManagerService( 3524): getProviders()=[]
D/LocationManagerService( 3524): getProviders()=[passive]
D/LocationManagerService( 3524): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10547): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10547): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/LWLocationManager(10659): mPrivacy is null
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl(10659): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ContextFramework:PrivacyManager(10659): Service for PrivacyManager is connected
,W/appmanager(:<default>):QuickExperimentControllerImpl(10547): Exposure of experiment com.facebook.imagepipeline.m.d@354ec71c occurred when no user was logged in
,W/appmanager(:<default>):aa(10547): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
W/appmanager(:<default>):aa(10547): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,D/LWLocationManager(10659): Privacy service : STATUS_PLACE
D/LWLocationManager(10659): updateLocationStatus()
,I/LocationWidgetFuctionData(10659): readDB
,I/LocationWidgetFuctionData(10659): selectedAppSize: 3
I/LocationWidgetFuctionData(10659): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(10659): selectedAppSize: 3
,I/LocationWidgetFuctionData(10659): selectedAppSize: 3
,I/LocationWidgetFuctionData(10659): selectedAppSize: 3
,I/LocationWidgetFuctionData(10659): selectedAppSize: 3
,I/art     (10547): Explicit concurrent mark sweep GC freed 49405(2MB) AllocSpace objects, 5(80KB) LOS objects, 22% free, 27MB/35MB, paused 1.085ms total 28.253ms
,W/appmanager(:<default>):m(10547): No feature status reporters found; is this dead code?
,E/LWLocationManager(10659): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(10659): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(10659): setShouldUpdateLocationId
D/LWLocationManager(10659): setShouldUpdateLocationId return false
D/LWLocationManager(10659): setShouldUpdateLocationId
D/LWLocationManager(10659): setShouldUpdateLocationId return false
D/LWLocationManager(10659): setShouldUpdateLocationId
D/LWLocationManager(10659): setShouldUpdateLocationId return false
D/LWLocationManager(10659): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10442): Thread-1413 calls detatch()
,W/Finsky  (10442): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  (10442): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 3524): waitForAlarm result :4
,D/Finsky  (10442): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 4292): client connected with version: 8296000
,D/Finsky  (10442): [1436] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10442): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  (10442): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(10442): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager( 3524): Killing 9946:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/ActivityManager( 3524): Killing 9924:com.policydm/1000 (adj 15): bgCount ##32
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    (10084): Thread[GAThread,5,main]: No campaign data found.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(10109): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension(10109): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log(10109): BLE multiple advertisement supported
I/jxcore-log(10109): 
,I/jxcore-log(10109): My device name is: samsung-SM-N910C
I/jxcore-log(10109): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    (10345): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3524): Killing 9963:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/9963/oom_score_adj; errno=22
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):UserScope(10486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/art     (10486): Thread[1,tid=10486,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/art     (10486): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching, sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImp,l(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/GcOptimizer(10486): Configure for next cold start: disable
,W/fb4a(:<default>):UserScope(10486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QuickExperimentControllerImpl(10486): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsMainExperiment@1d59a6b7 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(10486): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsPassiveListenerExperiment@3881ee24 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl(10486): Exposure of experiment com.facebook.inject.init.GeneratedFbInjectorWeakrefExperiment@129d5b43 occurred when no user was logged in
,W/fb4a(:<default>):UserScope(10486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10780): MountEmulatedStorage()
I/libpersona(10780): KNOX_SDCARD checking this for 10082
E/Zygote  (10780): v2
I/libpersona(10780): KNOX_SDCARD not a persona
,I/SELinux (10780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10780): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10780 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10780): TimaSignature is unavailable
,D/ActivityThread(10780): Added TimaKeyStore provider
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 21719(1335KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 1.183ms total 71.880ms
,D/ResourcesManager(10780): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(10780): onCreate
D/BadgeProvider(10780): DatabaseHelper
,D/BadgeProvider(10780): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider(10780): sendNotify, [notify] : null
D/BadgeProvider(10780): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider(10780): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10780): update, [UpdateCount] : 1
,D/Launcher.Model( 4000): reloadBadges entered.
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10110
,I/System.out(10547): P[5]_NetworkDispatch2 calls detatch()
,W/appmanager(:<default>):ae(10547): Got java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname while executing fetchSessionlessGKInfo, retrying on a safe network stack
,I/System.out(10547): P[5]_NetworkDispatch2 calls detatch()
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10486): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
E/appmanager(:<default>):p(10547): Sessionless gatekeeper fetch with SingleMethodRunner failed
E/appmanager(:<default>):p(10547): java.net.UnknownHostException: Unable to resolve host "api.facebook.com": No address associated with hostname
E/appmanager(:<default>):p(10547): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:427)
E/appmanager(:<default>):p(10547): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
E/appmanager(:<default>):p(10547): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1288)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:700)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:691)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:514)
E/appmanager(:<default>):p(10547): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:492)
E/appmanager(:<default>):p(10547): 	at android.net.http.AndroidHttpClient.execute(AndroidHttpClient.java:302)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:477)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.c(FbHttpRequestProcessor.java:398)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.b(FbHttpRequestProcessor.java:342)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:328)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:256)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ae.a(FbHttpRequestProcessor.java:1183)
E/appmanager(:<default>):p(10547): 	at com.facebook.http.common.ai.run(FbHttpRequestProcessor.java:1204)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p(10547): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/appmanager(:<default>):p(10547): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/appmanager(:<default>):p(10547): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/appmanager(:<default>):p(10547): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
E/appmanager(:<default>):p(10547): 	at java.lang.Thread.run(Thread.java:818)
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/ContextImpl(10486): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,I/ActivityManager( 3524): Killing 9989:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl(10486): Exposure of experiment com.facebook.imagepipeline.abtest.GeneratedDecodeFileDescriptorExperiment@5464f7b occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl(10486): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):UserScope(10486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
I/jxcore-log(10109): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAR.SERVICE(10607): mConnectedToCar = false, abort
,E/ActivityThread(10607): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@26c3b9e9 that was originally bound here
E/ActivityThread(10607): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@26c3b9e9 that was originally bound here
E/ActivityThread(10607): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10607): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10607): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10607): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10607): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10607): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10607): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10607): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread(10607): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread(10607): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread(10607): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread(10607): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread(10607): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread(10607): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(10607): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(10607): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(10607): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10607): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10607): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10607): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10607): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10607): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10607): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread(10607): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6038f88 that was originally bound here
E/ActivityThread(10607): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6038f88 that was originally bound here
E/ActivityThread(10607): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10607): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10607): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10607): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10607): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10607): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread(10607): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread(10607): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread(10607): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread(10607): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread(10607): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread(10607): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread(10607): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3181)
E/ActivityThread(10607): 	at android.app.ActivityThread.access$2000(ActivityThread.java:178)
E/ActivityThread(10607): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1537)
E/ActivityThread(10607): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10607): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10607): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10607): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10607): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10607): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10607): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 3524): Unbind failed: could not find connection for android.os.BinderProxy@2a2f6e87
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(10109): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(10109): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log(10109): 
,I/jxcore-log(10109): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log(10109): 
,I/io.jxcore.node.ConnectivityInfo(10109): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo(10109):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo(10109):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo(10109):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo(10109):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo(10109):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo(10109):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo(10109):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo(10109):     - force notify: true
D/io.jxcore.node.JXcoreExtension(10109): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log(10109): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log(10109): 
,I/jxcore-log(10109): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log(10109): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3524): [MSG] MCS_UNBIND
,I/ActivityManager( 3524): Killing 9355:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/9355/oom_score_adj; errno=22
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3524): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3524): waitForAlarm result :8
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10064
,W/NetworkUtils( 4034): OkHttp exception
W/EventLoggerService( 4034): Unable to send logs Error code: 262146
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4292): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10014
E/Auth    ( 4292): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 4034): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4292): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 4292): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 4034): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log(10109): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(10109): 
,I/jxcore-log(10109): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
I/jxcore-log(10109): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(10109): Unit Test app is loaded
I/jxcore-log(10109): 
,I/chromium(10109): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/jxcore-log(10109): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log(10109): 
,D/PowerManagerService( 3524): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3693 (0x0)
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4319, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-565, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-388
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3524): SIOP:: AP = 350, PST = 328, CUR = -565
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{3beafda3 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
,D/lights  ( 3524): lcd : 1 +
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 1 -
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [s] UserActivityState : 2 -> 4,
D/InputManager-JNI( 3524): setDeviceInteractive: 0
I/PowerManagerService( 3524): !@[ps] Screen__Off - 1 : timeout (0x4) (2)
,I/PowerManagerService( 3524): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 3524): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3524): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService( 3524): handleSandman : startDream()
D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event3/device/enabled: 0
E/PowerManagerService( 3524): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 3524): Sleeping (uid 1000)...
D/PowerManagerService( 3524): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3524): [input device light] setInputDeviceLightOn is called : 0
D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/PowerManagerService( 3524): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger( 2851): id=13 createSurf (1440x2560),2 flag=404, DolorFade
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService( 3524): Excessive delay in ColorFade : createSurface: 13ms
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/mali_winsys( 3524): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/SContextService( 3524): 	.unregisterCallback : 1, client=
D/SContextService( 3524): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@292bf8bc, Service = Auto Rotation, used = 1
W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3524): stop(ContextProvider.java:149)
,V/CAE     ( 3524): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3524): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2869): sendContextData: -78, 7, 0, 0
,D/CAE     ( 3524): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3524): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3524): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 38ms
,D/CAE     ( 3524): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3524): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3524): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3524): removeSContextService() : service = Auto Rotation
D/SContextService( 3524): ===== SContext Service List =====
D/SContextManager( 3524):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2f7fcf99, service=Auto Rotation
,D/KeyguardViewMediator( 3693): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3693): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3693): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 3693): notifyScreenOffLocked
,D/PowerManagerService( 3524): Excessive delay in ColorFade : initGLShaders: 31ms
,D/KeyguardViewMediator( 3693): timeout : 5000
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 16ms
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 12ms
,V/ActivityThread(10109): updateVisibility : ActivityRecord{35f09f35 token=android.os.BinderProxy@3d8f2a2d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 16ms
D/PowerManagerService( 3524): Excessive delay in ColorFade prepare: 134ms
D/DisplayPowerController( 3524): ColorFade: onAnimationStart
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/KeyguardViewMediator( 3693): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 3693): handleNotifyScreenOff
,V/AlarmManager( 3524): waitForAlarm result :4
,D/lights  ( 3524): lcd : 0 +
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 0 -
,D/LightsService( 3524): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3524) 
,D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager( 3524): unregisterListener ::   
,D/lights  ( 3524): led_pattern : 5 +
D/BatteryService( 3524): turn on LED for fully charged
,I/CAE     ( 3524): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3524): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs( 2869): sendContextData: -76, 13, -46, 0
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 1, 45, 32,
D/SensorHubManager( 3524): SendSensorHubData: send data = -63, 14, 1, 45, 32
D/Sensorhubs( 2869): sendContextData: -63, 14, 1, 45, 32
,D/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3524):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,I/WifiNative-HAL( 3524): startHal
E/wifi    ( 3524): getStaticLongField sWifiHalHandle 0x8f7627fc
D/wifi    ( 3524): halHandle = 0x0, mVM = 0xb4d5c280, mCls = 0x5020ee
I/WifiNative-HAL( 3524): Could not start hal
D/WifiStateMachine( 3524): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3524): handleScreenStateChanged Exit: false
,E/WifiStateMachine( 3524): setSuspendOptimizations: 4 true
E/WifiStateMachine( 3524): mSuspendOptNeedsDisabled 0
,D/NotificationService( 3524): ACTION_SCREEN_OFF
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
,D/lights  ( 3524): led_pattern : 5 -
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  ,
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,I/AudioHardwareTinyALSA( 2856): setParameters(screen_state=off)
D/SensorManager( 3524): unregisterListener ::   
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4391, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-134, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/SecExternalDisplayIntents_Java( 3524): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/IpRemoteDisplayController( 3524): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3524): Bridge Server is not available
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/VolumePanel( 3693): registerReceiver: onReceive start 
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/VolumePanel( 3693): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3693): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3693): registerReceiver: onReceive end 
,D/VolumePanel( 3693): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3693): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3693): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3693): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3693): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3524): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3524): sExerciseIterface is not available
,D/PersonaManagerService( 3524): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 3524): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 3966): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3693):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3693): onReceive : Intent.ACTION_SCREEN_OFF
,D/DisplayPowerState( 3524): !@ ColorFade entry
D/DisplayPowerController( 3524): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/accuweather( 5233): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/accuweather( 5233): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Display
D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/DisplayManagerService( 3524): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,I/Sensors ( 3524): Light old sensor_state 513, new sensor_state : 1 en : 0
V/ActivityManager( 3524): Display changed displayId=0
,D/SensorManager( 3524): unregisterListener ::   
,I/Sensors ( 3524): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/SensorManager( 3524): unregisterListener ::   
,D/SurfaceFlinger( 2851): Set power mode=0, type=0 flinger=0xb6962000
I/hwcomposer( 2851): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,D/accuweather( 5233): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3524): SIOP:: AP = 310, PST = 327, CUR = -134
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,D/accuweather( 5233): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5233): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5233): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5233): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5233): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5233): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5233): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
D/accuweather( 5233): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5233): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5233): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5233): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3524): Excessive delay in setPowerMode(): 212ms
D/PowerManagerService( 3524): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3524): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3524): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService( 3524): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 213ms
I/PowerManagerService( 3524): [PWL] Off : 0s ago
,D/Finsky  (10442): [1425] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10442): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 3524): waitForAlarm result :4
,D/FactoryTest( 9259): Not factory mode
,D/FactoryTest( 9259): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 9259): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 9259): still no open session command from host, so toast
,W/ContextImpl( 9259): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 9259): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
,I/Timeline( 9259): Timeline: Activity_launch_request id:com.android.settings time:97306
,E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
,I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager( 3524): mDVFSHelper.acquire()
,V/ActivityManager( 3524): Display changed displayId=0
,E/MTPRx   ( 9259): started activity for popup
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager( 9259): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 9259): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9259): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 9259): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9259): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9259): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9259): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 9259): PREF_DONT_ASK_AGAIN : true
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 3524): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@34318826 attribute=android.view.inputmethod.EditorInfo@3f6bc67, token = android.os.BinderProxy@b4c6b3a
,D/SettingsReceiverActivity( 9259): dev.kiessupport is : TRUE
,D/Activity( 9259): performCreate Call secproduct feature valuefalse
D/Activity( 9259): performCreate Call debug elastic valuetrue
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,V/ActivityThread(10109): updateVisibility : ActivityRecord{35f09f35 token=android.os.BinderProxy@3d8f2a2d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline(10109): Timeline: Activity_idle id: android.os.BinderProxy@3d8f2a2d time:97644
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardViewMediator( 3693): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 3693): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 3524): [PWL] Off : 5s ago
,W/ActivityManager( 3524): mDVFSHelper.release()
,E/Watchdog( 3524): !@Sync 3
,V/AlarmManager( 3524): waitForAlarm result :4
,V/xAnalytics(10486): xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 10857
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:116
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 300, PST = 324, CUR = 15
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 10871
,I/PowerManagerService( 3524): [PWL] Off : 15s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:102
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:n  ( 3524): SIOP:: AP = 290, PST = 321, CUR = 67
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :8
,V/AlarmManager( 3524): waitForAlarm result :4
,V/AlarmManager( 3524): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 3524): <AppSync3 Whitelist>
,V/AlarmManager( 3524): (AppSync) ### 0 added ###
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 318, CUR = 79
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:79, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 3524): Plugged
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 3524): [PWL] Off : 30s ago
I/PowerManagerService( 3524): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3524): [PWL]     mWakeLockSummary : 0x1
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 4
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 312, CUR = 79
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:76, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:75
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 305, CUR = 76
,I/PowerManagerService( 3524): [PWL] Off : 50s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:70, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3524): waitForAlarm result :4
,D/NtpTrustedTime( 3524): forceRefresh() from cache miss
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3524): forceRefresh Fail.
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 300, CUR = 70
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:64, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 5,
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 295, CUR = 64
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 75s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 290, CUR = 58
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :8
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/VacuumService( 4292): Vacuum at: now=1457574422819 tag=VacuumService
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 287, CUR = 54
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 10974
,I/ClearcutLoggerApiImpl( 4292): disconnect managed GoogleApiClient
,E/Watchdog( 3524): !@Sync 6
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 282, CUR = 51
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3524): waitForAlarm result :4
,V/AlarmManager( 3524): waitForAlarm result :4
,I/PowerManagerService( 3524): [PWL] Off : 105s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 275, CUR = 48
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3524): waitForAlarm result :8
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 270, CUR = 44
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 7
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 268, CUR = 42
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 140s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 266, CUR = 41
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :8
,D/NtpTrustedTime( 3524): forceRefresh() from cache miss
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3524): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 265, CUR = 40
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 8
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 263, CUR = 39
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 262, CUR = 37
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 180s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 262, CUR = 35
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 9
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 261, CUR = 34
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 261, CUR = 35
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :8
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 260, CUR = 33
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3524): initializing...
I/TLC_TIMA_PKM_initialize( 3524): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3524): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3524): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3524): root = 0, root_len = 1,
I/TZ: mc_tlc_communication( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3524): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3524): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3524): device_id = 0x0
,I/TZ: mc_tlc_communication( 3524): tlc_open() was called
I/TZ: mc_tlc_communication( 3524): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3524): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3524): Opening the session
,I/TZ: mc_tlc_communication( 3524): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3524): Trustlet response is completed
,E/Watchdog( 3524): !@Sync 10
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 260, CUR = 32,
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 11078
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 225s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 260, CUR = 31,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!,
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 260, CUR = 32
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 11
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 259, CUR = 31
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 259, CUR = 31
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 258, CUR = 29
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 275s ago
,E/Watchdog( 3524): !@Sync 12
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10442): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 257, CUR = 28
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 257, CUR = 27
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 256, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 13
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 256, CUR = 28
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 255, CUR = 28
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 330s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 255, CUR = 28
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 14
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 254, CUR = 26
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 254, CUR = 25
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 253, CUR = 25
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 15
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 253, CUR = 25
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 252, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :8
,I/PowerManagerService( 3524): [PWL] Off : 390s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 252, CUR = 26
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 16
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 252, CUR = 25
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 251, CUR = 25,
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 251, CUR = 24
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 17
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 251, CUR = 23
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 24
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 22
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 455s ago
,E/Watchdog( 3524): !@Sync 18
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 22
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 23
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 21
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 19
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 20
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 20
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3524): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 19
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 525s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 18
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3524): Killing 8461:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/CountryDetector( 3524): No listener is left
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 19
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 21
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 19
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 22
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10442): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 18
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3524): [PWL] Off : 600s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 23
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true,
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 24
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17,
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 25
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3524): [PWL] Off : 680s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 19
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 26
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 20
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 27
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 28
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 16
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 765s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 29
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 16,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 31
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,I/PowerManagerService( 3524): [PWL] Off : 855s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 32
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10442): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 33
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 34
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 950s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 35
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,E/Watchdog( 3524): !@Sync 36
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,E/Watchdog( 3524): !@Sync 37
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 10
,E/Watchdog( 3524): !@Sync 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 10
,E/Watchdog( 3524): !@Sync 39
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 11
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3524): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3524): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3524): Updating Usage Statistics in DB @ 1457575450525
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$Cu,rsorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb,.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3524): Done Updating Usage Statistics in DB @ 1457575450622
,E/Watchdog( 3524): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 10
,I/art     ( 3524): Background sticky concurrent mark sweep GC freed 97878(9MB) AllocSpace objects, 355(5MB) LOS objects, 14% free, 49MB/57MB, paused 3.418ms total 131.725ms
,E/Watchdog( 3524): !@Sync 41
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 11
,I/PowerManagerService( 3524): [PWL] Off : 1155s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 10
,E/Watchdog( 3524): !@Sync 42
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10442): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 10031
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 10
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11814): 
D/AndroidRuntime(11814): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11814): CheckJNI is OFF
D/AndroidRuntime(11814): readGMSProperty: start
D/AndroidRuntime(11814): readGMSProperty: already setted!!
D/AndroidRuntime(11814): readGMSProperty: end
D/AndroidRuntime(11814): addProductProperty: start
E/AffinityControl(11814): AffinityControl: registerfunction enter
D/AndroidRuntime(11814): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3524): START PACKAGE DELETE: observer{497459759}
D/PackageManager( 3524): pkg{<packageName>}
D/PackageManager( 3524): user{0}
D/PackageManager( 3524): caller{2000}
D/PackageManager( 3524): flags{3}
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3524): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 3524): !@killApplicatoin: 10688, uninstall pkg
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:-1
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10688 user=-1: uninstall pkg
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 3524): Killing 10109:com.test.thalitest/u0a688 (adj 0): stop com.test.thalitest
I/ActivityManager( 3524):   Force finishing activity ActivityRecord{38799a82 u0 com.test.thalitest/.MainActivity t27}
I/SurfaceFlinger( 2851): id=12 Removed NainActivit (5/8)
I/SurfaceFlinger( 2851): id=12 Removed NainActivit (-2/8)
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 3524): Skipping PackageSetting{3bb2c9e3 com.example.hello/10687} due to missing metadata
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10688 user=0: pkg removed
D/WifiService( 3524): Client connection lost with reason: 4
I/art     ( 8120): Explicit concurrent mark sweep GC freed 31144(1714KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.142ms total 47.106ms
I/art     ( 4034): Explicit concurrent mark sweep GC freed 5248(347KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.432ms total 49.516ms
E/libprocessgroup( 3524): failed to kill 1 processes for processgroup 10109
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
W/GeofencerStateMachine( 4292): Ignoring removeGeofence because network location is disabled.
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/LWLocationManager(10659): getDeviceLocationId :  id = -100
E/SamsungIME( 4436): mOCRHelper is null
E/Zygote  (11837): MountEmulatedStorage()
E/Zygote  (11837): v2
I/libpersona(11837): KNOX_SDCARD checking this for 10063
I/libpersona(11837): KNOX_SDCARD not a persona
I/ActivityManager( 3524): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=11837 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/LocationWidgetApplication(10659): getLastUiLocationId() : mLastUiLocationId = -100
I/SELinux (11837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 8369): Explicit concurrent mark sweep GC freed 746(49KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 2.222ms total 168.529ms
I/art     ( 4500): Explicit concurrent mark sweep GC freed 4859(191KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 8.553ms total 182.343ms
W/ResourceType( 4942): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4942): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/TimaKeyStoreProvider(11837): TimaSignature is unavailable
D/ActivityThread(11837): Added TimaKeyStore provider
I/InputReader( 3524): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(11837): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 11
D/VRSetupWizardStub/PackageIntentReceiver(11837): onReceive()
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/VRSetupWizardStub/PackageIntentReceiver(11837): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(11837): packagename:com.test.thalitest
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/art     ( 3524): Explicit concurrent mark sweep GC freed 22897(2033KB) AllocSpace objects, 19(304KB) LOS objects, 24% free, 48MB/64MB, paused 3.800ms total 277.632ms
I/art     ( 3524): WaitForGcToComplete blocked for 104.128ms for cause Explicit
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/Zygote  (11858): MountEmulatedStorage()
I/libpersona(11858): KNOX_SDCARD checking this for 10021
E/Zygote  (11858): v2
I/libpersona(11858): KNOX_SDCARD not a persona
I/SELinux (11858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11858 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 10028:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/EnterpriseDeviceManagerService( 3524): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3524): Admin package name: com.google.android.gms
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/TimaKeyStoreProvider(11858): TimaSignature is unavailable
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ActivityThread(11858): Added TimaKeyStore provider
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RegisteredServicesCache( 3966): empty dynamic service
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager(11858): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/KLMS-2.4.521: (11858): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 03:05:25 GMT+01:00 2016
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/KLMS-2.4.521: (11858): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3524): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3524): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/KLMS-2.4.521: (11858): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (11858): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (11858): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (11858): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/Zygote  (11874): MountEmulatedStorage()
I/libpersona(11874): KNOX_SDCARD checking this for 10106
E/Zygote  (11874): v2
I/libpersona(11874): KNOX_SDCARD not a persona
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SELinux (11874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11874 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (11874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (11858): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (11858): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.4.521: (11858): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
E/Zygote  (11890): MountEmulatedStorage()
E/Zygote  (11890): v2
I/libpersona(11890): KNOX_SDCARD checking this for 1000
I/libpersona(11890): KNOX_SDCARD not a persona
I/SELinux (11890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/SELinux (11890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=11890 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/TimaKeyStoreProvider(11874): TimaSignature is unavailable
D/ActivityThread(11874): Added TimaKeyStore provider
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager(10659): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     ( 3524): Explicit concurrent mark sweep GC freed 11342(621KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.553ms total 184.969ms
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/Zygote  (11906): MountEmulatedStorage()
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/Zygote  (11906): v2
I/libpersona(11906): KNOX_SDCARD checking this for 10050
I/libpersona(11906): KNOX_SDCARD not a persona
I/SELinux (11906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=11906 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (11906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11906): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (11858): KLMSIntentService(): listeningToPackageRemoved().END
D/TimaKeyStoreProvider(11890): TimaSignature is unavailable
D/ActivityThread(11890): Added TimaKeyStore provider
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(10659): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10659): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10659): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10659): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (11858): KLMSIntentService(): onDestroy()
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(11874): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/TimaKeyStoreProvider(11906): TimaSignature is unavailable
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ActivityThread(11906): Added TimaKeyStore provider
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/elm:14491(11874): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(11874): ELMEngine.ELMEngine( context ).
D/elm:14491(11874): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(11890): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(11890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/TapandpayWidget:TanpandpayAppWidgetProvider(10399): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10399): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(10399): Clear T&P info.
D/TapandpayWidget:TanpandpayAppWidgetProvider(10399): Widget is not attached.
D/elm:14491(11874): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(11874): ElmAgentService : onCreate()
D/elm:14491(11874): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11874): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11874): MDMBridge.getInstance()
D/elm:14491(11874): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(11874): MDMBridge.getAllLicenseInfoFromSDK()
D/RCPManager(11890):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3524):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3524): queryAllProviders():  providerCallBack is not register for 0
I/ActivityManager( 3524): Killing 7696:com.android.settings/1000 (adj 15): bgCount ##31
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/elm:14491(11874): ElmAgentService : onDestroy().
D/ResourcesManager(10659): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11906): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/PackageBroadcastService( 4500): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4500): Clearing selected account for com.test.thalitest
W/ResourcesManager(11906): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager(10659): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
W/ResourceType( 3524): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
E/Zygote  (11925): MountEmulatedStorage()
E/Zygote  (11925): v2
I/libpersona(11925): KNOX_SDCARD checking this for 10019
I/libpersona(11925): KNOX_SDCARD not a persona
I/SELinux (11925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=11925 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (11925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/LocationSettingsChecker( 4500): Removing dialog suppression flag for package com.test.thalitest
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/gH_CompatibleDatabase( 4500): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4500): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4500): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4500): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/TimaKeyStoreProvider(11925): TimaSignature is unavailable
D/gH_CompatibleDatabase( 4500): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4500): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4500): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/ActivityThread(11925): Added TimaKeyStore provider
D/gH_CompatibleDatabase( 4500): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4500): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4500): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4500): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4500): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4500): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/PackageManager( 3524): delete codoeFile: 
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/AASAUninstall( 3524):  com.test.thalitest not target!
D/PackageManager( 3524): result of delete: 1{497459759}
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/AndroidRuntime(11814): Shutting down VM
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
W/ResourcesManager( 3524): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(10659): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(11925): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/ContextImpl(10248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
D/ChimeraCfgMgr( 4500): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4500): Module APK com.google.android.play.games already loaded
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/PackageManager( 3524): findPreferredActivity: No PreferredActivities set
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/RCPManagerService( 3524): PackageReceiver onReceive()
E/Zygote  (11950): MountEmulatedStorage()
I/libpersona(11950): KNOX_SDCARD checking this for 10116
E/Zygote  (11950): v2
I/libpersona(11950): KNOX_SDCARD not a persona
I/HarmonyEASService( 3524): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux (11950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/KnoxMUMContainerPolicy( 3524): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3524): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3524): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): uID is 10688
V/EnterpriseBillingPolicy( 3524): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - end - null
I/ActivityManager( 3524): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=11950 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
I/SELinux (11950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11950): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10659): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
D/UsbSettingsManager( 3524): clearDefaults: com.test.thalitest

```
