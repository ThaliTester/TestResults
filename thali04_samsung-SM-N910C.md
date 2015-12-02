#### Test 52383621d5a0cb8_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3521): !@Sync 4
D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 280, CUR = 32
D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:84
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/BatteryService( 3521): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11921): 
D/AndroidRuntime(11921): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11921): CheckJNI is OFF
D/AndroidRuntime(11921): readGMSProperty: start
D/AndroidRuntime(11921): readGMSProperty: already setted!!
D/AndroidRuntime(11921): readGMSProperty: end
D/AndroidRuntime(11921): addProductProperty: start
E/AffinityControl(11921): AffinityControl: registerfunction enter
D/AndroidRuntime(11921): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3521): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3521): mDVFSHelper.acquire()
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (11939): MountEmulatedStorage()
E/Zygote  (11939): v2
I/libpersona(11939): KNOX_SDCARD checking this for 10442
I/libpersona(11939): KNOX_SDCARD not a persona
I/SELinux (11939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11939 uid=10442 gids={50442, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(11921): Shutting down VM
E/SELinux (11939): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11939): TimaSignature is unavailable
D/ActivityThread(11939): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6415): updateVisibility : ActivityRecord{3f80c69f token=android.os.BinderProxy@5c98240 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager(11939): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/WebViewFactory(11939): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11939): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11939): Loading: webviewchromium
I/LibraryLoader(11939): Time to load native libraries: 3 ms (timestamps 5235-5238)
I/LibraryLoader(11939): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11939): Binding Chromium to main looper Looper (main, tid 1) {3c088a49}
,I/LibraryLoader(11939): Expected native library version number "",actual native library version number ""
I/chromium(11939): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11939): Initializing chromium process, renderers=0
,W/art     (11939): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11939): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11939): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11939): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11939): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11939): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11939): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11939): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11939): CordovaWebView is running on device made by: samsung
,W/art     (11939): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11939): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11939): performCreate Call secproduct feature valuefalse
D/Activity(11939): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11939): Render dirty regions requested: true
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11939): Initialized EGL, version 1.4
I/OpenGLRenderer(11939): HWUI protection enabled for context ,  &this =0xaf6ad1a0 ,&mEglDisplay = 1 , &mEglConfig = -1280847600 
D/OpenGLRenderer(11939): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11939): Enabling debug mode 0
D/mali_winsys(11939): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11939): updateVisibility : ActivityRecord{398b97b9 token=android.os.BinderProxy@2ece1e4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3521): mDVFSHelper.release()
,I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{3494ee2b u0 com.test.thalitest/.MainActivity t26} time:135567
,W/IInputConnectionWrapper(11939): showStatusIcon on inactive InputConnection
,I/Timeline(11939): Timeline: Activity_idle id: android.os.BinderProxy@2ece1e4 time:135575
,D/JsMessageQueue(11939): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11939): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11939): 
,D/jxcore_app_log(11939): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357479424
D/JX-Cordova(11939): jxcore cordova android initializing
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11939): Initializing JXcore engine
W/jxcore-log(11939): JXcore engine is ready
,W/jxcore-log(11939): Starting JXcore engine
,E/auditd  ( 4634): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3521): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3521): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11939): Platform android
W/jxcore-log(11939): 
W/jxcore-log(11939): Process ARCH arm
W/jxcore-log(11939): 
,I/jxcore-log(11939): JXcore Cordova bridge is ready!
I/jxcore-log(11939): 
W/jxcore-log(11939): JXcore engine is started
,E/jxcore  (11939): Error!: Cannot find module '../server-address.js'
E/jxcore  (11939): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium(11939): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,W/ScreenOrientationListener(11939): Removing an inexistent observer!
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,E/ViewRootImpl(11939): sendUserActionEvent() mView == null
,W/ActivityManager( 3521): mDVFSHelper.acquire()
,I/DBG_DM  ( 6415): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6415): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 7
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6415): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
D/SecContentProvider2( 3521): mCursor = null
,D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
D/PanelView( 3692): There is/are notification(s) 
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6415): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6415): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6415): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6415): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6415): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,I/DBG_DM  ( 6415): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2849): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6415): updateVisibility : ActivityRecord{3f80c69f token=android.os.BinderProxy@5c98240 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(11939): showStatusIcon on inactive InputConnection
,I/Timeline( 6415): Timeline: Activity_idle id: android.os.BinderProxy@5c98240 time:137172
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{170b40b2 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:137191
W/ActivityManager( 3521): mDVFSHelper.release()
,D/TaskPersister( 3521): removeObsoleteFile: deleting file=24_task.xml
,I/ActivityManager( 3521): Killing 11181:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 278, CUR = 59
,I/PowerManagerService( 3521): [PWL] Off : 50s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3521): [MSG] WRITE_PACKAGE_RESTRICTIONS
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 275, CUR = 31
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 5
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 272, CUR = 50
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 75s ago
,V/AlarmManager( 3521): waitForAlarm result :8
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 271, CUR = 55
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4643): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 270, CUR = 54
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 6
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 266, CUR = 51
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 105s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 261, CUR = 49
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 259, CUR = 45
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 7
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 258, CUR = 43
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 140s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 256, CUR = 40
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 255, CUR = 40
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 8
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 253, CUR = 39
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 252, CUR = 36
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 180s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 250, CUR = 36
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 9
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 248, CUR = 35
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 247, CUR = 36
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3521): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 4780): Aggregate from 1449054851337 (log), 1449054851337 (data)
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 246, CUR = 35,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3521): initializing...
,I/TLC_TIMA_PKM_initialize( 3521): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3521): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3521): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3521): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3521): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3521): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3521): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3521): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3521): device_id = 0x0
,I/TZ: mc_tlc_communication( 3521): tlc_open() was called
I/TZ: mc_tlc_communication( 3521): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3521): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3521): Opening the session
,I/TZ: mc_tlc_communication( 3521): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3521): Trustlet response is completed
,E/Watchdog( 3521): !@Sync 10
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 245, CUR = 34
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 225s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 245, CUR = 33,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 244, CUR = 31
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3521): !@Sync 11
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 244, CUR = 31,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :8
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 243, CUR = 29
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 242, CUR = 28
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 3521): [PWL] Off : 275s ago
,E/Watchdog( 3521): !@Sync 12
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 242, CUR = 29
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 242, CUR = 29,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 241, CUR = 28
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 13
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 241, CUR = 29
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 330s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 14
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 27
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 15
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 390s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 16
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 23
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 17
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :8
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 455s ago
,E/Watchdog( 3521): !@Sync 18
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 24
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 19
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 21
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 18,
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3521): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3521): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 19
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 525s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3521): Killing 10450:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3521): !@Sync 21
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 22
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 239, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 600s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 239, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 23
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 239, CUR = 18
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 238, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged,
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 238, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 24
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 238, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 237, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 237, CUR = 18
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 25
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 237, CUR = 18
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 680s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 236, CUR = 18
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 236, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 26
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 236, CUR = 16
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 235, CUR = 15,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 235, CUR = 17,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 27
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 235, CUR = 16
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 234, CUR = 15
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 234, CUR = 15,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 28
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 234, CUR = 16
,I/PowerManagerService( 3521): [PWL] Off : 765s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 233, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 233, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-12
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 29
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 233, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 232, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 232, CUR = 14
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 232, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 231, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 231, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3521): stay LED for fully charged
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 31
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 231, CUR = 14
,I/PowerManagerService( 3521): [PWL] Off : 855s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 32
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 33
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 34
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 950s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 35
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/Watchdog( 3521): !@Sync 36
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,E/Watchdog( 3521): !@Sync 37
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3521): !@Sync 38
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3521): !@Sync 39
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 11
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3521): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3521): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3521): Updating Usage Statistics in DB @ 1449057620546
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.a,ndroid.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3521): Done Updating Usage Statistics in DB @ 1449057620631
,E/Watchdog( 3521): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3521): !@Sync 41
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 3521): Background sticky concurrent mark sweep GC freed 105663(9MB) AllocSpace objects, 352(5MB) LOS objects, 13% free, 49MB/57MB, paused 3.325ms total 130.564ms
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,I/PowerManagerService( 3521): [PWL] Off : 1155s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3521): !@Sync 42
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19,
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3521): !@Sync 43
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3521): !@Sync 44
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,I/PowerManagerService( 3521): [PWL] Off : 1265s ago
,E/Watchdog( 3521): !@Sync 45
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3521): !@Sync 46
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3521): !@Sync 47
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3521): !@Sync 48
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,I/PowerManagerService( 3521): [PWL] Off : 1380s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3521): !@Sync 49
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3521): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3521): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3521): !@Sync 51
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6,
,E/Watchdog( 3521): !@Sync 52
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged,
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,I/PowerManagerService( 3521): [PWL] Off : 1500s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,E/Watchdog( 3521): !@Sync 53
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3521): Plugged,
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3521): !@Sync 54
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,E/Watchdog( 3521): !@Sync 55
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3521): !@Sync 56
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,I/PowerManagerService( 3521): [PWL] Off : 1625s ago
,E/Watchdog( 3521): !@Sync 57
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/LightsService( 3521): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3521): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3521): #>LightSensor r=140 g=134 b=110 c=289 atime=238 again=64 lux=48.000000
,D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 48
I/Sensors ( 3521): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3521): unregisterListener ::   
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,V/AlarmManager( 3521): waitForAlarm result :8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3521): !@Sync 58,
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 59
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3521): waitForAlarm result :8
,D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,V/AlarmManager( 3521): OOI=Alarm{de4ed8a type 0 when 1449060009010 com.google.android.gms}
,V/AlarmManager( 3521): waitForAlarm result :4
,V/GLSActivity( 4131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/System.out( 4131): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4131): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4131): Tagging socket 33 with tag 1000040100000000{268436481,0} uid 10014, pid: 4131, getuid(): 10014
,I/qtaguid ( 4131): Tagging socket 48 with tag 1000040100000000{268436481,0} uid 10014, pid: 4131, getuid(): 10014
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3521): !@Sync 60,
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 61
,I/PowerManagerService( 3521): [PWL] Off : 1755s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3521): stay LED for fully charged
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3521): waitForAlarm result :8
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 62
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,I/art     ( 3521): Background partial concurrent mark sweep GC freed 51630(4MB) AllocSpace objects, 195(3MB) LOS objects, 24% free, 49MB/65MB, paused 3.055ms total 195.371ms
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 63
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 64
,I/MMD     ( 2867): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms)
```
