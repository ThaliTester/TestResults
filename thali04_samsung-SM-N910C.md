#### Test 5563415007e42e9_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,V/AlarmManager( 3528): waitForAlarm result :4
D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 275, CUR = 72
D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PowerManagerService( 3528): [PWL] Off : 30s ago
D/AndroidRuntime(11644): 
D/AndroidRuntime(11644): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11644): CheckJNI is OFF
D/AndroidRuntime(11644): readGMSProperty: start
D/AndroidRuntime(11644): readGMSProperty: already setted!!
D/AndroidRuntime(11644): readGMSProperty: end
D/AndroidRuntime(11644): addProductProperty: start
E/AffinityControl(11644): AffinityControl: registerfunction enter
D/AndroidRuntime(11644): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3528): inState():  stateMachine is null !!
I/PersonaManagerService( 3528): PersonaId don't exist
I/ActivityManager( 3528): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3528): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3528): mDVFSHelper.acquire()
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (11663): MountEmulatedStorage()
E/Zygote  (11663): v2
I/libpersona(11663): KNOX_SDCARD checking this for 10561
I/libpersona(11663): KNOX_SDCARD not a persona
I/SELinux (11663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11663 uid=10561 gids={50561, 9997, 3003} abi=armeabi-v7a
I/SELinux (11663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11663): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11644): Shutting down VM
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11663): TimaSignature is unavailable
D/ActivityThread(11663): Added TimaKeyStore provider
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (5/8)
D/ResourcesManager(11663): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6300): updateVisibility : ActivityRecord{3e6bcaf token=android.os.BinderProxy@21b3da10 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11663): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11663): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11663): Loading: webviewchromium
I/LibraryLoader(11663): Time to load native libraries: 15 ms (timestamps 4622-4637)
I/LibraryLoader(11663): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11663): Binding Chromium to main looper Looper (main, tid 1) {fa6ef9e}
,I/LibraryLoader(11663): Expected native library version number "",actual native library version number ""
,I/chromium(11663): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11663): Initializing chromium process, renderers=0
,W/art     (11663): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(11663): Requires BLUETOOTH permission
,W/chromium(11663): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11663): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(11663): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11663): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11663): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11663): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11663): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11663): CordovaWebView is running on device made by: samsung
,W/art     (11663): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11663): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11663): performCreate Call secproduct feature valuefalse
D/Activity(11663): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11663): Render dirty regions requested: true
,D/ActivityManager( 3528): post active user change for 0
D/KnoxTimeoutHandler( 3528): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3528): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2852): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11663): Initialized EGL, version 1.4
,I/OpenGLRenderer(11663): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279946480 
,D/OpenGLRenderer(11663): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11663): Enabling debug mode 0
,D/mali_winsys(11663): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11663): updateVisibility : ActivityRecord{a385d50 token=android.os.BinderProxy@2398acdd {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3528): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3528): mDVFSHelper.release()
I/Timeline( 3528): Timeline: Activity_windows_visible id: ActivityRecord{39358f8a u0 com.example.hello/.MainActivity t26} time:125148
,W/IInputConnectionWrapper(11663): showStatusIcon on inactive InputConnection
,I/Timeline(11663): Timeline: Activity_idle id: android.os.BinderProxy@2398acdd time:125164
,I/chromium(11663): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(11663): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium(11663): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11663): 
,D/JsMessageQueue(11663): Set native->JS mode to OnlineEventsBridgeMode
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 4,
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 268, CUR = 66
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3528): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3528): waitForAlarm result :8
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 262, CUR = 59
,I/PowerManagerService( 3528): [PWL] Off : 50s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 258, CUR = 53
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 5
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 251, CUR = 51
,V/AlarmManager( 3528): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3695): handleTimeUpdate
,D/KeyguardEffectViewController( 3695): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3695): *** don't update sliding image ***
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 75s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 247, CUR = 47
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4640): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 242, CUR = 45
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 6
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 240, CUR = 41
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3528): waitForAlarm result :8
,I/PowerManagerService( 3528): [PWL] Off : 105s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 236, CUR = 39,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3528): stay LED for fully charged
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 235, CUR = 39
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 7
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 234, CUR = 37
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 3528): [PWL] Off : 140s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 233, CUR = 36
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 232, CUR = 35,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 8
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 232, CUR = 32
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 31
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 180s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 32
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 9
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 31
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 31
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 30
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 3528): initializing...
,I/TLC_TIMA_PKM_initialize( 3528): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3528): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3528): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3528): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3528): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3528): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3528): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3528): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3528): device_id = 0x0
,I/TZ: mc_tlc_communication( 3528): tlc_open() was called
I/TZ: mc_tlc_communication( 3528): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3528): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3528): Opening the session
,I/TZ: mc_tlc_communication( 3528): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3528): Trustlet response is completed
,E/Watchdog( 3528): !@Sync 10
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 29
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3528): [PWL] Off : 225s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 28
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 29
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 11
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 229, CUR = 28
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 229, CUR = 26
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 227, CUR = 27
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 3528): [PWL] Off : 275s ago
,E/Watchdog( 3528): !@Sync 12
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 227, CUR = 27
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3695): handleTimeUpdate
,D/KeyguardEffectViewController( 3695): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3695): *** don't update sliding image ***
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 227, CUR = 25,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 226, CUR = 25
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 13
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 225, CUR = 26
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 225, CUR = 25
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 330s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 225, CUR = 26
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 14
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 224, CUR = 23
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :8
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 223, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 223, CUR = 23
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 15
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 223, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 222, CUR = 23
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 390s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 222, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/BatteryService( 3528): stay LED for fully charged
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 16
,V/AlarmManager( 3528): waitForAlarm result :4
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11979): MountEmulatedStorage()
,E/Zygote  (11979): v2
I/libpersona(11979): KNOX_SDCARD checking this for 1000
I/libpersona(11979): KNOX_SDCARD not a persona
,I/ActivityManager( 3528): Start proc com.policydm for broadcast com.policydm/.XKNOXReceiver: pid=11979 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3695): handleTimeUpdate
,I/SELinux (11979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/KeyguardEffectViewController( 3695): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3695): *** don't update sliding image ***
,I/SELinux (11979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11979): TimaSignature is unavailable
,D/ActivityThread(11979): Added TimaKeyStore provider
,D/ResourcesManager(11979): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3695): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager( 3528): Killing 10825:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,W/ActivityThread(11979): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(11979): Thread-1627(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11979): Thread-1627(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11979): Thread-1627(ApacheHTTPLog):isShipBuild true
I/System.out(11979): Thread-1627(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 502 for uid 1000
,I/System.out(11979): Thread-1627 calls detatch()
,TIME-OUT KILL (timeout was 360000ms),D/SSRM:n  ( 3528): SIOP:: AP = 220, PST = 222, CUR = 22
I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
D/SettingsProvider( 3528): name = SPD_REGISTERD
W/ContextImpl(11979): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 android.content.ContextWrapper.sendBroadcast:391 com.policydm.XDMBroadcastReceiver.sendRegisterIntent:458 com.policydm.XDMBroadcastReceiver.processEULAAgreement:447 com.policydm.XDMBroadcastReceiver.xdmExecResumeCase:367 
D/AndroidRuntime(12024): 
D/AndroidRuntime(12024): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12024): CheckJNI is OFF
D/AndroidRuntime(12024): readGMSProperty: start
D/AndroidRuntime(12024): readGMSProperty: already setted!!
D/AndroidRuntime(12024): readGMSProperty: end
D/AndroidRuntime(12024): addProductProperty: start
E/AffinityControl(12024): AffinityControl: registerfunction enter
D/AndroidRuntime(12024): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 3528): START PACKAGE DELETE: observer{820644031}
D/PackageManager( 3528): pkg{<packageName>}
D/PackageManager( 3528): user{0}
D/PackageManager( 3528): caller{2000}
D/PackageManager( 3528): flags{3}
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3528): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3528): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3528): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3528): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3528): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3528): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3528): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3528): !@killApplicatoin: 10561, uninstall pkg
I/ActivityManager( 3528): Force stopping com.example.hello appid=10561 user=-1: uninstall pkg
I/ActivityManager( 3528): Killing 11663:com.example.hello/u0a561 (adj 0): stop com.example.hello
I/ActivityManager( 3528):   Force finishing activity ActivityRecord{39358f8a u0 com.example.hello/.MainActivity t26}
W/ActivityManager( 3528): mDVFSHelper.acquire()
I/WindowState( 3528): WIN DEATH: Window{2a5e3e1 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger( 2852): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger( 2852): id=14 Removed NainActivit (-2/8)
W/PackageSettings( 3528): Skipping PackageSetting{1ceb9b95 com.test.thalitest/10560} due to missing metadata
I/SurfaceFlinger( 2852): id=14 Removed NainActivit (-2/8)
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 3528): Force stopping com.example.hello appid=10561 user=0: pkg removed
I/ActivityManager( 3528):   Force finishing activity ActivityRecord{39358f8a u0 com.example.hello/.MainActivity t26 f}
W/ActivityManager( 3528): Duplicate finish request for ActivityRecord{39358f8a u0 com.example.hello/.MainActivity t26 f}
I/art     ( 8993): Explicit concurrent mark sweep GC freed 29750(1657KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.136ms total 35.270ms
I/DBG_DM  ( 6300): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/art     ( 6764): Explicit concurrent mark sweep GC freed 6792(343KB) AllocSpace objects, 1(16KB) LOS objects, 20% free, 31MB/39MB, paused 1.863ms total 63.518ms
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
I/art     ( 4059): Explicit concurrent mark sweep GC freed 32888(2020KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.334ms total 40.387ms
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/SamsungIME( 4456): mOCRHelper is null
W/GeofencerStateMachine( 4640): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6300): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
I/InputReader( 3528): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
D/LWLocationManager(11185): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11185): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/DBG_DM  ( 6300): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
E/Zygote  (12039): MountEmulatedStorage()
E/Zygote  (12039): v2
I/libpersona(12039): KNOX_SDCARD checking this for 10063
I/libpersona(12039): KNOX_SDCARD not a persona
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/SELinux (12039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12039 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/EnterpriseDeviceManagerService( 3528): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3528): Admin package name: com.google.android.gms
W/ResourceType( 5359): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5359): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/SecContentProvider2( 3528): uri = 14 selection = getSealedState
D/SecContentProvider2( 3528): mCursor = null
D/ApplicationPolicy( 3528): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/TimaKeyStoreProvider(12039): TimaSignature is unavailable
D/ActivityThread(12039): Added TimaKeyStore provider
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/DBG_DM  ( 6300): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6300): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6300): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6300): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/DBG_DM  ( 6300): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager( 3528): post active user change for 0
D/KnoxTimeoutHandler( 3528): postActiveUserChange for user 0
I/DBG_DM  ( 6300): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/SurfaceFlinger( 2852): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Books/Books.apk
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(12039): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6300): updateVisibility : ActivityRecord{3e6bcaf token=android.os.BinderProxy@21b3da10 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/art     ( 3528): Explicit concurrent mark sweep GC freed 85995(6MB) AllocSpace objects, 137(2MB) LOS objects, 24% free, 49MB/65MB, paused 3.925ms total 190.908ms
I/art     ( 3528): WaitForGcToComplete blocked for 163.575ms for cause Explicit
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/VRSetupWizardStub/PackageIntentReceiver(12039): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12039): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12039): packagename:com.example.hello
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/Zygote  (12056): MountEmulatedStorage()
E/Zygote  (12056): v2
I/libpersona(12056): KNOX_SDCARD checking this for 10021
I/libpersona(12056): KNOX_SDCARD not a persona
D/InputMethodManagerService( 3528): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/SELinux (12056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12056 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/SELinux (12056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/SELinux (12056): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/InputMethodManagerService( 3528): Got RemoteException sending setActive(false) notification to pid 11663 uid 10561
I/ActivityManager( 3528): Killing 10677:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/Timeline( 6300): Timeline: Activity_idle id: android.os.BinderProxy@21b3da10 time:497285
W/ActivityManager( 3528): mDVFSHelper.release()
I/Timeline( 3528): Timeline: Activity_windows_visible id: ActivityRecord{cb0a76e u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:497289
D/TimaKeyStoreProvider(12056): TimaSignature is unavailable
D/ActivityThread(12056): Added TimaKeyStore provider
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(12056): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/SecContentProvider2( 3528): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3528): mCursor = null
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/RegisteredServicesCache( 3968): empty dynamic service
I/KLMS-2.4.521: (12056): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 17:04:58 GMT+01:00 2016
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.521: (12056): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (12056): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12056): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12056): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12056): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
I/KLMS-2.4.521: (12056): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (12056): KLMSIntentService(): listeningToPackageRemoved().START
I/splitIntent( 3528): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3528): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/KLMS-2.4.521: (12056): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/art     ( 3528): Explicit concurrent mark sweep GC freed 9574(462KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 1.940ms total 130.109ms
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager(11185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  (12075): MountEmulatedStorage()
E/Zygote  (12075): v2
I/libpersona(12075): KNOX_SDCARD checking this for 10106
I/libpersona(12075): KNOX_SDCARD not a persona
I/SELinux (12075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12075 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (12075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
E/SELinux (12075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (12089): MountEmulatedStorage()
E/Zygote  (12089): v2
I/libpersona(12089): KNOX_SDCARD checking this for 1000
I/libpersona(12089): KNOX_SDCARD not a persona
I/SELinux (12089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12089): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/TimaKeyStoreProvider(12075): TimaSignature is unavailable
D/ActivityThread(12075): Added TimaKeyStore provider
I/KLMS-2.4.521: (12056): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(11185): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11185): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11185): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11185): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider(12089): TimaSignature is unavailable
D/ActivityThread(12089): Added TimaKeyStore provider
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
I/KLMS-2.4.521: (12056): KLMSIntentService(): onDestroy()
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(12075): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/PackageManager( 3528): delete codoeFile: 
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
I/AASAUninstall( 3528):  com.example.hello not target!
D/PackageManager( 3528): result of delete: 1{820644031}
D/AndroidRuntime(12024): Shutting down VM
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/elm:14491(12075): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(12075): ELMEngine.ELMEngine( context ).
D/elm:14491(12075): MDMBridge.setEnterpriseBridge()
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12089): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(12089): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  (12107): MountEmulatedStorage()
E/Zygote  (12107): v2
I/libpersona(12107): KNOX_SDCARD checking this for 10052
I/libpersona(12107): KNOX_SDCARD not a persona
I/SELinux (12107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(11185): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux (12107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12107): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12107 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
D/ResourcesManager(11185): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourceType( 3528): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/elm:14491(12075): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(11185): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(11119): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11119): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11119): Clear T&P info.
D/RCPManager(12089):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3528):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3528): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/TapandpayWidget:TanpandpayAppWidgetProvider(11119): Widget is not attached.
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/elm:14491(12075): ElmAgentService : onCreate()
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/elm:14491(12075): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
W/ResourcesManager( 3528): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3528): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3528): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3528): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/elm:14491(12075): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12075): MDMBridge.getInstance()
D/elm:14491(12075): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/elm:14491(12075): MDMBridge.getAllLicenseInfoFromSDK()
D/TimaKeyStoreProvider(12107): TimaSignature is unavailable
D/ActivityThread(12107): Added TimaKeyStore provider
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-592
D/BatteryService( 3528): stay LED for fully charged
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(12107): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager(12107): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12107): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/ResourcesManager(12107): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12107): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12107): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12107): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(11185): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/Zygote  (12126): MountEmulatedStorage()
E/Zygote  (12126): v2
I/libpersona(12126): KNOX_SDCARD checking this for 10019
I/libpersona(12126): KNOX_SDCARD not a persona
I/SELinux (12126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12126 uid=10019 gids={50019, 9997} abi=armeabi-v7a
I/SELinux (12126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/SELinux (12126): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/CrashAnrDetector( 3528): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 3528): clearDefaults: com.example.hello
D/elm:14491(12075): ElmAgentService : onDestroy().
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3528): PackageReceiver onReceive()
I/HarmonyEASService( 3528): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 3528): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3528): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3528): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3528): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3528): uID is 10561
V/EnterpriseBillingPolicy( 3528): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3528): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3528): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3528): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3528): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3528): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3528): getBillingProfileForVpnEngine - end - null

```
