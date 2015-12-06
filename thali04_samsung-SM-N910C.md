#### Test 50242285576d0b0_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 255, CUR = 52
--------- beginning of main
D/AndroidRuntime(10672): 
D/AndroidRuntime(10672): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10672): CheckJNI is OFF
D/AndroidRuntime(10672): readGMSProperty: start
D/AndroidRuntime(10672): readGMSProperty: already setted!!
D/AndroidRuntime(10672): readGMSProperty: end
D/AndroidRuntime(10672): addProductProperty: start
E/AffinityControl(10672): AffinityControl: registerfunction enter
D/AndroidRuntime(10672): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
D/FocusedStackFrame( 3522): Set to : 0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (10690): MountEmulatedStorage()
E/Zygote  (10690): v2
I/libpersona(10690): KNOX_SDCARD checking this for 10456
I/libpersona(10690): KNOX_SDCARD not a persona
I/SELinux (10690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10690 uid=10456 gids={50456, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/SELinux (10690): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10672): Shutting down VM
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10690): TimaSignature is unavailable
D/ActivityThread(10690): Added TimaKeyStore provider
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3522): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10690): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (6/8)
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/8)
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/ActivityThread( 3998): updateVisibility : ActivityRecord{23aea72c token=android.os.BinderProxy@3f1893de {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3998): onTrimMemory. Level: 20
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/WebViewFactory(10690): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10690): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10690): Loading: webviewchromium
I/LibraryLoader(10690): Time to load native libraries: 4 ms (timestamps 5173-5177)
I/LibraryLoader(10690): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10690): Binding Chromium to main looper Looper (main, tid 1) {2eb40b44}
I/LibraryLoader(10690): Expected native library version number "",actual native library version number ""
I/chromium(10690): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(10690): Initializing chromium process, renderers=0
,W/art     (10690): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10690): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10690): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10690): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10690): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10690): 951039021: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10690): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10690): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10690): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10690): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10690): CordovaWebView is running on device made by: samsung
,W/art     (10690): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10690): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10690): performCreate Call secproduct feature valuefalse
D/Activity(10690): performCreate Call debug elastic valuetrue
,W/ActivityManager( 3522): Activity pause timeout for ActivityRecord{b5f1b21 u0 com.example.hello/.MainActivity t25}
,D/OpenGLRenderer(10690): Render dirty regions requested: true
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,V/ActivityThread(10690): updateVisibility : ActivityRecord{1a93029d token=android.os.BinderProxy@627ab7b {com.example.hello/com.example.hello.MainActivity}} show : true
,I/SurfaceFlinger( 2850): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(10690): Initialized EGL, version 1.4
,I/OpenGLRenderer(10690): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1279942384 
,D/OpenGLRenderer(10690): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10690): Enabling debug mode 0
,D/mali_winsys(10690): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 29266(1942KB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 48MB/64MB, paused 1.629ms total 163.492ms
,W/ActivityManager( 3522): mDVFSHelper.release()
,I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{b5f1b21 u0 com.example.hello/.MainActivity t25} time:215834
,W/IInputConnectionWrapper(10690): showStatusIcon on inactive InputConnection
,I/Timeline(10690): Timeline: Activity_idle id: android.os.BinderProxy@627ab7b time:215837
,I/chromium(10690): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(10690): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue(10690): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10690): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10690): 
,V/AlarmManager( 3522): waitForAlarm result :8
,D/NtpTrustedTime( 3522): forceRefresh() from cache miss
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 3522): forceRefresh Fail.
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/jxcore_app_log(10690): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1359522048
,D/JX-Cordova(10690): jxcore cordova android initializing
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/jxcore-log(10690): Initializing JXcore engine
W/jxcore-log(10690): JXcore engine is ready
,W/jxcore-log(10690): Starting JXcore engine
,E/auditd  ( 4554): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10690): Platform android
W/jxcore-log(10690): 
W/jxcore-log(10690): Process ARCH arm
W/jxcore-log(10690): 
,I/jxcore-log(10690): JXcore Cordova bridge is ready!
I/jxcore-log(10690): 
W/jxcore-log(10690): JXcore engine is started
,E/jxcore-log(10690): >> samsung-SM-N910C
E/jxcore-log(10690): 
,I/jxcore-log(10690): Total memory 2970812416
I/jxcore-log(10690): 
,I/jxcore-log(10690): Free memory 159895552
I/jxcore-log(10690): 
I/jxcore-log(10690): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10690): 
I/jxcore-log(10690): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10690): 
,I/jxcore-log(10690): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10690): 
,I/jxcore-log(10690): Size 1440 2560
I/jxcore-log(10690): 
,I/jxcore-log(10690): Screen Brightness 134
I/jxcore-log(10690): 
,E/jxcore-log(10690): Dummy Error Log.
E/jxcore-log(10690): 
,I/jxcore-log(10690): getBuffer is called!!!!
I/jxcore-log(10690): 
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 10797
,D/BluetoothAdapter(10690): disable()
,E/BluetoothManagerService( 3522): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3522): New client listening to asynchronous messages
,I/WifiManager(10690): packageName : com.example.hello
,D/SecContentProvider( 3522): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3522): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3522): mCursor = null
,D/WifiService( 3522): setWifiEnabled: false pid=10690, uid=10456
,E/WifiService( 3522): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3522): name = wifi_on
,I/jxcore-log(10690): ****TEST TOOK:  5069  ms ****
I/jxcore-log(10690): 
,I/jxcore-log(10690): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10690): 
,D/AndroidRuntime(10805): 
D/AndroidRuntime(10805): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10805): CheckJNI is OFF
,D/AndroidRuntime(10805): readGMSProperty: start
D/AndroidRuntime(10805): readGMSProperty: already setted!!
,D/AndroidRuntime(10805): readGMSProperty: end
D/AndroidRuntime(10805): addProductProperty: start
,E/AffinityControl(10805): AffinityControl: registerfunction enter
,D/AndroidRuntime(10805): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 3522): START PACKAGE DELETE: observer{793732262}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{3}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
,D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3522): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService( 3522): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 3522): !@killApplicatoin: 10456, uninstall pkg
D/PackageManagerService( 3522): deletePackage- pkg:com.example.hello, edmuserId:-1
I/ActivityManager( 3522): Force stopping com.example.hello appid=10456 user=-1: uninstall pkg
,D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
I/ActivityManager( 3522): Killing 10690:com.example.hello/u0a456 (adj 0): stop com.example.hello
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 3522):   Force finishing activity ActivityRecord{b5f1b21 u0 com.example.hello/.MainActivity t25}
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,D/WifiService( 3522): Client connection lost with reason: 4
,W/PackageSettings( 3522): Skipping PackageSetting{19272a62 com.test.thalitest/10454} due to missing metadata
,I/ActivityManager( 3522): Force stopping com.example.hello appid=10456 user=0: pkg removed
,I/art     ( 8442): Explicit concurrent mark sweep GC freed 750(49KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 976us total 25.026ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 8041): Explicit concurrent mark sweep GC freed 28756(1612KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.135ms total 33.718ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4248): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4448): mOCRHelper is null
,D/LWLocationManager(10506): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10506): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (10823): MountEmulatedStorage()
E/Zygote  (10823): v2
I/libpersona(10823): KNOX_SDCARD checking this for 10063
I/libpersona(10823): KNOX_SDCARD not a persona
,I/SELinux (10823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/EnterpriseDeviceManagerService( 3522): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3522): Admin package name: com.google.android.gms
,I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10823 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/SELinux (10823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourceType( 4972): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 4972): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(10823): TimaSignature is unavailable
,D/ActivityThread(10823): Added TimaKeyStore provider
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 17164(1474KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 3.823ms total 152.089ms
,I/art     ( 3522): WaitForGcToComplete blocked for 145.907ms for cause Explicit
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(10823): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/VRSetupWizardStub/PackageIntentReceiver(10823): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10823): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10823): packagename:com.example.hello
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10840): MountEmulatedStorage()
I/libpersona(10840): KNOX_SDCARD checking this for 10021
E/Zygote  (10840): v2
I/libpersona(10840): KNOX_SDCARD not a persona
,I/SELinux (10840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10840 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 10035:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/RegisteredServicesCache( 3962): empty dynamic service
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8711(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 894us total 23.172ms
,D/TimaKeyStoreProvider(10840): TimaSignature is unavailable
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ActivityThread(10840): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 837us total 18.492ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.141ms total 14.735ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(10840): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10506): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 8524(515KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 4.622ms total 155.657ms
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/KLMS-2.4.521: (10840): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Dec 06 15:13:06 GMT+01:00 2015
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/KLMS-2.4.521: (10840): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10840): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (10840): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(10506): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (10840): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (10840): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (10840): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (10840): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (10840): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,E/Zygote  (10857): MountEmulatedStorage()
E/Zygote  (10857): v2
I/libpersona(10857): KNOX_SDCARD checking this for 10106
I/libpersona(10857): KNOX_SDCARD not a persona
,I/SELinux (10857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10857 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10506): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10506): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10506): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10506): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10857): TimaSignature is unavailable
,D/ActivityThread(10857): Added TimaKeyStore provider
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,E/Zygote  (10872): MountEmulatedStorage()
E/Zygote  (10872): v2
I/libpersona(10872): KNOX_SDCARD checking this for 1000
I/libpersona(10872): KNOX_SDCARD not a persona
,I/SELinux (10872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=10872 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(10857): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(10872): TimaSignature is unavailable
,D/ActivityThread(10872): Added TimaKeyStore provider
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/elm:14491(10857): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(10857): ELMEngine.ELMEngine( context ).
D/elm:14491(10857): MDMBridge.setEnterpriseBridge()
I/KLMS-2.4.521: (10840): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(10872): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(10872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10840): KLMSIntentService(): onDestroy()
D/elm:14491(10857): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/RCPManager(10872):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 3522):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3522): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10412): onReceive()
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/TapandpayWidget:TanpandpayAppWidgetProvider(10412): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(10412): Clear T&P info.
D/Mms/FreeMessageStatusReceiver( 7881): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10412): Widget is not attached.
,W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,D/elm:14491(10857): ElmAgentService : onCreate()
D/PackageManager( 3522): delete codoeFile: 
D/elm:14491(10857): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14491(10857): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10857): MDMBridge.getInstance()
D/elm:14491(10857): MDMBridge.getAllLicenseInfoFromSDK()
,I/AASAUninstall( 3522):  com.example.hello not target!
D/elm:14491(10857): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(10506): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/PackageManager( 3522): result of delete: 1{793732262}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  (10890): MountEmulatedStorage()
E/Zygote  (10890): v2
I/libpersona(10890): KNOX_SDCARD checking this for 10019
D/ResourcesManager(10506): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/libpersona(10890): KNOX_SDCARD not a persona
,D/AndroidRuntime(10805): Shutting down VM
I/SELinux (10890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux (10890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10890 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (10890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/elm:14491(10857): ElmAgentService : onDestroy().
,D/RCPManagerService( 3522): PackageReceiver onReceive()
I/HarmonyEASService( 3522): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3522): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): uID is 10456
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=25_task.xml
D/UsbSettingsManager( 3522): clearDefaults: com.example.hello
I/CrashAnrDetector( 3522): onPackageRemoved : com.example.hello
D/TimaKeyStoreProvider(10890): TimaSignature is unavailable
,D/ActivityThread(10890): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 7881): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 7881): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(10890): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/ContextImpl(10277): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,I/TactileAssist( 3522): enable value -1
I/TactileAssist( 3522): internal enable value -1
I/TactileAssist( 3522): intensity value -1
I/TactileAssist( 3522): saveAppList value true
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10890): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(10890): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10890): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(10506): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/TactileAssist( 3522): List of disabled apps :
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Books/Books.apk
,E/Zygote  (10908): MountEmulatedStorage()
E/Zygote  (10908): v2
I/libpersona(10908): KNOX_SDCARD checking this for 10116
I/libpersona(10908): KNOX_SDCARD not a persona
,I/SELinux (10908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10506): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
I/SELinux (10908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10908 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
E/SELinux (10908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/LocationWidgetApplication(10506): getLastUiLocationId() : mLastUiLocationId = -100
,D/TimaKeyStoreProvider(10908): TimaSignature is unavailable
D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/ActivityThread(10443): Failed to find provider info for com.facebook.appmanager.installrecord
,D/ActivityThread(10908): Added TimaKeyStore provider
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(10908): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/Compatibility(10154): onReceive() it will make start service
D/PackageBroadcastService( 4482): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 4482): Clearing selected account for com.example.hello
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/Zygote  (10926): MountEmulatedStorage()
E/Zygote  (10926): v2
I/libpersona(10926): KNOX_SDCARD checking this for 1000
I/libpersona(10926): KNOX_SDCARD not a persona
,I/SELinux (10926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10926 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager(10506): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/SELinux (10926): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 10057:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,I/LocationSettingsChecker( 4482): Removing dialog suppression flag for package com.example.hello
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(10926): TimaSignature is unavailable
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/Compatibility(10154): onHandleIntent()
,D/ActivityThread(10926): Added TimaKeyStore provider
,D/Compatibility(10154): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10456, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/gH_CompatibleDatabase( 4482): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4482): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 4482): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 4482): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/Compatibility(10154): found: 2
D/Compatibility(10154): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10154): skipping ResolveInfo{33839d62 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10154): considering ResolveInfo{24ca0ef3 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10154): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10154): enabling receiver ResolveInfo{3d8897b0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility(10154): enabling receiver ResolveInfo{13806629 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/Zygote  (10945): MountEmulatedStorage()
,E/Zygote  (10945): v2
I/libpersona(10945): KNOX_SDCARD checking this for 1000
,I/libpersona(10945): KNOX_SDCARD not a persona
I/ActivityManager( 3522): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 10074:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
I/SELinux (10945): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10506): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
I/SELinux (10945): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10945): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility(10154): enabling receiver ResolveInfo{19822dae com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/gH_CompatibleDatabase( 4482): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4482): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 4482): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 4482): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4482): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 4482): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4482): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4482): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4482): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,E/SQLiteLog(10908): (284) automatic index on titles(filter_id)
,D/ResourcesManager(10506): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/Compatibility(10154): enabling receiver ResolveInfo{8eca74f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider(10945): TimaSignature is unavailable
D/ResourcesManager(10926): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/ActivityThread(10945): Added TimaKeyStore provider
,D/Compatibility(10154): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/SQLiteLog( 4482): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
D/ResourcesManager(10506): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/SQLiteDatabase( 4482): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4482): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4482): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4482): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 4482): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4482): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4482): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4482): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 4482): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4482): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4482): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4482): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFi,le:68)
E/SQLiteOpenHelper( 4482): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4482): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4482): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4482): Opened phenotype.db in read-only mode
,E/SQLiteLog( 4482): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4482): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/PCWCLIENTTRACE_LOG(10926): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10926): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10926): new DMDBOpenHelper instance
,E/SQLiteLog( 4482): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4482): (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
,E/GMPM-SVC( 4482): Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
E/ClearPendingStateOp( 4482): Runtime exception while performing operation
E/ClearPendingStateOp( 4482): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
E/ClearPendingStateOp( 4482): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 4482): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 4482): 	at java.lang.Thread.run(Thread.java:818)
,F/ClearPendingStateOp( 4482): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 4482): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
F/ClearPendingStateOp( 4482): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 4482): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 4482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 4482): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 4482): 	at java.lang.Thread.run(Thread.java:818)
,E/SharedPreferencesImpl( 4482): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SQLiteLog(10926): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(10945): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,I/UpdateIcingCorporaServi( 4036): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/PeopleContactsSync( 4482): CP2 sync disabled
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4482): Module APK com.google.android.play.games already loaded
,E/SQLiteDatabase(10926): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(10926): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10926): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10926): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10926): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10926): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10926): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10926): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10926): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10926): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10926): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10926): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10926): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10926): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10926): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10926): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10926): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10926): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10926): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10926): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10926): Shutting down VM
,E/AndroidRuntime(10926): FATAL EXCEPTION: main
E/AndroidRuntime(10926): Process: com.sec.pcw.device, PID: 10926
E/AndroidRuntime(10926): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10926): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10926): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10926): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10926): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10926): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10926): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10926): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10926): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10926): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10926): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10926): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10926): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10926): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10926): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10926): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10926): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10926): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10926): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10926): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10926): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10926): 	... 11 more
,W/ContextImpl(10945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
E/Watchdog( 3522): !@Sync 7
,V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,D/ChimeraCfgMgr( 4482): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4482): Module APK com.google.android.play.games already loaded
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 4482): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4482): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
E/DropBoxManagerService( 3522): Can't write: system_app_wtf
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop180.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
,E/SQLiteLog(10945): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10945): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(10945): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10945): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10945): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10945): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10945): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(10945): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(10945): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10945): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10945): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime(10945): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(10945): Process: com.android.keychain, PID: 10945
E/AndroidRuntime(10945): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10945): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10945): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10945): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10945): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(10945): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:55,4)
E/AndroidRuntime(10945): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10945): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10945): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3522): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
E/Zygote  (10975): MountEmulatedStorage()
E/Zygote  (10975): v2
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/003
I/libpersona(10975): KNOX_SDCARD checking this for 10035
I/libpersona(10975): KNOX_SDCARD not a persona
D/UsbHostManager( 3522): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3522): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3522): displayNotification : [0ah,00h,01h]
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3522): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
I/ActivityManager( 3522): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=10975 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux (10975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.android.keychain
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
E/SQLiteLog( 4036): (10) POSIX Error : 9 SQLite Error : 3850
D/UsbHostManager( 3522): displayNotification : [09h,00h,00h]
E/SQLiteLog( 4036): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/SELinux (10975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/Icing   ( 4482): doRemovePackageData com.example.hello
E/AndroidRuntime( 4036): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4036): Process: com.google.android.googlequicksearchbox:search, PID: 4036
E/AndroidRuntime( 4036): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4036): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 4036): 	at csx.d(PG:186)
E/AndroidRuntime( 4036): 	at cun.g(PG:594)
E/AndroidRuntime( 4036): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 4036): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:334)
E/AndroidRuntime( 4036): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 4036): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 4036): 	at cuy.ub(PG:301)
E/AndroidRuntime( 4036): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 4036): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 4036): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4036): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4036): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4036): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SELinux (10975): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Process (10926): Sending signal. PID: 10926 SIG: 9
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 4482): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 4482): Process: com.google.android.gms, PID: 4482
E/AndroidRuntime( 4482): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4482): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/AndroidRuntime( 4482): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 4482): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 4482): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 4482): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/AndroidRuntime( 4482): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/AndroidRuntime( 4482): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3143)
E/AndroidRuntime( 4482): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 4482): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/AndroidRuntime( 4482): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 4482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4482): 	at java.lang.Thread.run(Thread.java:818)
D/MtpClient( 9359): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient( 9359): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10506): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
D/TimaKeyStoreProvider(10975): TimaSignature is unavailable
D/ActivityThread(10975): Added TimaKeyStore provider
E/Zygote  (10993): MountEmulatedStorage()
E/Zygote  (10993): v2
I/libpersona(10993): KNOX_SDCARD checking this for 1000
I/libpersona(10993): KNOX_SDCARD not a persona
I/SELinux (10993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10506): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
I/SELinux (10993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10993 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Process (10945): Sending signal. PID: 10945 SIG: 9
,D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/JavaBinder( 3522): !!! FAILED BINDER TRANSACTION !!!
E/lowmemorykiller( 2825): Error writing /proc/10926/oom_score_adj; errno=22
I/ActivityManager( 3522): Killing 10099:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop184.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
,E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
I/EventHub( 3522): Removing device '/dev/input/event10' due to inotify event
D/TimaKeyStoreProvider(10993): TimaSignature is unavailable
,D/ActivityThread(10993): Added TimaKeyStore provider
,D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/ActivityManager( 3522): Process com.android.keychain (pid 10945)(adj 0) has died(216,1256)
,W/ActivityManager( 3522): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/ActivityManager( 3522): Process com.sec.pcw.device (pid 10926)(adj 9) has died(217,1256)
,I/EventHub( 3522): Removing device '/dev/input/event7' due to inotify event
,E/SQLiteLog( 4178): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4178): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4178): Shutting down VM
,E/AndroidRuntime( 4178): FATAL EXCEPTION: main
E/AndroidRuntime( 4178): Process: com.google.process.gapps, PID: 4178
E/AndroidRuntime( 4178): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4178): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4178): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4178): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4178): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4178): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4178): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4178): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4178): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4178): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4178): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4178): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4178): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4178): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4178): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4178): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4178): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4178): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 4178): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4178): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4178): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4178): 	... 9 more
,I/EventHub( 3522): Removing device '/dev/input/event8' due to inotify event
,I/Process ( 4482): Sending signal. PID: 4482 SIG: 9
,I/FeatureConfig(10975): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.google.process.gapps
,I/ActivityManager( 3522): Killing 10138:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,I/EventHub( 3522): Removing device '/dev/input/event9' due to inotify event
,I/Process ( 4036): Sending signal. PID: 4036 SIG: 9
,D/ResourcesManager(10993): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(10975): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop185.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ContextImpl(10277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:44 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:149 android.os.Handler.dispatchMessage:102 
,W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3522): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/Process ( 4178): Sending signal. PID: 4178 SIG: 9
,D/ConnectivityService( 3522): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@4924eb0)
,D/ConnectivityService( 3522): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager( 3522): Process com.google.android.gms (pid 4482)(adj 0) has died(289,1256)
W/ResourcesManager(10975): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/ConnectivityService( 3522): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 3522): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10827ms
W/ActivityManager( 3522): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10827ms
W/ActivityManager( 3522): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10827ms
W/ActivityManager( 3522): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10827ms
,I/EventHub( 3522): Removing device '/dev/input/event12' due to inotify event
,D/WifiService( 3522): Client connection lost with reason: 4
,D/AcmsPackageEventListener(10993): Received: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl(10993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ResourcesManager(10975): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/ActivityManager( 3522): Process com.google.android.googlequicksearchbox:search (pid 4036)(adj 0) has died(299,1256)
,W/ActivityManager( 3522): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 20802ms
W/ActivityManager( 3522): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 30802ms
,W/ActivityManager( 3522): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 30801ms
,I/EventHub( 3522): Removing device '/dev/input/event13' due to inotify event
,D/WifiService( 3522): Client connection lost with reason: 4
,D/ResourcesManager(10975): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/AcmsService(10993): Enter Oncreate
D/AcmsServiceMonitor(10993): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10993): creating AcmsCore
D/AcmsCore(10993): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10993): AcmsCore
,W/ResourcesManager(10975): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10975): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/AcmsCore(10993): init
D/AcmsCore(10993): Looper handler is not null
D/AcmsCore(10993): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10993): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10993): Incrementing - Counter value: 1
D/AcmsCore(10993): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(10993): onStartCommand
D/AcmsService(10993): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor(10993): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10993): Incrementing - Counter value: 2
D/AcmsService(10993): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr(10993): AcmsCertificateMngr
,D/AcmsRevocationMngr(10993): AcmsRevocationMngr
,D/ActivityThread(10993): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/UserAnalysis.UserAnalysisBroadcastReceiver(10313): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,D/UserAnalysis.SecurePlaceDbHelper(10313): SecurePlaceDbHelper() 
D/UserAnalysis.UserAnalysisBroadcastReceiver(10313): Create SecureDbHelper
,E/SQLiteLog(10993): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 3522): Process com.google.process.gapps (pid 4178)(adj 0) has died(304,1256)
,E/SQLiteDatabase(10993): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase(10993): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10993): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase(10993): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10993): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/SQLiteDatabase(10993): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/SQLiteDatabase(10993): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/SQLiteDatabase(10993): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/SQLiteDatabase(10993): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/SQLiteDatabase(10993): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10993): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10993): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10993): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10993): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10993): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 3522): Scheduling restart ,of crashed service com.google.android.gms/.gcm.GcmService in 40762ms
D/AndroidRuntime(10993): Shutting down VM
D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
E/AndroidRuntime(10993): FATAL EXCEPTION: main
E/AndroidRuntime(10993): Process: ACMS.Process, PID: 10993
E/AndroidRuntime(10993): java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@1145ad98 with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10993): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3326)
E/AndroidRuntime(10993): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/AndroidRuntime(10993): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/AndroidRuntime(10993): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10993): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10993): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10993): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10993): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10993): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10993): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/AndroidRuntime(10993): Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10993): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10993): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/AndroidRuntime(10993): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/AndroidRuntime(10993): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/AndroidRuntime(10993): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/AndroidRuntime(10993): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/AndroidRuntime(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/AndroidRuntime(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/AndroidRuntime(10993): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/AndroidRuntime(10993): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/AndroidRuntime(10993): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/AndroidRuntime(10993): 	... 9 more
E/AndroidRuntime(10993): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10993): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10993): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10993): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/AndroidRuntime(10993): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10993): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10993): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10993): 	... 20 more
,W/ResourcesManager(10975): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,E/SQLiteLog(10313): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/SQLiteDatabase(10313): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10313): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10313): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10313): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteDatabase(10313): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteDatabase(10313): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10313): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper(10313): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(10313): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10313): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10313): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10313): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteOpenHelper(10313): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteOpenHelper(10313): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteOpenHelper(10313): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper(10313): Opened privacy in read-only mode
,D/ActivityThread(10993): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
E/SQLiteLog(10993): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog(10313): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3522): Removing device '/dev/input/event14' due to inotify event
E/SQLiteDatabase(10313): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10313): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10313): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10313): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10313): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
E/SQLiteDatabase(10313): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10313): 	at java.lang.Thread.run(Thread.java:818)
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname ACMS.Process
W/System.err(10313): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(10313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(10313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(10313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(10313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(10313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(10313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(10313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(10313): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(10313): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(10313): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
W/System.err(10313): 	at com.samsung.,android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
W/System.err(10313): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase(10993): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase(10993): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10993): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10993): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase(10993): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10993): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10993): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/SQLiteDatabase(10993): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/SQLiteDatabase(10993): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/SQLiteDatabase(10993): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/SQLiteDatabase(10993): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.<init>(AcmsRevocationMngr.java:118)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.getAcmsRevocationMngr(AcmsRevocationMngr.java:128)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.<init>(AcmsCertificateMngr.java:94)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.getAcmsCertificateMngr(AcmsCertificateMngr.java:286)
E/SQLiteDatabase(10993): 	at com.samsung.android.mirrorlink.acms.api.AcmsCore$AcmsHandler.handleMessage(AcmsCore.java:138)
E/SQLiteDatabase(10993): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10993): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10993): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process (10993): Sending signal. PID: 10993 SIG: 9
,E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop186.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(10975): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(10975): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (11020): MountEmulatedStorage()
E/Zygote  (11020): v2
I/libpersona(11020): KNOX_SDCARD checking this for 10036
I/libpersona(11020): KNOX_SDCARD not a persona
,I/SELinux (11020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11020): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=11020 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 10172:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,I/ActivityManager( 3522): Process ACMS.Process (pid 10993)(adj 0) has died(309,1256)
,W/ActivityManager( 3522): Scheduling restart of crashed service com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService in 50662ms
,D/ResourcesManager(10975): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(10975): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10975): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.

```
