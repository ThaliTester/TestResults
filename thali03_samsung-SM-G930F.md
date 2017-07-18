#### Test 1305890652ce07bc_thali03_samsung-SM-G930F Logs


```
--------- beginning of system
,07-18 10:32:32.818  3492  4777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-18 10:32:32.838  3492  4777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-18 10:32:32.838  3492  4777 D BatteryService: online:4, current avg:144, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:139
07-18 10:32:32.838  3492  3492 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-18 10:32:32.838  3492  3492 I MotionRecognitionService: Plugged
07-18 10:32:32.838  3492  3492 D MotionRecognitionService:   cableConnection= 1
07-18 10:32:32.838  3492  3492 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-18 10:32:32.838  3492  3492 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
07-18 10:32:32.838  3492  3853 D WifiController: ApOrStaEnabledState  msg.what= 155652
07-18 10:32:32.838  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-18 10:32:32.838  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
07-18 10:32:32.838  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
07-18 10:32:32.848  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-18 10:32:32.858  5172  5172 D CommonServiceConfiguration: getStringValueSetting
07-18 10:32:32.858  5118  5118 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-18 10:32:32.858  5118  5464 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-18 10:32:32.868  5172  5172 D BatteryMonitor: new battery level: 100
07-18 10:32:32.888  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-18 10:32:33.278  3492  4126 E Watchdog: !@Sync 5 [07-18 10:32:33.288]
07-18 10:32:33.398  9351  9351 I FIPS_bssl: FIPS approved mode (1) | 9351 | app_process
07-18 10:32:33.408  9351  9351 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-18 10:32:33.408  9351  9351 D AndroidRuntime: CheckJNI is OFF
07-18 10:32:33.408  9351  9351 D AndroidRuntime: readGMSProperty: start
07-18 10:32:33.408  9351  9351 D AndroidRuntime: readGMSProperty: already setted!!
07-18 10:32:33.408  9351  9351 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-18 10:32:33.408  9351  9351 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-18 10:32:33.408  9351  9351 D AndroidRuntime: readGMSProperty: end
07-18 10:32:33.408  9351  9351 D AndroidRuntime: addProductProperty: start
07-18 10:32:33.428  9351  9351 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-18 10:32:33.448  9351  9351 I Radio-JNI: register_android_hardware_Radio DONE
07-18 10:32:33.448  9351  9351 E AffinityControl: AffinityControl: registerfunction enter
07-18 10:32:33.458  9351  9351 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-18 10:32:33.488  3492  3966 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-18 10:32:33.488  3492  3966 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-1/base.apk / 1.0 running in null rsrc of package com.example.hello
07-18 10:32:33.508  3492  3966 D ResourcesManager: For user 0 new overlays fetched Null
07-18 10:32:33.508  3492  3966 D GameManagerService: identifyGamePackage. com.example.hello
07-18 10:32:33.508  3492  3966 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.example.hello)
07-18 10:32:33.508  3492  3966 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3492  pkgName : ACTIVITY_RESUME_BOOSTER@3
07-18 10:32:33.508  3492  3966 D ActivityManager: mDVFSHelper.acquire()
07-18 10:32:33.508  3492  3966 V WindowManager: addAppToken: AppWindowToken{d0576e874 token=Token{f97d847 ActivityRecord{4382786 u0 com.example.hello/.MainActivity t4}}} to stack=2 task=4 at 0
07-18 10:32:33.508  3492  3600 I InjectionManager: Inside getClassLibPath caller 
07-18 10:32:33.508  3492  3600 D SecWifiDisplayUtil: Metadata value : SecSettings2
07-18 10:32:33.508  3492  3600 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e12d20c V.E...... R.....ID 0,0-0,0}
07-18 10:32:33.508  3492  3600 D ISSUE_DEBUG: InputChannelName : f87756a Starting com.example.hello
07-18 10:32:33.518  9360  9360 E Zygote  : v2
07-18 10:32:33.518  9360  9360 I libpersona: KNOX_SDCARD checking this for 10172
07-18 10:32:33.518  9360  9360 I libpersona: KNOX_SDCARD not a persona
07-18 10:32:33.518  9360  9360 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
07-18 10:32:33.518  9360  9360 E Zygote  : accessInfo : 0
07-18 10:32:33.518  3009  3009 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, iello
07-18 10:32:33.518  9360  9360 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.example.hello 
07-18 10:32:33.528  3492  3966 I ActivityManager: Start proc 9360:com.example.hello/u0a172 for activity com.example.hello/.MainActivity
07-18 10:32:33.538  9360  9360 D TimaKeyStoreProvider: TimaSignature is unavailable
07-18 10:32:33.538  9360  9360 D ActivityThread: Added TimaKeyStore provider
07-18 10:32:33.538  6184  6184 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 10:32:33.538  6184  6184 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 10:32:33.538  3492  3600 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-18 10:32:33.538  3492  3966 D InputDispatcher: Focused application set to: xxxx
07-18 10:32:33.538  9351  9351 D AndroidRuntime: Shutting down VM
07-18 10:32:33.538  3492  3847 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
07-18 10:32:33.538  3492  4577 D ActivityManager:  Launching com.example.hello, updated priority
07-18 10:32:33.548  4276  4276 V ActivityThread: updateVisibility : ActivityRecord{12d151d token=android.os.BinderProxy@83af496 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
07-18 10:32:33.548  3492  3572 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.example.hello
07-18 10:32:33.548  3492  3492 D GameManagerService: NotifyRunnable. pkg: com.example.hello, type: 4, isMinimized: false, isTunableApp: false
07-18 10:32:33.558  6184  6184 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 10:32:33.558  6184  6184 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 10:32:33.558  6184  6184 V ActivityThread: updateVisibility : ActivityRecord{58eac45 token=android.os.BinderProxy@25b41f {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-18 10:32:33.558  3009  4345 D libEGL  : eglTerminate EGLDisplay = 0x7f817fee78
07-18 10:32:33.558  3009  4345 D libEGL  : eglTerminate EGLDisplay = 0x7f817fee78
07-18 10:32:33.568  4276  4276 D Launcher: onTrimMemory. Level: 20
07-18 10:32:33.568  3492  3600 V WindowStateAnimator: Finishing drawing window Window{f87756a u0 d0 Starting com.example.hello}: mDrawState=DRAW_PENDING
07-18 10:32:33.568  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fee8a6798
07-18 10:32:33.588  3009  4643 I SurfaceFlinger: id=14 Removed VSBConnecti (8/12)
07-18 10:32:33.588  3009  3020 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/12)
07-18 10:32:33.588  3009  4643 D libEGL  : eglTerminate EGLDisplay = 0x7f8157ee78
07-18 10:32:33.588  3009  4643 D libEGL  : eglTerminate EGLDisplay = 0x7f8157ee78
07-18 10:32:33.598  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fee8a68b8
,07-18 10:32:33.858  3492  4577 I WindowManager: Screenshot max retries 4 of Token{f97d847 ActivityRecord{4382786 u0 com.example.hello/.MainActivity t4}} appWin=Window{f87756a u0 d0 Starting com.example.hello} drawState=4
,07-18 10:32:33.858  3492  3572 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
07-18 10:32:33.858  3492  3572 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
07-18 10:32:33.858  3492  3572 E MARsPolicyManager: getPackageInfo package com.thaliproject.thalitest not installed!
,07-18 10:32:33.858  3492  6079 D GameManagerService: identifyGamePackage. com.example.hello
07-18 10:32:33.858  3492  3847 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
07-18 10:32:33.858  3492  6079 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 10:32:33.858  3009  3895 I SurfaceFlinger: id=9 Removed MauncherAct (5/11)
,07-18 10:32:33.858  3009  4643 I SurfaceFlinger: id=15 Removed VSBConnecti (6/10)
07-18 10:32:33.858  3009  3895 I SurfaceFlinger: id=9 Removed MauncherAct (-2/10)
07-18 10:32:33.858  3009  3020 I SurfaceFlinger: id=15 Removed VSBConnecti (-2/10)
,07-18 10:32:33.858  9360  9360 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-1/base.apk / 1.0 running in com.example.hello rsrc of package com.example.hello
,07-18 10:32:33.868  3492  3844 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-18 10:32:33.868  9360  9360 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-18 10:32:33.868  9360  9360 D ResourcesManager: For user 0 new overlays fetched Null
,07-18 10:32:33.868  3492  6079 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-18 10:32:33.868  3492  6079 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 10:32:33.868  9360  9360 I InjectionManager: Inside getClassLibPath caller 
,07-18 10:32:33.868  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fee8a68b8
07-18 10:32:33.868  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fee8a68b8
,07-18 10:32:33.878  3492  6079 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-18 10:32:33.878  9360  9360 W System  : ClassLoader referenced unknown path: /data/app/com.example.hello-1/lib/arm64
07-18 10:32:33.878  3492  6079 D GameManagerService: identifyGamePackage. com.example.hello
07-18 10:32:33.878  3492  6079 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 10:32:33.878  9360  9360 D InjectionManager: InjectionManager
07-18 10:32:33.878  9360  9360 D InjectionManager: fillFeatureStoreMap com.example.hello
,07-18 10:32:33.878  9360  9360 I InjectionManager: Constructor com.example.hello, Feature store :{}
07-18 10:32:33.878  9360  9360 I InjectionManager: featureStore :{}
,07-18 10:32:33.878  9360  9360 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-1/base.apk / 1.0 running in com.example.hello rsrc of package com.example.hello
,07-18 10:32:33.878  9360  9360 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,07-18 10:32:33.878  9360  9360 D RelationGraph: garbageCollect()
,07-18 10:32:33.888  9360  9360 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-1/base.apk / 1.0 running in com.example.hello rsrc of package com.example.hello
,07-18 10:32:33.888  9360  9360 I CordovaLog: Changing log level to DEBUG(3)
07-18 10:32:33.888  9360  9360 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-18 10:32:33.888  9360  9360 D CordovaActivity: CordovaActivity.onCreate()
,07-18 10:32:33.888  9360  9360 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
,07-18 10:32:33.918  9360  9360 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.example.hello rsrc of package com.google.android.webview
,07-18 10:32:33.918  9360  9360 D ResourcesManager: For user 0 new overlays fetched Null
,07-18 10:32:33.918  9360  9360 I InjectionManager: Inside getClassLibPath caller 
,07-18 10:32:33.918  9360  9360 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm64
,07-18 10:32:33.948  9360  9360 I cr_LibraryLoader: Time to load native libraries: 13 ms (timestamps 4411-4424)
,07-18 10:32:33.948  9360  9360 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,07-18 10:32:33.968  9360  9360 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39f45e6}
07-18 10:32:33.968  9360  9360 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,07-18 10:32:33.968  9360  9375 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.example.hello/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-18 10:32:33.978  9360  9360 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,07-18 10:32:33.998  9360  9360 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-18 10:32:34.088  9360  9360 D libEGL  : eglInitialize EGLDisplay = 0x7fc267c208
,07-18 10:32:34.098  3492  3872 D MdnieScenarioControlService:  packageName : com.example.hello    className : com.example.hello.MainActivity
,07-18 10:32:34.128  3492  4777 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10172
07-18 10:32:34.128  3492  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-18 10:32:34.128  9360  9398 W cr_media: Requires BLUETOOTH permission
,07-18 10:32:34.168  9360  9360 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-18 10:32:34.178  9360  9360 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-18 10:32:34.178  9360  9360 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-18 10:32:34.188  9360  9360 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-18 10:32:34.188  9360  9360 D PluginManager: init()
,07-18 10:32:34.188  9360  9360 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
07-18 10:32:34.198  9360  9360 I cr_Ime  : ImeThread is not enabled.
07-18 10:32:34.208  3492  3872 I MdnieScenarioControlService: mGameModeLauncher : false
07-18 10:32:34.208  3492  3872 I MdnieScenarioControlService: setUIMode
07-18 10:32:34.208  9360  9360 D Activity: performCreate Call Injection manager
07-18 10:32:34.208  9360  9360 D CordovaActivity: Started the activity.
07-18 10:32:34.208  9360  9360 I InjectionManager: dispatchOnViewCreated > Target : com.example.hello.MainActivity isFragment :false
07-18 10:32:34.208  9360  9360 D CordovaActivity: Resumed the activity.
07-18 10:32:34.208  9360  9360 D SecWifiDisplayUtil: Metadata value : SecSettings2
07-18 10:32:34.208  9360  9360 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{feb0f21 I.E...... R.....ID 0,0-0,0}
07-18 10:32:34.218  9360  9408 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-18 10:32:34.218  3492  3844 D ISSUE_DEBUG: InputChannelName : 9ef127d com.example.hello/com.example.hello.MainActivity
07-18 10:32:34.218  3492  4777 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-18 10:32:34.218  3492  4777 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-18 10:32:34.218  3492  3492 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-18 10:32:34.218  9360  9360 D CordovaActivity: Paused the activity.
07-18 10:32:34.218  3492  3492 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-18 10:32:34.228  9360  9375 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.example.hello/shared_prefs/com.example.hello_preferences.xml.bak
,07-18 10:32:34.238  9360  9360 D SecWifiDisplayUtil: Metadata value : SecSettings2
,07-18 10:32:34.238  3009  3009 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,07-18 10:32:34.268  9360  9408 D libEGL  : eglInitialize EGLDisplay = 0x7f64e81178
07-18 10:32:34.268  9360  9408 I OpenGLRenderer: Initialized EGL, version 1.4
,07-18 10:32:34.268  9360  9408 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,07-18 10:32:34.268  9360  9360 V ActivityThread: updateVisibility : ActivityRecord{a487c5d token=android.os.BinderProxy@921f8c5 {com.example.hello/com.example.hello.MainActivity}} show : true
07-18 10:32:34.268  9360  9360 D CordovaActivity: Stopped the activity.
,07-18 10:32:34.288  3492  6079 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:6), CP = 223, CUR = 144, LCD = 57
,07-18 10:32:34.338  9360  9360 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-18 10:32:34.358  9360  9412 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-18 10:32:34.358  9360  9412 D libEGL  : eglInitialize EGLDisplay = 0x7f647bea28
,07-18 10:32:34.368  9360  9412 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.example.hello
,07-18 10:32:34.378  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fee8a6798
,07-18 10:32:34.378  3492  4443 V WindowStateAnimator: Finishing drawing window Window{9ef127d u0 d0 com.example.hello/com.example.hello.MainActivity}: mDrawState=DRAW_PENDING
,07-18 10:32:34.378  9360  9360 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,07-18 10:32:34.378  3492  3600 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-18 10:32:34.378  3492  3492 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-18 10:32:34.378  3492  3600 I ActivityManager: Displayed com.example.hello/.MainActivity: +531ms (total +878ms)
07-18 10:32:34.378  3492  3600 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3492  tag : ACTIVITY_RESUME_BOOSTER@3
,07-18 10:32:34.388  3492  3492 I KnoxTimeoutHandler: SD activityfalse
07-18 10:32:34.388  3492  3600 D ActivityManager: mDVFSHelper.release()
07-18 10:32:34.388  3492  3600 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4382786 u0 com.example.hello/.MainActivity t4} time:164860
07-18 10:32:34.388  3492  3572 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3492  pkgName : ACTIVITY_RESUME_BOOSTER@9
07-18 10:32:34.388  3492  3600 D ViewRootImpl: #3 mView = null
07-18 10:32:34.388  3009  3018 I SurfaceFlinger: id=16 Removed iello (6/10)
,07-18 10:32:34.388  3009  3020 I SurfaceFlinger: id=16 Removed iello (-2/10)
,07-18 10:32:34.388  9360  9360 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9360
,07-18 10:32:34.388  9360  9360 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
07-18 10:32:34.388  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fee8a68b8
,07-18 10:32:34.388  3492  4251 V WindowStateAnimator: Finishing drawing window Window{9ef127d u0 d0 com.example.hello/com.example.hello.MainActivity}: mDrawState=HAS_DRAWN
,07-18 10:32:34.388  9360  9360 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
07-18 10:32:34.398  9360  9360 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@921f8c5 time:164870
,07-18 10:32:34.418  9360  9360 D SystemWebChromeClient: file:///android_asset/www/index.html: Line 10 : The key "target-densitydpi" is not supported.
07-18 10:32:34.418  9360  9360 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,07-18 10:32:34.428  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fee8a6798
,07-18 10:32:34.438  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fee8a6798
,07-18 10:32:34.468  9360  9360 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-18 10:32:34.478  9360  9400 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,07-18 10:32:34.558  9360  9360 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-18 10:32:34.688  3492  3492 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3492  tag : ACTIVITY_RESUME_BOOSTER@9
,07-18 10:32:34.868  3492  6081 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-1/base.apk / 1.0 running in null rsrc of package com.example.hello
,07-18 10:32:35.228  4014  4014 D Recents : onTaskStackChanged
,07-18 10:32:35.228  4014  4014 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.example.hello
,07-18 10:32:35.228  4014  4014 D ResourcesManager: For user 0 new overlays fetched Null
,07-18 10:32:36.518  3492  3899 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,07-18 10:32:36.868  3492  6079 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 10:32:39.048  3492  6127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-18 10:32:39.918  3492  6079 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-18 10:32:39.958  3492  3603 I PowerManagerService: [PWL] On : 0 (170421 ms ago)
07-18 10:32:39.958  3492  3603 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-18 10:32:42.498  3153  3616 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 10:32:42.898  3492  4409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-18 10:32:42.898  3492  4409 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-18 10:32:42.898  3492  4409 D BatteryService: online:4, current avg:136, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:138
07-18 10:32:42.898  3492  3492 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-18 10:32:42.898  3492  3492 I MotionRecognitionService: Plugged
,07-18 10:32:42.898  3492  3492 D MotionRecognitionService:   cableConnection= 1
07-18 10:32:42.898  3492  3492 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-18 10:32:42.898  3492  3492 D MotionRecognitionService: skip setTransmitPower. 
,07-18 10:32:42.898  3492  3853 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-18 10:32:42.898  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-18 10:32:42.918  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
07-18 10:32:42.918  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-18 10:32:42.928  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 10:32:42.928  5172  5172 D CommonServiceConfiguration: getStringValueSetting
,07-18 10:32:42.928  5118  5118 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-18 10:32:42.928  5118  5464 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-18 10:32:42.928  5172  5172 D BatteryMonitor: new battery level: 100
,07-18 10:32:42.958  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 10:32:43.568  3492  3609 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-18 10:32:43.578  3492  3609 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-18 10:32:44.318  3492  6079 D SSRM:n  : SIOP:: AP = 270, PST = 265 (W:6), CP = 224, CUR = 136, LCD = 57
,07-18 10:32:47.268  3153  3616 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 10:32:52.948  3492  4204 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-18 10:32:52.948  3492  4204 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-18 10:32:52.948  3492  4204 D BatteryService: online:4, current avg:135, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:138
07-18 10:32:52.948  3492  3492 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-18 10:32:52.958  3492  3492 I MotionRecognitionService: Plugged
07-18 10:32:52.958  3492  3492 D MotionRecognitionService:   cableConnection= 1
07-18 10:32:52.958  3492  3492 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-18 10:32:52.958  3492  3492 D MotionRecognitionService: skip setTransmitPower. 
,07-18 10:32:52.968  3492  3853 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-18 10:32:52.968  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-18 10:32:52.968  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-18 10:32:52.968  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-18 10:32:52.988  5172  5172 D CommonServiceConfiguration: getStringValueSetting
,07-18 10:32:52.988  5118  5118 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-18 10:32:52.988  5118  5464 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-18 10:32:52.998  5172  5172 D BatteryMonitor: new battery level: 100
,07-18 10:32:53.008  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-18 10:32:53.008  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 10:32:54.338  3492  6079 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:6), CP = 222, CUR = 135, LCD = 57
,07-18 10:32:59.058  3492  6127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-18 10:32:59.998  3492  3807 V AlarmManager: Expired Alarm result :8
,07-18 10:32:59.998  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-18 10:33:00.008  3941  3941 D KeyguardUpdateMonitor: handleTimeUpdate
,07-18 10:33:00.018  3941  3941 D Clock   : received broadcast android.intent.action.TIME_TICK
,07-18 10:33:00.058  3941  3941 D DateView: received broadcast android.intent.action.TIME_TICK
,07-18 10:33:00.098  4727  4727 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,07-18 10:33:00.098  4727  4727 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,07-18 10:33:00.098  4727  4727 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,07-18 10:33:00.098  4727  4727 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,07-18 10:33:00.098  4727  4727 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0C471787A98F7DD7D3924300438F66FFD236DCC6D0A0E4472006322FA1E91BFC19871E5BC22B8A5C7C627C0DF988DD34D]}
,07-18 10:33:00.098  4727  4727 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,07-18 10:33:02.298  3153  3616 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 10:33:03.288  3492  4126 E Watchdog: !@Sync 6 [07-18 10:33:03.290]
,07-18 10:33:04.358  3492  6079 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:6), CP = 221, CUR = 135, LCD = 57
,07-18 10:33:04.458  4311  4424 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-18 10:33:04.458  4311  4424 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-18 10:33:04.598  4311  4424 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 143ms lastUpdatedAfter : 130392ms
,07-18 10:33:07.278  3153  3616 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found

```
