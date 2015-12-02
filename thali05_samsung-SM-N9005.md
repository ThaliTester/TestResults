#### Test 52383621d5a0cb8_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
D/SSRM:n  (  902): SIOP:: AP = 310, PST = 334, CUR = 450
D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService(  902): Plugged
--------- beginning of main
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): setPowerConnected  = true
D/BatteryService(  902): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
E/SMD     (  288): DCD ON
,D/AndroidRuntime( 7236): 
D/AndroidRuntime( 7236): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7236): CheckJNI is OFF
D/AndroidRuntime( 7236): readGMSProperty: start
D/AndroidRuntime( 7236): readGMSProperty: already setted!!
D/AndroidRuntime( 7236): readGMSProperty: end
D/AndroidRuntime( 7236): addProductProperty: start
E/AffinityControl( 7236): AffinityControl: registerfunction enter
D/AndroidRuntime( 7236): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  902): inState():  stateMachine is null !!
I/PersonaManagerService(  902): PersonaId don't exist
I/ActivityManager(  902): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  902): mDVFSHelper.acquire()
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7252): MountEmulatedStorage()
E/Zygote  ( 7252): v2
I/libpersona( 7252): KNOX_SDCARD checking this for 10262
I/libpersona( 7252): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7252 uid=10262 gids={50262, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/PointerIcon(  902): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  902): setMouseCustomIcon IconType is same.101
D/PointerIcon(  902): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  902): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 7252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/AndroidRuntime( 7236): Shutting down VM
E/SELinux ( 7252): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7252): TimaSignature is unavailable
D/ActivityThread( 7252): Added TimaKeyStore provider
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
D/ResourcesManager( 7252): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 3727): updateVisibility : ActivityRecord{257bfafd token=android.os.BinderProxy@cd6983a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7252): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7252): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7252): Loading: webviewchromium
,I/LibraryLoader( 7252): Time to load native libraries: 5 ms (timestamps 8493-8498)
I/LibraryLoader( 7252): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7252): Binding Chromium to main looper Looper (main, tid 1) {14dfea29}
,I/LibraryLoader( 7252): Expected native library version number "",actual native library version number ""
,I/chromium( 7252): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7252): Initializing chromium process, renderers=0
,W/art     ( 7252): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7252): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7252): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7252): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 7252): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7252): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7252): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7252): Local Branch: mybranch5813579
I/Adreno-EGL( 7252): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7252): Local Patches: NONE
I/Adreno-EGL( 7252): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/ActivityManager(  902): Activity pause timeout for ActivityRecord{86882f1 u0 com.test.thalitest/.MainActivity t4}
,W/chromium( 7252): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7252): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7252): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7252): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7252): CordovaWebView is running on device made by: samsung
,W/art     ( 7252): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7252): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7252): performCreate Call secproduct feature valuefalse
D/Activity( 7252): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7252): Render dirty regions requested: true
,D/Atlas   ( 7252): Validating map...
,D/ActivityManager(  902): post active user change for 0
D/KnoxTimeoutHandler(  902): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  902): handleActiveUserChange for user 0
,V/ActivityThread( 7252): updateVisibility : ActivityRecord{3043925e token=android.os.BinderProxy@115160e0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  902): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  902): setMouseCustomIcon IconType is same.101
D/PointerIcon(  902): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  902): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7252): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7252): HWUI protection enabled for context ,  &this =0xafc76038 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7252): Enabling debug mode 0
,D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  902): mDVFSHelper.release()
,I/Timeline(  902): Timeline: Activity_windows_visible id: ActivityRecord{86882f1 u0 com.test.thalitest/.MainActivity t4} time:169091
,W/IInputConnectionWrapper( 7252): showStatusIcon on inactive InputConnection
,I/Timeline( 7252): Timeline: Activity_idle id: android.os.BinderProxy@115160e0 time:169101
,I/chromium( 7252): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7252): 
,D/JsMessageQueue( 7252): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7252): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357819520
,D/JX-Cordova( 7252): jxcore cordova android initializing
,E/SMD     (  288): DCD ON
,W/jxcore-log( 7252): Initializing JXcore engine
W/jxcore-log( 7252): JXcore engine is ready
W/jxcore-log( 7252): Starting JXcore engine
E/auditd  ( 1884): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  902): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  902): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
E/Zygote  ( 7333): MountEmulatedStorage()
I/libpersona( 7333): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7333): v2
I/libpersona( 7333): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7333 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7333): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  334): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 3.060ms total 26.332ms
I/art     (  334): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 9.652ms
I/art     (  334): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 264us total 9.612ms
D/TimaKeyStoreProvider( 7333): TimaSignature is unavailable
D/ActivityThread( 7333): Added TimaKeyStore provider
D/ResourcesManager( 7333): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/SecurityLogAgent( 7333):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
D/SecurityLogAgent( 7333):  SeDenialReceiver : File path = null
I/ActivityManager(  902): Killing 5909:com.google.android.talk/u0a131 (adj 15): bgCount ##41
W/jxcore-log( 7252): Platform android
W/jxcore-log( 7252): 
W/jxcore-log( 7252): Process ARCH arm
W/jxcore-log( 7252): 
,I/jxcore-log( 7252): JXcore Cordova bridge is ready!
I/jxcore-log( 7252): ,
W/jxcore-log( 7252): JXcore engine is started
,E/jxcore  ( 7252): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 7252): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 7252): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  902): Killing 6311:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ScreenOrientationListener( 7252): Removing an inexistent observer!
,I/SurfaceFlinger(  254): id=15 Removed NainActivit (5/8)
,I/SurfaceFlinger(  254): id=15 Removed NainActivit (-2/8)
,D/PointerIcon(  902): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  902): setMouseCustomIcon IconType is same.101
D/PointerIcon(  902): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  902): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  902): mDVFSHelper.acquire()
,E/ViewRootImpl( 7252): sendUserActionEvent() mView == null
,I/DBG_DM  ( 3727): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3727): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 13
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 3727): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): There is/are notification(s) 
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3727): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3727): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3727): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3727): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  902): post active user change for 0
D/KnoxTimeoutHandler(  902): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  902): handleActiveUserChange for user 0
I/DBG_DM  ( 3727): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),2 flag=404, YUIInstallC
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  902): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  902): setMouseCustomIcon IconType is same.101
D/PointerIcon(  902): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  902): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 3727): updateVisibility : ActivityRecord{257bfafd token=android.os.BinderProxy@cd6983a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7252): showStatusIcon on inactive InputConnection
,I/Timeline( 3727): Timeline: Activity_idle id: android.os.BinderProxy@cd6983a time:172143
,W/ActivityManager(  902): mDVFSHelper.release()
I/Timeline(  902): Timeline: Activity_windows_visible id: ActivityRecord{16a45cc1 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:172162
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/TaskPersister(  902): removeObsoleteFile: deleting file=2_task.xml
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 320, PST = 331, CUR = 450
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/PackageManager(  902): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 75s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 310, PST = 323, CUR = 450
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 6
,I/ClearcutLoggerApiImpl( 1900): disconnect managed GoogleApiClient
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 317, CUR = 450
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService(  902): [PWL] Off : 105s ago
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 310, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/Watchdog(  902): !@Sync 7
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 306, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 140s ago
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 8
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 304, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 303, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 300, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 9
,I/PowerManagerService(  902): [PWL] Off : 180s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 297, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  902): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  902): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  902): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  902): initializing...
,I/TLC_TIMA_PKM_initialize(  902): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  902): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  902): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  902): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  902): aligned max_sendmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  902): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  902): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  902): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  902): App is not loaded in QSEE
,D/QSEECOMAPI: (  902): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  902): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  902): Trustlet response is completed
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  902): !@Sync 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 300, PST = 296, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 225s ago
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  902): waitForAlarm result :4
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): stay LED for fully charged
,I/ActivityManager(  902): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7384 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,E/Zygote  ( 7384): MountEmulatedStorage()
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,E/Zygote  ( 7384): v2
I/libpersona( 7384): KNOX_SDCARD checking this for 10096
I/libpersona( 7384): KNOX_SDCARD not a persona
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,I/SELinux ( 7384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7384): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7384): TimaSignature is unavailable
,D/ActivityThread( 7384): Added TimaKeyStore provider
,D/ResourcesManager( 7384): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  902): Killing 6334:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,V/AlarmManager(  902): waitForAlarm result :8
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  902): !@Sync 11
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 293, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/Watchdog(  902): !@Sync 12
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 275s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 291, CUR = 450
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  902): !@Sync 13
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,E/SMD     (  288): DCD ON
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  902): !@Sync 14
,I/PowerManagerService(  902): [PWL] Off : 330s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  902): !@Sync 15
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/bootchecker(  337): bootchecker wake up!!
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  902): !@Sync 16
,I/PowerManagerService(  902): [PWL] Off : 390s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 17
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  349): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  349): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 18
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,I/Atfwd_Sendcmd(  349): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  349): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 455s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,I/Atfwd_Daemon(  349): Stop the daemon....
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 19
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): Plugged
E/SMD     (  288): DCD ON
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  902): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  902): TimaServiceHandler.handleMessage what =1
,D/TimaService(  902): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  902): !@Sync 20
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 525s ago
,E/SMD     (  288): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager(  902): Killing 6390:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 21
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 22
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 23
,I/PowerManagerService(  902): [PWL] Off : 600s ago
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 24
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 25
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 680s ago
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 26
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 27
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 28
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  902): [PWL] Off : 765s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 29
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/TimaService(  902): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  902): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  902): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  902): !@Sync 30
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/LightsService(  902): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  902): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SensorManager(  902): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  902): [SvcLED]  onSensorChanged::light value = 47
E/LightSensor(  902): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  902): unregisterListener ::   
D/LightsService(  902): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 31
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  902): [PWL] Off : 855s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 32
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): stay LED for fully charged
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 33
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 34
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 950s ago
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 35
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 36
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 37
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 38
,I/PowerManagerService(  902): [PWL] Off : 1050s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 39
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  902): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  902): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  902): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  902): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  902): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  902): Updating Usage Statistics in DB @ 1449057570774
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
,W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
,W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
,W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
,W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
,W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
,W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
,W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  902): ::getAppControlDB: Exception to create DB
W/System.err(  902): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  902): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  902): Done Updating Usage Statistics in DB @ 1449057570966
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  902): !@Sync 40
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 41
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 1155s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 42
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 43
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 44
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 45
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 1265s ago
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryService(  902): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 46
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 47
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 48
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 49
,I/PowerManagerService(  902): [PWL] Off : 1380s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/TimaService(  902): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  902): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  902): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  902): !@Sync 50
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): stay LED for fully charged
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/LightsService(  902): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  902): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  902): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  902): [SvcLED]  onSensorChanged::light value = 47
,E/LightSensor(  902): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  902): unregisterListener ::   
,D/LightsService(  902): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 51
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 52
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  902): !@Sync 53
,I/PowerManagerService(  902): [PWL] Off : 1500s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  902): !@Sync 54
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  902): !@Sync 55
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  902): !@Sync 56
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  902): !@Sync 57
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  902): [PWL] Off : 1625s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  902): !@Sync 58
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  902): !@Sync 59
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/NetworkStatsFactory(  902): UpdateStatsForKnox
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/TimaService(  902): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  902): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  902): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  902): !@Sync 60
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 61
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 1755s ago
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  902): stay LED for fully charged
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 62
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  902): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,I/ActivityManager(  902): Killing 5162:com.sec.spp.push/u0a43 (adj 11): empty for 1800s
,V/AlarmManager(  902): waitForAlarm result :4
,I/ActivityManager(  902): Killing 6835:com.policydm/1000 (adj 11): empty for 1800s
,I/ActivityManager(  902): Killing 5967:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1800s
,I/ActivityManager(  902): Killing 6288:com.samsung.android.app.galaxyfinder/u0a39 (adj 13): empty for 1800s
,I/ActivityManager(  902): Killing 6660:com.android.defcontainer/u0a7 (adj 13): empty for 1800s
,I/ActivityManager(  902): Killing 6801:com.sec.pcw.device/1000 (adj 13): empty for 1800s
,I/ActivityManager(  902): Killing 6243:sstream.app/u0a25 (adj 13): empty for 1800s
,I/ActivityManager(  902): Killing 6783:com.samsung.groupcast/u0a20 (adj 13): empty for 1800s
,I/ActivityManager(  902): Killing 6765:com.google.android.partnersetup/u0a19 (adj 13): empty for 1800s
,I/ActivityManager(  902): Killing 6677:com.google.android.gms:car/u0a15 (adj 13): empty for 1809s
,I/ActivityManager(  902): Killing 5837:com.google.android.gm/u0a128 (adj 13): empty for 1834s
,E/SMD     (  288): DCD ON
,I/ActivityManager(  902): Killing 6498:flipboard.app/u0a125 (adj 13): empty for 1834s
,I/ActivityManager(  902): Killing 5727:com.sec.android.app.myfiles/u0a56 (adj 13): empty for 1834s
,I/ActivityManager(  902): Killing 5654:com.sec.android.app.music:service/u0a49 (adj 15): empty for 1834s
,I/ActivityManager(  902): Killing 6120:com.android.providers.calendar/u0a51 (adj 15): empty for 1834s
,I/ActivityManager(  902): Killing 4826:com.android.calendar/u0a172 (adj 15): empty for 1834s
,I/ActivityManager(  902): Killing 5517:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): empty for 1834s
,I/ActivityManager(  902): Killing 5873:com.sec.providers.settingsearch/u0a191 (adj 15): empty for 1834s
,I/ActivityManager(  902): Killing 6354:com.sec.chaton/u0a102 (adj 11): empty for 1800s
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,I/ActivityManager(  902): Killing 5893:com.samsung.android.app.assistantmenu/1000 (adj 11): empty for 1800s
,I/ActivityManager(  902): Killing 6906:com.sec.android.app.soundalive/u0a64 (adj 11): empty for 1800s
,I/ActivityManager(  902): Killing 5749:com.android.mms/u0a55 (adj 11): empty for 1800s
,I/ActivityManager(  902): Killing 5670:com.sec.android.gallery3d/u0a53 (adj 11): empty for 1800s
,I/ActivityManager(  902): Killing 6885:com.osp.app.signin/u0a50 (adj 11): empty for 1800s
,I/ActivityManager(  902): Killing 6855:com.samsung.android.sdk.samsunglink/u0a48 (adj 11): empty for 1800s
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6835/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10040/pid_5967/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10039/pid_6288/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10007/pid_6660/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6801/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10025/pid_6243/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10020/pid_6783/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10019/pid_6765/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10015/pid_6677/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10128/pid_5837/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10125/pid_6498/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10056/pid_5727/cgroup.procs: No such file or directory
,D/CountryDetector(  902): No listener is left
,W/libprocessgroup(  902): failed to open /acct/uid_10049/pid_5654/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10051/pid_6120/cgroup.procs: No such file or directory
,I/ProcessStatsService(  902): Prepared write state in 7ms
,W/libprocessgroup(  902): failed to open /acct/uid_10043/pid_5162/cgroup.procs: No such file or directory
,I/ProcessStatsService(  902): Prepared write state in 7ms
,W/libprocessgroup(  902): failed to open /acct/uid_10172/pid_4826/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10171/pid_5517/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10191/pid_5873/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10102/pid_6354/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_5893/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10064/pid_6906/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10055/pid_5749/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10053/pid_5670/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10050/pid_6885/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10048/pid_6855/cgroup.procs: No such file or directory
,I/ProcessStatsService(  902): Prepared write state in 10ms
,I/ProcessStatsService(  902): Prepared write state in 8ms
,I/ProcessStatsService(  902): Prepared write state in 25ms
,I/ProcessStatsService(  902): Prepared write state in 9ms
,I/ProcessStatsService(  902): Prepared write state in 6ms
,I/ProcessStatsService(  902): Prepared write state in 9ms
,I/ProcessStatsService(  902): Prepared write state in 9ms
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService(  902): Prepared write state in 9ms
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2184): Aggregate from 1449055870444 (log), 1449055870444 (data)
,I/ProcessStatsService(  902): Prepared write state in 7ms
,I/ProcessStatsService(  902): Prepared write state in 7ms
,I/ProcessStatsService(  902): Prepared write state in 7ms
,I/ProcessStatsService(  902): Prepared write state in 9ms
,I/ProcessStatsService(  902): Prepared write state in 9ms
,I/ProcessStatsService(  902): Prepared write state in 9ms
,V/AlarmManager(  902): waitForAlarm result :8
,I/ProcessStatsService(  902): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-48.bin
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ActivityManager(  902): Killing 6997:com.samsung.helphub/1000 (adj 13): empty for 1804s
,I/ActivityManager(  902): Killing 6982:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): empty for 1804s
,I/ActivityManager(  902): Killing 6962:com.samsung.android.app.filterinstaller/1000 (adj 13): empty for 1804s
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6997/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10126/pid_6982/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6962/cgroup.procs: No such file or directory
,I/ActivityManager(  902): Killing 6375:com.sec.android.app.controlpanel/u0a134 (adj 13): empty for 1804s
,W/libprocessgroup(  902): failed to open /acct/uid_10134/pid_6375/cgroup.procs: No such file or directory
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager(  902): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 63
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService(  902): stay LED for fully charged
,E/SMD     (  288): DCD ON,
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3147): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  902): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 64
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  902): stay LED for fully charged
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  902): !@Sync 65
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  902): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7552): 
D/AndroidRuntime( 7552): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7552): CheckJNI is OFF
D/AndroidRuntime( 7552): readGMSProperty: start
D/AndroidRuntime( 7552): readGMSProperty: already setted!!
D/AndroidRuntime( 7552): readGMSProperty: end
D/AndroidRuntime( 7552): addProductProperty: start
E/AffinityControl( 7552): AffinityControl: registerfunction enter
D/AndroidRuntime( 7552): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  902): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  902): START PACKAGE DELETE: observer{987005652}
D/PackageManager(  902): pkg{<packageName>}
D/PackageManager(  902): user{0}
D/PackageManager(  902): caller{2000}
D/PackageManager(  902): flags{3}
D/PersonaManagerService(  902): isFromApprovedUnInstaller: isApproved : true
D/PackageManager(  902): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  902): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  902): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  902): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  902): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  902): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  902): getApplicationUninstallationEnabled
D/ApplicationPolicy(  902): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  902): !@killApplicatoin: 10262, uninstall pkg
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10262 user=-1: uninstall pkg
I/ActivityManager(  902): Killing 7252:com.test.thalitest/u0a262 (adj 9): stop com.test.thalitest
W/PackageSettings(  902): Skipping PackageSetting{67f92a5 com.example.hello/10256} due to missing metadata
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10262 user=0: pkg removed
I/art     ( 1572): Explicit concurrent mark sweep GC freed 30028(1974KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 586us total 46.514ms
I/art     ( 7013): Explicit concurrent mark sweep GC freed 9053(519KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 559us total 42.347ms
W/ActivityManager(  902): Spurious death for ProcessRecord{10507c7d 7252:com.test.thalitest/u0a262}, curProc for 7252: null
I/art     ( 4567): Explicit concurrent mark sweep GC freed 36403(1993KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 523us total 37.142ms
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
W/GeofencerStateMachine( 1900): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
I/InputReader(  902): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1725): mOCRHelper is null
E/Zygote  ( 7581): MountEmulatedStorage()
E/Zygote  ( 7581): v2
I/libpersona( 7581): KNOX_SDCARD checking this for 10023
I/libpersona( 7581): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7581 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/art     (  902): Explicit concurrent mark sweep GC freed 17718(1588KB) AllocSpace objects, 15(240KB) LOS objects, 17% free, 37MB/45MB, paused 1.480ms total 131.965ms
D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/art     (  902): WaitForGcToComplete blocked for 27.544ms for cause Explicit
I/SELinux ( 7581): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7581): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7581): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/TimaKeyStoreProvider( 7581): TimaSignature is unavailable
D/ActivityThread( 7581): Added TimaKeyStore provider
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/BatteryService(  902): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  902): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  902): stay LED for fully charged
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 7581): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/RegisteredServicesCache( 1403): empty dynamic service
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.511: ( 7581): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.511: ( 7581): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449058339617
I/KLMS-2.4.511: ( 7581): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.511: ( 7581): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/SMD     (  288): DCD ON
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/RCPManagerService(  902): PackageReceiver onReceive()
I/HarmonyEASService(  902): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  902): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  902): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  902): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  902): uID is 10262
V/EnterpriseBillingPolicy(  902): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  902): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  902): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  902): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  902): getBillingProfileForVpnEngine - end - null
E/Zygote  ( 7597): MountEmulatedStorage()
E/Zygote  ( 7597): v2
I/libpersona( 7597): KNOX_SDCARD checking this for 10116
I/libpersona( 7597): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7597 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
D/TaskPersister(  902): removeObsoleteFile: deleting file=4_task.xml
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
I/art     (  902): Explicit concurrent mark sweep GC freed 9871(661KB) AllocSpace objects, 1(16KB) LOS objects, 17% free, 37MB/45MB, paused 2.353ms total 272.275ms
I/SELinux ( 7597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3147): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3147): Disconnected process message: 10
I/SELinux ( 7597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7597): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/TimaKeyStoreProvider( 7597): TimaSignature is unavailable
D/ActivityThread( 7597): Added TimaKeyStore provider
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager( 7597): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/PackageManager(  902): delete codoeFile: 
I/AASAUninstall(  902):  com.test.thalitest not target!
D/PackageManager(  902): result of delete: 1{987005652}
D/AndroidRuntime( 7552): Shutting down VM
D/EnterpriseDeviceManagerService(  902): Package has changed for user 0
D/EnterpriseDeviceManagerService(  902): Admin package name: com.google.android.gms
D/elm:14491( 7597): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/elm:14491( 7597): ELMEngine.ELMEngine( context ).
D/elm:14491( 7597): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
D/elm:14491( 7597): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Books/Books.apk
D/elm:14491( 7597): ElmAgentService : onCreate()
D/elm:14491( 7597): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7597): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7597): MDMBridge.getInstance()
D/elm:14491( 7597): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7597): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  ( 7614): MountEmulatedStorage()
E/Zygote  ( 7614): v2
I/libpersona( 7614): KNOX_SDCARD checking this for 10021
I/libpersona( 7614): KNOX_SDCARD not a persona
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ActivityManager(  902): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7614 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/SELinux ( 7614): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 7597): ElmAgentService : onDestroy().
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux ( 7614): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  902): Killing 5133:com.google.android.apps.plus/u0a155 (adj 13): empty for 1891s
E/SELinux ( 7614): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/TimaKeyStoreProvider( 7614): TimaSignature is unavailable
D/ActivityThread( 7614): Added TimaKeyStore provider
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/libprocessgroup(  902): failed to open /acct/uid_10155/pid_5133/cgroup.procs: No such file or directory
W/ResourcesManager(  902): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager( 7614): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7614): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7614): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7614): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7629): MountEmulatedStorage()
I/libpersona( 7629): KNOX_SDCARD checking this for 10025
E/Zygote  ( 7629): v2
I/libpersona( 7629): KNOX_SDCARD not a persona
I/SELinux ( 7629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  902): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7629 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  902): Killing 7031:com.samsung.android.snote:provider/u0a168 (adj 13): empty for 1891s
D/TimaKeyStoreProvider( 7629): TimaSignature is unavailable
D/ActivityThread( 7629): Added TimaKeyStore provider
D/UsbSettingsManager(  902): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  902): onPackageRemoved : com.test.thalitest
W/libprocessgroup(  902): failed to open /acct/uid_10168/pid_7031/cgroup.procs: No such file or directory
D/ResourcesManager( 7629): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
W/ResourcesManager( 7629): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/linker  ( 7629): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/MVFD_interface( 7629): <<<  caMVFace_FaceInit
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7629): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7629): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/SharedPreferencesImpl( 7629): Couldn't rename file /data/data/sstream.app/shared_prefs/shared_prefs.xml to backup file /data/data/sstream.app/shared_prefs/shared_prefs.xml.bak
I/EventHub(  902): Removing device '/dev/input/event6' due to inotify event
D/HockeyApp( 7629): Current handler class = sstream.app.util.Log$1
E/SharedPreferencesImpl( 7629): Couldn't rename file /data/data/sstream.app/shared_prefs/shared_prefs.xml to backup file /data/data/sstream.app/shared_prefs/shared_prefs.xml.bak
I/EventHub(  902): Removing device '/dev/input/event7' due to inotify event
I/EventHub(  902): Removing device '/dev/input/event8' due to inotify event
I/EventHub(  902): Removing device '/dev/input/event9' due to inotify event
E/SQLiteLog( 7629): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 7629): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 7629): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7629): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7629): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7629): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 7629): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 7629): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 7629): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 7629): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 7629): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 7629): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 7629): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 7629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7629): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7629): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 7629): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7629): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 7629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/AndroidRuntime( 7629): Shutting down VM
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/HockeyApp( 7629): Writing unhandled exception to: /data/data/sstream.app/files/2526d1b2-832d-4bfc-82e9-5727fc7eaf27.stacktrace
D/ResourcesManager( 7629): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 7629): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog( 7629): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 7629): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 7629): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7629): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7629): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7629): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7629): 	at sstream.app.provider.StoryProvider.query(StoryProvider.java:386)
E/SQLiteDatabase( 7629): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 7629): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 7629): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/SQLiteDatabase( 7629): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase( 7629): 	at sstream.app.provider.DatabaseUtil.queryConfigSetting(DatabaseUtil.java:685)
E/SQLiteDatabase( 7629): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:418)
E/SQLiteDatabase( 7629): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 7629): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
I/ActivityManager(  902): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  902): Killing 7048:com.sec.kidsplat.installer/u0a189 (adj 13): empty for 1891s
I/EventHub(  902): Removing device '/dev/input/event10' due to inotify event
E/Zygote  ( 7670): MountEmulatedStorage()
E/Zygote  ( 7670): v2
I/libpersona( 7670): KNOX_SDCARD checking this for 1000
I/libpersona( 7670): KNOX_SDCARD not a persona
E/HockeyApp( 7629): Error saving exception stacktrace!
E/HockeyApp( 7629): 
E/HockeyApp( 7629): java.io.FileNotFoundException: /data/data/sstream.app/files/2526d1b2-832d-4bfc-82e9-5727fc7eaf27.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 7629): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 7629): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 7629): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 7629): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 7629): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 7629): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 7629): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 7629): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 7629): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 7629): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 7629): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 7629): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 7629): 	... 7 more
D/HockeyApp( 7629): Writing unhandled exception to: /data/data/sstream.app/files/ce4e4691-ef8b-49e1-ba0e-8f2b4fd0b5a4.stacktrace
E/HockeyApp( 7629): Error saving exception stacktrace!
E/HockeyApp( 7629): 
E/HockeyApp( 7629): java.io.FileNotFoundException: /data/data/sstream.app/files/ce4e4691-ef8b-49e1-ba0e-8f2b4fd0b5a4.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 7629): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 7629): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 7629): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 7629): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 7629): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 7629): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 7629): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 7629): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 7629): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 7629): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 7629): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 7629): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 7629): 	... 7 more
I/EventHub(  902): Removing device '/dev/input/event11' due to inotify event
I/SELinux ( 7670): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 7670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/EventHub(  902): Removing device '/dev/input/event12' due to inotify event
D/TimaKeyStoreProvider( 7670): TimaSignature is unavailable
D/ActivityThread( 7670): Added TimaKeyStore provider
W/libprocessgroup(  902): failed to open /acct/uid_10189/pid_7048/cgroup.procs: No such file or directory
I/EventHub(  902): Removing device '/dev/input/event13' due to inotify event
D/ResourcesManager( 7670): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
W/ContextImpl( 7670): Unable to create files subdir /data/data/com.sec.pcw.device/cache
E/ActivityThread( 7670): Unable to setupGraphicsSupport due to missing cache directory
D/AndroidRuntime( 7670): Shutting down VM
E/AndroidRuntime( 7670): FATAL EXCEPTION: main
E/AndroidRuntime( 7670): Process: com.sec.pcw.device, PID: 7670
E/AndroidRuntime( 7670): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 7670): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 7670): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 7670): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 7670): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 7670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 7670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7670): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 7670): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 7670): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7670): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 7670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 7670): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 7670): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 7670): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 7670): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 7670): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5545)
E/AndroidRuntime( 7670): 	... 11 more
E/AndroidRuntime( 7670): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/PCWClientS18/PCWClientS18.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 7670): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 7670): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 7670): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 7670): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 7670): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 7670): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 7670): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 7670): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 7670): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 7670): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 7670): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7670): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7670): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 7670): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 7670): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 7670): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 7670): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 7670): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 7670): 		... 9 more
E/AndroidRuntime( 7670): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/PCWClientS18/PCWClientS18.apk'
E/AndroidRuntime( 7670): 		... 27 more
E/AndroidRuntime( 7670): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/PCWClientS18/arm/PCWClientS18.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 7670): 		... 27 more
E/AndroidRuntime( 7670): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 7670): 		... 27 more
E/AndroidRuntime( 7670): 	Suppressed: java.lang.ClassNotFoundException: com.sec.pcw.device.contentprovider.DMProvider
E/AndroidRuntime( 7670): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 7670): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 7670): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 7670): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 7670): 		... 13 more
E/AndroidRuntime( 7670): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device

```
