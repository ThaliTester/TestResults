#### Test 50388019c82294c_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3531): !@Sync 3
,--------- beginning of main
D/AndroidRuntime(10614): 
D/AndroidRuntime(10614): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10614): CheckJNI is OFF
D/AndroidRuntime(10614): readGMSProperty: start
D/AndroidRuntime(10614): readGMSProperty: already setted!!
D/AndroidRuntime(10614): readGMSProperty: end
D/AndroidRuntime(10614): addProductProperty: start
E/AffinityControl(10614): AffinityControl: registerfunction enter
D/AndroidRuntime(10614): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3531): inState():  stateMachine is null !!
I/PersonaManagerService( 3531): PersonaId don't exist
I/ActivityManager( 3531): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3531): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3531): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3531): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3531): mDVFSHelper.acquire()
D/FocusedStackFrame( 3531): Set to : 0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (10632): MountEmulatedStorage()
E/Zygote  (10632): v2
I/libpersona(10632): KNOX_SDCARD checking this for 10400
I/libpersona(10632): KNOX_SDCARD not a persona
I/SELinux (10632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3531): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10632 uid=10400 gids={50400, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (10632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10632): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10614): Shutting down VM
D/PointerIcon( 3531): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3531): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3531): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3531): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10632): TimaSignature is unavailable
D/ActivityThread(10632): Added TimaKeyStore provider
V/WindowOrientationListener( 3531): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3531): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3531): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3531): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3531): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3999): updateVisibility : ActivityRecord{ef477a5 token=android.os.BinderProxy@10bdefef {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3999): onTrimMemory. Level: 20
D/ResourcesManager(10632): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/WebViewFactory(10632): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10632): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10632): Loading: webviewchromium
I/LibraryLoader(10632): Time to load native libraries: 5 ms (timestamps 3804-3809)
I/LibraryLoader(10632): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10632): Binding Chromium to main looper Looper (main, tid 1) {91c5352}
I/LibraryLoader(10632): Expected native library version number "",actual native library version number ""
I/chromium(10632): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(10632): Initializing chromium process, renderers=0
W/art     (10632): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(10632): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AlarmManager( 3531): waitForAlarm result :8
W/chromium(10632): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(10632): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10632): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10632): 98477603: getState() :  mService = null. Returning STATE_OFF
W/chromium(10632): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(10632): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:94, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:127
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3531): stay LED for fully charged
I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
W/art     (10632): Attempt to remove local handle scope entry from IRT, ignoring
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
W/AwContents(10632): onDetachedFromWindow called when already detached. Ignoring
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/SystemWebViewEngine(10632): CordovaWebView is running on device made by: samsung
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/art     (10632): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10632): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(10632): performCreate Call secproduct feature valuefalse
D/Activity(10632): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(10632): Render dirty regions requested: true
D/ActivityManager( 3531): post active user change for 0
D/KnoxTimeoutHandler( 3531): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3531): handleActiveUserChange for user 0
I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3531): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3531): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3531): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3531): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3531): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3531): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10632): Initialized EGL, version 1.4
I/OpenGLRenderer(10632): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278947056 
D/OpenGLRenderer(10632): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10632): Enabling debug mode 0
D/mali_winsys(10632): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(10632): updateVisibility : ActivityRecord{37d55e13 token=android.os.BinderProxy@21d766a1 {com.example.hello/com.example.hello.MainActivity}} show : true
D/InputMethodManagerService( 3531): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3531): mDVFSHelper.release()
I/Timeline( 3531): Timeline: Activity_windows_visible id: ActivityRecord{e683308 u0 com.example.hello/.MainActivity t25} time:104246
D/SSRM:n  ( 3531): SIOP:: AP = 270, PST = 311, CUR = 94
I/art     ( 3531): Explicit concurrent mark sweep GC freed 50553(3MB) AllocSpace objects, 16(256KB) LOS objects, 24% free, 48MB/64MB, paused 1.634ms total 155.768ms
W/IInputConnectionWrapper(10632): showStatusIcon on inactive InputConnection
I/Timeline(10632): Timeline: Activity_idle id: android.os.BinderProxy@21d766a1 time:104397
I/chromium(10632): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler(10632): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue(10632): Set native->JS mode to OnlineEventsBridgeMode
I/chromium(10632): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10632): 
,D/jxcore_app_log(10632): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361672448
D/JX-Cordova(10632): jxcore cordova android initializing
,W/jxcore-log(10632): Initializing JXcore engine
W/jxcore-log(10632): JXcore engine is ready
,W/jxcore-log(10632): Starting JXcore engine
,E/auditd  ( 4543): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3531): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3531): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10632): Platform android
W/jxcore-log(10632): 
W/jxcore-log(10632): Process ARCH arm
W/jxcore-log(10632): 
,I/jxcore-log(10632): JXcore Cordova bridge is ready!
I/jxcore-log(10632): 
W/jxcore-log(10632): JXcore engine is started
,E/jxcore-log(10632): >> samsung-SM-N910C
E/jxcore-log(10632): 
,I/jxcore-log(10632): Total memory 2970812416
I/jxcore-log(10632): 
,I/jxcore-log(10632): Free memory 112091136
I/jxcore-log(10632): 
I/jxcore-log(10632): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10632): 
I/jxcore-log(10632): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10632): 
,I/jxcore-log(10632): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10632): 
,I/jxcore-log(10632): Size 1440 2560
I/jxcore-log(10632): 
,I/jxcore-log(10632): Screen Brightness 134
I/jxcore-log(10632): 
,E/jxcore-log(10632): Dummy Error Log.
E/jxcore-log(10632): 
,I/jxcore-log(10632): getBuffer is called!!!!
I/jxcore-log(10632): 
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3531): [PWL] Off : 15s ago
,D/BluetoothAdapter(10632): disable()
,E/BluetoothManagerService( 3531): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3531): New client listening to asynchronous messages
,I/WifiManager(10632): packageName : com.example.hello
,D/SecContentProvider( 3531): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3531): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3531): mCursor = null
,D/WifiService( 3531): setWifiEnabled: false pid=10632, uid=10400
,E/WifiService( 3531): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3531): name = wifi_on
,I/jxcore-log(10632): ****TEST TOOK:  5074  ms ****
I/jxcore-log(10632): 
,I/jxcore-log(10632): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10632): 
,D/AndroidRuntime(10739): 
D/AndroidRuntime(10739): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10739): CheckJNI is OFF
,D/AndroidRuntime(10739): readGMSProperty: start
D/AndroidRuntime(10739): readGMSProperty: already setted!!
D/AndroidRuntime(10739): readGMSProperty: end
D/AndroidRuntime(10739): addProductProperty: start
,E/AffinityControl(10739): AffinityControl: registerfunction enter
,D/AndroidRuntime(10739): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3531): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 3531): START PACKAGE DELETE: observer{733433995}
D/PackageManager( 3531): pkg{<packageName>}
D/PackageManager( 3531): user{0}
D/PackageManager( 3531): caller{2000}
D/PackageManager( 3531): flags{3}
D/PersonaManagerService( 3531): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3531): [MSG] DELETE_PACKAGE_AS_USER
,D/PersonaManagerService( 3531): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3531): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3531): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3531): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManager( 3531): !@killApplicatoin: 10400, uninstall pkg
D/PackageManagerService( 3531): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3531): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3531): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 3531): Force stopping com.example.hello appid=10400 user=-1: uninstall pkg
,I/ActivityManager( 3531): Killing 10632:com.example.hello/u0a400 (adj 0): stop com.example.hello
,I/ActivityManager( 3531):   Force finishing activity ActivityRecord{e683308 u0 com.example.hello/.MainActivity t25}
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3531): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3531): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3531): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3531): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3531): Skipping PackageSetting{2c3eba80 com.test.thalitest/10394} due to missing metadata
,I/ActivityManager( 3531): Force stopping com.example.hello appid=10400 user=0: pkg removed
,D/WifiService( 3531): Client connection lost with reason: 4
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     ( 7965): Explicit concurrent mark sweep GC freed 27179(1545KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.063ms total 46.216ms
,I/InputReader( 3531): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4272): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4447): mOCRHelper is null
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
D/LWLocationManager(10225): getDeviceLocationId :  id = -100
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
D/LocationWidgetApplication(10225): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/talkback/talkback.apk
E/Zygote  (10760): MountEmulatedStorage()
E/Zygote  (10760): v2
I/libpersona(10760): KNOX_SDCARD checking this for 10063
I/libpersona(10760): KNOX_SDCARD not a persona
,I/SELinux (10760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3531): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10760 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (10760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10760): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseDeviceManagerService( 3531): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3531): Admin package name: com.google.android.gms
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/TimaKeyStoreProvider(10760): TimaSignature is unavailable
,D/ActivityThread(10760): Added TimaKeyStore provider
D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/art     ( 3531): Explicit concurrent mark sweep GC freed 16529(1389KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 2.102ms total 168.401ms
,I/art     ( 3531): WaitForGcToComplete blocked for 144.342ms for cause Explicit
D/ResourcesManager( 3531): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(10760): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/ResourceType( 4966): For resource 0x7f020a0f, entry index(2575) is beyond type entryCount(725)
,W/ResourceType( 4966): Failure getting entry for 0x7f020a0f (t=1 e=2575) (error -75)
W/ResourceType( 4966): For resource 0x7f020a62, entry index(2658) is beyond type entryCount(725)
W/ResourceType( 4966): Failure getting entry for 0x7f020a62 (t=1 e=2658) (error -75)
,D/VRSetupWizardStub/PackageIntentReceiver(10760): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10760): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10760): packagename:com.example.hello
,W/ResourceType( 4966): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4966): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (10777): MountEmulatedStorage()
E/Zygote  (10777): v2
I/libpersona(10777): KNOX_SDCARD checking this for 10021
I/libpersona(10777): KNOX_SDCARD not a persona
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/SELinux (10777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3531): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10777 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (10777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Killing 9717:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/RegisteredServicesCache( 3966): empty dynamic service
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/TimaKeyStoreProvider(10777): TimaSignature is unavailable
,D/ActivityThread(10777): Added TimaKeyStore provider
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/SecContentProvider2( 3531): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3531): mCursor = null
,D/ResourcesManager(10777): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/ResourceType( 3531): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/art     ( 3531): Explicit concurrent mark sweep GC freed 6363(371KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.818ms total 145.632ms
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10225): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10777): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:44:31 GMT+01:00 2015
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/KLMS-2.4.521: (10777): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3531): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=24, mSplitNum[2]=34 divideNum= 10 r.nextReceiver= 2 receivers.size=44
,I/splitIntent( 3531): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10225): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3531): delete codoeFile: 
D/ResourcesManager(10225): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/AASAUninstall( 3531):  com.example.hello not target!
D/PackageManager( 3531): result of delete: 1{733433995}
D/AndroidRuntime(10739): Shutting down VM
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10225): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10225): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10225): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10225): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/Zygote  (10794): MountEmulatedStorage()
E/Zygote  (10794): v2
I/libpersona(10794): KNOX_SDCARD checking this for 10106
I/libpersona(10794): KNOX_SDCARD not a persona
,I/SELinux (10794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3531): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10794 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (10777): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (10777): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (10777): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux (10794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/KLMS-2.4.521: (10777): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/SELinux (10794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10777): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (10777): KLMSIntentService(): listeningToPackageRemoved().START
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/KLMS-2.4.521: (10777): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  (10808): MountEmulatedStorage()
E/Zygote  (10808): v2
I/libpersona(10808): KNOX_SDCARD checking this for 10101
I/libpersona(10808): KNOX_SDCARD not a persona
,I/SELinux (10808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/TimaKeyStoreProvider(10794): TimaSignature is unavailable
E/SELinux (10808): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityThread(10794): Added TimaKeyStore provider
,I/ActivityManager( 3531): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10808 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10808): TimaSignature is unavailable
,D/ActivityThread(10808): Added TimaKeyStore provider
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(10794): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager(10225): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/Zygote  (10825): MountEmulatedStorage()
E/Zygote  (10825): v2
I/libpersona(10825): KNOX_SDCARD checking this for 10190
I/libpersona(10825): KNOX_SDCARD not a persona
,D/elm:14491(10794): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(10794): ELMEngine.ELMEngine( context ).
,D/elm:14491(10794): MDMBridge.setEnterpriseBridge()
,I/SELinux (10825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/ActivityManager( 3531): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10825 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (10825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10825): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/elm:14491(10794): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/ResourcesManager( 3531): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/elm:14491(10794): ElmAgentService : onCreate()
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/elm:14491(10794): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,W/ResourcesManager( 3531): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(10794): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10794): MDMBridge.getInstance()
D/elm:14491(10794): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/elm:14491(10794): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (10777): KLMSIntentService(): listeningToPackageRemoved().END
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10825): TimaSignature is unavailable
,D/ActivityThread(10825): Added TimaKeyStore provider
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(10808): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  (10843): MountEmulatedStorage()
I/libpersona(10843): KNOX_SDCARD checking this for 10019
E/Zygote  (10843): v2
I/libpersona(10843): KNOX_SDCARD not a persona
I/SELinux (10843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/SELinux (10843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/SELinux (10843): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10843 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3531): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/RCPManagerService( 3531): PackageReceiver onReceive()
I/HarmonyEASService( 3531): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/KLMS-2.4.521: (10777): KLMSIntentService(): onDestroy()
D/KnoxMUMContainerPolicy( 3531): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
D/BackupManagerService( 3531): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/elm:14491(10794): ElmAgentService : onDestroy().
D/JobSchedulerService( 3531): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3531): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3531): uID is 10400
V/EnterpriseBillingPolicy( 3531): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3531): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3531): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3531): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3531): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3531): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 3531): getBillingProfileForVpnEngine - end - null
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3531): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/TaskPersister( 3531): removeObsoleteFile: deleting file=25_task.xml
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Mms/FreeMessageStatusReceiver(10500): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/Resources( 3531): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3531): clearDefaults: com.example.hello
I/CrashAnrDetector( 3531): onPackageRemoved : com.example.hello
,D/TimaKeyStoreProvider(10843): TimaSignature is unavailable
,D/ActivityThread(10843): Added TimaKeyStore provider
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(10825): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/Mms/FreeMessageReceiverService(10500): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(10500): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/ActivityManager( 3531): Killing 9916:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/ResourcesManager(10843): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10825): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10825): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TactileAssist( 3531): enable value -1
I/TactileAssist( 3531): internal enable value -1
I/TactileAssist( 3531): intensity value -1
I/TactileAssist( 3531): saveAppList value true
,I/TapandpayWidget:Utils(10825): Clear T&P info.
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Books/Books.apk
,D/DocsApplication(10808): Installing DEX configuration.
,I/TactileAssist( 3531): List of disabled apps :
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10825): Widget is not attached.
,D/DexInstaller(10808): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(10808): Provided clientMode=RELEASE, packageInfo=PackageInfo{26f4cab com.google.android.apps.docs}
,D/TAG     (10808): onCreate()
,D/CrossAppStateProvider(10808): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10843): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(10843): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10843): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/LocationWidgetApplication(10225): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Zygote  (10862): MountEmulatedStorage()
I/libpersona(10862): KNOX_SDCARD checking this for 10059
E/Zygote  (10862): v2
I/libpersona(10862): KNOX_SDCARD not a persona
,I/SELinux (10862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10862): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/ActivityManager( 3531): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10862 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 3531): Killing 9964:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/TimaKeyStoreProvider(10862): TimaSignature is unavailable
,D/ActivityThread(10862): Added TimaKeyStore provider
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 8711(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 917us total 35.239ms
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 652us total 16.300ms
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.014ms total 15.542ms
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,E/Zygote  (10877): MountEmulatedStorage()
I/libpersona(10877): KNOX_SDCARD checking this for 10110
E/Zygote  (10877): v2
I/libpersona(10877): KNOX_SDCARD not a persona
D/UsbHostManager( 3531): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3531): displayNotification : [02h,02h,01h]
,I/SELinux (10877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3531): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=10877 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/UsbHostManager( 3531): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3531): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3531): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3531): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3531): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/UsbHostManager( 3531): displayNotification : [0ah,00h,01h]
,I/SELinux (10877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3531): Killing 9985:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
D/ResourcesManager(10225): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/SELinux (10877): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3531): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3531): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3531): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3531): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3531): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/TimaKeyStoreProvider(10877): TimaSignature is unavailable
,D/ActivityThread(10877): Added TimaKeyStore provider
,D/MtpClient(10413): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/ResourcesManager(10225): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
D/MtpClient(10413): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10862): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(10862): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/UsbHostManager( 3531): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3531): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ResourcesManager(10225): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/Zygote  (10899): MountEmulatedStorage()
E/Zygote  (10899): v2
I/libpersona(10899): KNOX_SDCARD checking this for 1000
I/libpersona(10899): KNOX_SDCARD not a persona
,I/SELinux (10899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10899 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3531): Killing 9943:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/ResourcesManager(10225): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/Compatibility(10862): onReceive() it will make start service
,I/EventHub( 3531): Removing device '/dev/input/event10' due to inotify event
,I/EventHub( 3531): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(10225): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/TimaKeyStoreProvider(10899): TimaSignature is unavailable
,D/ActivityThread(10899): Added TimaKeyStore provider
,I/EventHub( 3531): Removing device '/dev/input/event8' due to inotify event
,D/Compatibility(10862): onHandleIntent()
,D/Compatibility(10862): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10400, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/ResourcesManager(10877): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,D/Compatibility(10862): found: 2
,D/Compatibility(10862): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10862): skipping ResolveInfo{2a01ef08 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
I/EventHub( 3531): Removing device '/dev/input/event9' due to inotify event
,D/Compatibility(10862): considering ResolveInfo{21d766a1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10862): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10862): enabling receiver ResolveInfo{b81f0c6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ResourcesManager(10225): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/Compatibility(10862): enabling receiver ResolveInfo{3cd40887 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/EventHub( 3531): Removing device '/dev/input/event11' due to inotify event
,I/UpdateIcingCorporaServi( 4053): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/ResourcesManager(10899): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/Compatibility(10862): enabling receiver ResolveInfo{204af3b4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/EventHub( 3531): Removing device '/dev/input/event12' due to inotify event
,D/Compatibility(10862): enabling receiver ResolveInfo{762cbdd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/EventHub( 3531): Removing device '/dev/input/event13' due to inotify event
,D/Compatibility(10862): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/UserAnalysis.UserAnalysisBroadcastReceiver(10101): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/UserAnalysis.SecurePlaceDbHelper(10101): SecurePlaceDbHelper() 
D/UserAnalysis.UserAnalysisBroadcastReceiver(10101): Create SecureDbHelper
,I/PCWCLIENTTRACE_LOG(10899): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG(10899): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper(10899): new DMDBOpenHelper instance
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3531): Removing device '/dev/input/event14' due to inotify event
,E/SQLiteLog(10899): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10899): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(10899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10899): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10899): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10899): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10899): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10899): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10899): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10899): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(10899): Shutting down VM
,E/AndroidRuntime(10899): FATAL EXCEPTION: main
E/AndroidRuntime(10899): Process: com.sec.pcw.device, PID: 10899
E/AndroidRuntime(10899): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10899): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10899): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10899): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10899): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10899): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10899): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10899): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10899): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10899): 	... 11 more
E/SQLiteLog(10101): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10101): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10101): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10101): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10101): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteDatabase(10101): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteDatabase(10101): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10101): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper(10101): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(10101): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10101): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10101): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10101): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteOpenHelper(10101): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteOpenHelper(10101): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteOpenHelper(10101): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper(10101): Opened privacy in read-only mode
,E/Zygote  (10918): MountEmulatedStorage()
,E/Zygote  (10918): v2
,E/SQLiteLog(10101): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
I/libpersona(10918): KNOX_SDCARD checking this for 1000
I/libpersona(10918): KNOX_SDCARD not a persona
,I/SELinux (10918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/SQLiteDatabase(10101): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10101): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10101): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10101): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10101): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
E/SQLiteDatabase(10101): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10101): 	at java.lang.Thread.run(Thread.java:818)
,W/System.err(10101): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/System.err(10101): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
I/SELinux (10918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/System.err(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(10101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
,W/System.err(10101): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/SELinux (10918): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/System.err(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,W/System.err(10101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,E/SQLiteLog( 4053): (10) POSIX Error : 9 SQLite Error : 3850
,W/System.err(10101): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
I/ActivityManager( 3531): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=10918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/System.err(10101): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(10101): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(10101): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10101): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(10101): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(10101): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
W/System.err(10101): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
W/System.err(10101): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 4053): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager( 3531): Killing 10051:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,E/AndroidRuntime( 4053): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4053): Process: com.google.android.googlequicksearchbox:search, PID: 4053
E/AndroidRuntime( 4053): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 4053): 	at csx.d(PG:186)
E/AndroidRuntime( 4053): 	at cun.g(PG:594)
E/AndroidRuntime( 4053): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 4053): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:334)
E/AndroidRuntime( 4053): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 4053): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 4053): 	at cuy.ub(PG:301)
E/AndroidRuntime( 4053): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 4053): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 4053): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4053): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4053): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4053): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/ApplicationPolicy( 3531): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
,V/ApplicationPolicy( 3531): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device

```
