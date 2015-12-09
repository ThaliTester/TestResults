#### Test 5065027873d6a28_thali04_samsung-SM-N910C Logs


```
--------- beginning of system,
I/PowerManagerService( 3522): [PWL] Off : 140s ago
D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 264, CUR = 77
--------- beginning of main
D/AndroidRuntime(13728): 
D/AndroidRuntime(13728): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13728): CheckJNI is OFF
D/AndroidRuntime(13728): readGMSProperty: start
D/AndroidRuntime(13728): readGMSProperty: already setted!!
D/AndroidRuntime(13728): readGMSProperty: end
D/AndroidRuntime(13728): addProductProperty: start
E/AffinityControl(13728): AffinityControl: registerfunction enter
D/AndroidRuntime(13728): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (13746): MountEmulatedStorage()
I/libpersona(13746): KNOX_SDCARD checking this for 10470
E/Zygote  (13746): v2
I/libpersona(13746): KNOX_SDCARD not a persona
I/SELinux (13746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=13746 uid=10470 gids={50470, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (13746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13746): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(13728): Shutting down VM
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(13746): TimaSignature is unavailable
D/ActivityThread(13746): Added TimaKeyStore provider
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6298): updateVisibility : ActivityRecord{4633bd6 token=android.os.BinderProxy@142165fb {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager(13746): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/WebViewFactory(13746): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(13746): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(13746): Loading: webviewchromium
I/LibraryLoader(13746): Time to load native libraries: 3 ms (timestamps 5732-5735)
I/LibraryLoader(13746): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(13746): Binding Chromium to main looper Looper (main, tid 1) {97d6741}
,I/LibraryLoader(13746): Expected native library version number "",actual native library version number ""
,I/chromium(13746): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:78, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:83
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,I/BrowserStartupController(13746): Initializing chromium process, renderers=0
,W/art     (13746): Attempt to remove local handle scope entry from IRT, ignoring
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,W/chromium(13746): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(13746): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(13746): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/chromium(13746): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(13746): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (13746): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(13746): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(13746): CordovaWebView is running on device made by: samsung
,W/art     (13746): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (13746): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 3522): Activity pause timeout for ActivityRecord{2ae17e4f u0 com.test.thalitest/.MainActivity t26}
,D/Activity(13746): performCreate Call secproduct feature valuefalse
,D/Activity(13746): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(13746): Render dirty regions requested: true
,D/ActivityManager( 3522): post active user change for 0
,D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,V/ActivityThread(13746): updateVisibility : ActivityRecord{24cda2b1 token=android.os.BinderProxy@21b98a3c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger( 2852): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(13746): Initialized EGL, version 1.4
,I/OpenGLRenderer(13746): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279766256 
,D/OpenGLRenderer(13746): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(13746): Enabling debug mode 0
,D/mali_winsys(13746): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{2ae17e4f u0 com.test.thalitest/.MainActivity t26} time:296263
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 85677(5MB) AllocSpace objects, 57(912KB) LOS objects, 24% free, 49MB/65MB, paused 2.272ms total 162.313ms
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(13746): showStatusIcon on inactive InputConnection
I/Timeline(13746): Timeline: Activity_idle id: android.os.BinderProxy@21b98a3c time:296428
,I/chromium(13746): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(13746): 
,D/JsMessageQueue(13746): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(13746): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1359522688
D/JX-Cordova(13746): jxcore cordova android initializing
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13825): MountEmulatedStorage()
E/Zygote  (13825): v2
I/libpersona(13825): KNOX_SDCARD checking this for 1000
I/libpersona(13825): KNOX_SDCARD not a persona
,I/SELinux (13825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.android.settings for preferred application com.android.settings: pid=13825 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (13825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13825): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(13825): TimaSignature is unavailable
,D/ActivityThread(13825): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 12289:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/ResourcesManager(13825): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(13825): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(13825): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(13825): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(13825): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13825): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(13825): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13825): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/MySettingsProvider(13825): DatabaseHelper(Context context):DATABASE_VERSION=1
,E/SQLiteLog(13825): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/MySettingsProvider(13825): onCreate():(mDB == null)? false:true  =true
,W/jxcore-log(13746): Initializing JXcore engine
W/jxcore-log(13746): JXcore engine is ready
,W/jxcore-log(13746): Starting JXcore engine
,E/auditd  ( 4632): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(13746): Platform android
W/jxcore-log(13746): 
W/jxcore-log(13746): Process ARCH arm
W/jxcore-log(13746): 
,I/jxcore-log(13746): JXcore Cordova bridge is ready!
I/jxcore-log(13746): 
W/jxcore-log(13746): JXcore engine is started
,E/jxcore  (13746): Error!: missing ) after argument list
E/jxcore  (13746): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium(13746): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager( 3522): Killing 12327:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,W/ScreenOrientationListener(13746): Removing an inexistent observer!
,I/SurfaceFlinger( 2852): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2852): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,E/ViewRootImpl(13746): sendUserActionEvent() mView == null
,W/ActivityManager( 3522): mDVFSHelper.acquire()
,I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 7
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6298): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
,D/ApplicationPolicy( 3522): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
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
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6298): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6298): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6298): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2852): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6298): updateVisibility : ActivityRecord{4633bd6 token=android.os.BinderProxy@142165fb {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(13746): showStatusIcon on inactive InputConnection
,I/Timeline( 6298): Timeline: Activity_idle id: android.os.BinderProxy@142165fb time:297963
,I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{13de9e0 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:297981
W/ActivityManager( 3522): mDVFSHelper.release()
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=24_task.xml
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 263, CUR = 78
,D/PackageManager( 3522): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:81
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3522): initializing...
,I/TLC_TIMA_PKM_initialize( 3522): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3522): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3522): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3522): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3522): device_id = 0x0
,I/TZ: mc_tlc_communication( 3522): tlc_open() was called
I/TZ: mc_tlc_communication( 3522): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3522): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 3522): Opening the session
,I/TZ: mc_tlc_communication( 3522): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3522): Trustlet response is completed
,E/Watchdog( 3522): !@Sync 10
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 263, CUR = 57
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 13881
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:69, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:81
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 262, CUR = 69
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:70, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 180s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 261, CUR = 70
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:70, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 11
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 260, CUR = 70
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 258, CUR = 70
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:69, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 257, CUR = 69
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:68, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 12
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 68
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 225s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 67
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity(11150): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(11150): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(11150): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12103): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12103): (HTTPLog)-Static: isShipBuild true
I/System.out(12103): (HTTPLog)-Thread-1688-174877785: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12103): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10031
,I/System.out(12103): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 255, CUR = 65
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,E/Watchdog( 3522): !@Sync 13
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 254, CUR = 63
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 254, CUR = 62,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 253, CUR = 62
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 275s ago
,E/Watchdog( 3522): !@Sync 14
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 253, CUR = 61
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 252, CUR = 60
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity(11150): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(11150): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(11150): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11150): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (11150): Tagging socket 85 with tag 1000040100000000{268436481,0} uid 10014, pid: 11150, getuid(): 10014
,I/System.out(11315): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 10014
,I/System.out(11315): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/GetConfigurationSnapshotOperation(11150): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(11150): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory(11150): Using platform SSLCertificateSocketFactory
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 252, CUR = 58
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged,
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 15,
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 251, CUR = 58,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 251, CUR = 57
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 330s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 57
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 16
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 56
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 54
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 54
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 17
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 249, CUR = 55
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 249, CUR = 53
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 390s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 248, CUR = 50
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 18
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 248, CUR = 48
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 247, CUR = 50
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 247, CUR = 50
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,E/Watchdog( 3522): !@Sync 19
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 247, CUR = 50
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 246, CUR = 49
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 246, CUR = 48
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 455s ago
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3522): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 246, CUR = 48
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 48
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 46
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 21
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 47
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 46
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 44,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 22
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 44
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 525s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 44
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 23,
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 42
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 24
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 40
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 600s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 25
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 40
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 26
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 39
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 27
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3522): [PWL] Off : 680s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 28
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 29
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 34
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 33
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/LightsService( 3522): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3522): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/GCM     (11150): Heartbeat request when already waiting for ack
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3522): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3522): unregisterListener ::   
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 14267
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 32
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 31
,I/PowerManagerService( 3522): [PWL] Off : 765s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 32
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 32
,V/AlarmManager( 3522): waitForAlarm result :8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 31
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 32
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 30
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 31
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 32
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 30
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 30
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 30
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 33
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 29
,I/PowerManagerService( 3522): [PWL] Off : 855s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 34
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 35
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 29
,E/Watchdog( 3522): !@Sync 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 950s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 30
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 28
,E/Watchdog( 3522): !@Sync 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 27
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 27
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 233, CUR = 27
,E/Watchdog( 3522): !@Sync 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 233, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged,
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 233, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 232, CUR = 24
,E/Watchdog( 3522): !@Sync 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 232, CUR = 26
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 232, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 231, CUR = 25
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3522): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3522): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3522): Updating Usage Statistics in DB @ 1449627750148
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3522): Done Updating Usage Statistics in DB @ 1449627750244
,E/Watchdog( 3522): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 231, CUR = 24
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 231, CUR = 23,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 23
,E/Watchdog( 3522): !@Sync 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 23,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 22
,E/Watchdog( 3522): !@Sync 42
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 23
,E/Watchdog( 3522): !@Sync 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 22
,I/PowerManagerService( 3522): [PWL] Off : 1155s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 22
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 22
,E/Watchdog( 3522): !@Sync 44
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20,
,E/Watchdog( 3522): !@Sync 45
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,E/Watchdog( 3522): !@Sync 46
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,I/PowerManagerService( 3522): [PWL] Off : 1265s ago
,E/Watchdog( 3522): !@Sync 47
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,E/Watchdog( 3522): !@Sync 48
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18,
,E/Watchdog( 3522): !@Sync 49
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 20
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3522): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,I/art     ( 3522): Background sticky concurrent mark sweep GC freed 93885(9MB) AllocSpace objects, 378(5MB) LOS objects, 13% free, 49MB/57MB, paused 3.267ms total 119.504ms
,I/PowerManagerService( 3522): [PWL] Off : 1380s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,E/Watchdog( 3522): !@Sync 51
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 52
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged,
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 53
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 54
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 55
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 56
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 57
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 58
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1625s ago
,E/Watchdog( 3522): !@Sync 59
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 14777
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox,
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3522): waitForAlarm result :8
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 3522): waitForAlarm result :4
,I/ProcessStatsService( 3522): Prepared write state in 31ms
,D/LightsService( 3522): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3522): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,V/NetworkStats( 3522): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,V/NetworkStats( 3522): performPollLocked() took 24ms
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,I/EventLogService(11315): Aggregate from 1449626417582 (log), 1449626417582 (data)
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3522): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3522): unregisterListener ::   
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/Watchdog( 3522): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,E/Watchdog( 3522): !@Sync 61
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 62
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 63
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,I/PowerManagerService( 3522): [PWL] Off : 1755s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3522): !@Sync 64
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3522): !@Sync 65
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 66
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 67
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1890s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 68
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 69
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms)
```
