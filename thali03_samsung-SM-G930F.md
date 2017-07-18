#### Test 13058906542a01a0_thali03_samsung-SM-G930F Logs


```
--------- beginning of system
,07-18 08:07:50.894  3153  3615 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-18 08:07:51.434  3497  6358 D SSRM:n  : SIOP:: AP = 260, PST = 273 (W:10), CP = 220, CUR = 150, LCD = 57
--------- beginning of main
07-18 08:07:51.754 10031 10031 I FIPS_bssl: FIPS approved mode (1) | 10031 | app_process
07-18 08:07:51.764 10031 10031 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-18 08:07:51.774 10031 10031 D AndroidRuntime: CheckJNI is OFF
07-18 08:07:51.774 10031 10031 D AndroidRuntime: readGMSProperty: start
07-18 08:07:51.774 10031 10031 D AndroidRuntime: readGMSProperty: already setted!!
07-18 08:07:51.774 10031 10031 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-18 08:07:51.774 10031 10031 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-18 08:07:51.774 10031 10031 D AndroidRuntime: readGMSProperty: end
07-18 08:07:51.774 10031 10031 D AndroidRuntime: addProductProperty: start
07-18 08:07:51.794 10031 10031 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-18 08:07:51.824 10031 10031 I Radio-JNI: register_android_hardware_Radio DONE
07-18 08:07:51.824 10031 10031 E AffinityControl: AffinityControl: registerfunction enter
07-18 08:07:51.834 10031 10031 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-18 08:07:51.864  3497  4262 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-18 08:07:51.864  3497  4262 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-2/base.apk / 1.0 running in null rsrc of package com.example.hello
07-18 08:07:51.864  3497  4262 D ResourcesManager: For user 0 new overlays fetched Null
07-18 08:07:51.864  3497  4262 D GameManagerService: identifyGamePackage. com.example.hello
07-18 08:07:51.864  3497  4262 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.example.hello)
07-18 08:07:51.864  3497  4262 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3497  pkgName : ACTIVITY_RESUME_BOOSTER@3
07-18 08:07:51.874  3497  4262 D ActivityManager: mDVFSHelper.acquire()
07-18 08:07:51.874  3497  4262 V WindowManager: addAppToken: AppWindowToken{d0f5ebbbe token=Token{37d2279 ActivityRecord{2ec5340 u0 com.example.hello/.MainActivity t4}}} to stack=2 task=4 at 0
07-18 08:07:51.874  3497  3601 I InjectionManager: Inside getClassLibPath caller 
07-18 08:07:51.884  3497  3601 D SecWifiDisplayUtil: Metadata value : SecSettings2
07-18 08:07:51.884  3497  3601 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2e48496 V.E...... R.....ID 0,0-0,0}
07-18 08:07:51.884  3497  3601 D ISSUE_DEBUG: InputChannelName : e44b404 Starting com.example.hello
07-18 08:07:51.884 10040 10040 E Zygote  : v2
07-18 08:07:51.884 10040 10040 I libpersona: KNOX_SDCARD checking this for 10172
07-18 08:07:51.884 10040 10040 I libpersona: KNOX_SDCARD not a persona
07-18 08:07:51.884 10040 10040 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
07-18 08:07:51.884 10040 10040 E Zygote  : accessInfo : 0
07-18 08:07:51.884 10040 10040 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.example.hello 
07-18 08:07:51.884  3497  4262 I ActivityManager: Start proc 10040:com.example.hello/u0a172 for activity com.example.hello/.MainActivity
07-18 08:07:51.894  3497  4262 D InputDispatcher: Focused application set to: xxxx
07-18 08:07:51.894  3497  3851 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
07-18 08:07:51.894 10031 10031 D AndroidRuntime: Shutting down VM
07-18 08:07:51.894  3006  3006 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, iello
07-18 08:07:51.904 10040 10040 D TimaKeyStoreProvider: TimaSignature is unavailable
07-18 08:07:51.904 10040 10040 D ActivityThread: Added TimaKeyStore provider
07-18 08:07:51.914  6477  6477 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 08:07:51.914  6477  6477 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 08:07:51.914  3497  3601 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-18 08:07:51.914  3497  3978 D ActivityManager:  Launching com.example.hello, updated priority
07-18 08:07:51.914  4249  4249 V ActivityThread: updateVisibility : ActivityRecord{649952d token=android.os.BinderProxy@535e42b {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
07-18 08:07:51.924  3497  3497 D GameManagerService: NotifyRunnable. pkg: com.example.hello, type: 4, isMinimized: false, isTunableApp: false
07-18 08:07:51.924  3497  3580 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.example.hello
07-18 08:07:51.924  6477  6477 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 08:07:51.924  6477  6477 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-18 08:07:51.924  6477  6477 V ActivityThread: updateVisibility : ActivityRecord{121e03e token=android.os.BinderProxy@d78a370 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-18 08:07:51.934  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7fa9880e78
07-18 08:07:51.934  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7fa9880e78
07-18 08:07:51.944  4249  4249 D Launcher: onTrimMemory. Level: 20
07-18 08:07:51.944  3497  3601 V WindowStateAnimator: Finishing drawing window Window{e44b404 u0 d0 Starting com.example.hello}: mDrawState=DRAW_PENDING
07-18 08:07:51.964  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fe3804698
,07-18 08:07:52.224  3497  3978 I WindowManager: Screenshot max retries 4 of Token{37d2279 ActivityRecord{2ec5340 u0 com.example.hello/.MainActivity t4}} appWin=Window{e44b404 u0 d0 Starting com.example.hello} drawState=2
,07-18 08:07:52.224  3497  3580 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
07-18 08:07:52.224  3497  3580 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
07-18 08:07:52.224  3497  3580 E MARsPolicyManager: getPackageInfo package com.thaliproject.thalitest not installed!
,07-18 08:07:52.224  3497  3851 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
,07-18 08:07:52.224  3497  6358 D GameManagerService: identifyGamePackage. com.example.hello
07-18 08:07:52.224  3497  6358 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 08:07:52.234 10040 10040 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-2/base.apk / 1.0 running in com.example.hello rsrc of package com.example.hello
,07-18 08:07:52.244  3497  4409 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-18 08:07:52.244  3006  3015 I SurfaceFlinger: id=10 Removed MauncherAct (6/12)
07-18 08:07:52.244 10040 10040 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
07-18 08:07:52.244  3006  3017 I SurfaceFlinger: id=15 Removed VSBConnecti (6/11)
07-18 08:07:52.244  3006  4291 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
07-18 08:07:52.244  3006  3017 I SurfaceFlinger: id=15 Removed VSBConnecti (-2/11)
,07-18 08:07:52.244 10040 10040 D ResourcesManager: For user 0 new overlays fetched Null
,07-18 08:07:52.244  3497  6358 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-18 08:07:52.244 10040 10040 I InjectionManager: Inside getClassLibPath caller 
,07-18 08:07:52.244  3497  6358 D GameManagerService: identifyGamePackage. com.example.hello
07-18 08:07:52.244  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe38047b8
,07-18 08:07:52.244  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe38047b8
,07-18 08:07:52.244 10040 10040 W System  : ClassLoader referenced unknown path: /data/app/com.example.hello-2/lib/arm64
,07-18 08:07:52.254 10040 10040 D InjectionManager: InjectionManager
07-18 08:07:52.254 10040 10040 D InjectionManager: fillFeatureStoreMap com.example.hello
07-18 08:07:52.254 10040 10040 I InjectionManager: Constructor com.example.hello, Feature store :{}
07-18 08:07:52.254 10040 10040 I InjectionManager: featureStore :{}
07-18 08:07:52.254  3497  6358 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-18 08:07:52.254  3006  3017 I SurfaceFlinger: id=14 Removed VSBConnecti (6/10)
07-18 08:07:52.254  3006  4291 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/10)
07-18 08:07:52.254  3497  6358 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 08:07:52.254  3497  6358 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 08:07:52.254  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7fa9880e78
,07-18 08:07:52.254  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7fa9880e78
07-18 08:07:52.254 10040 10040 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-2/base.apk / 1.0 running in com.example.hello rsrc of package com.example.hello
,07-18 08:07:52.254 10040 10040 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,07-18 08:07:52.254 10040 10040 D RelationGraph: garbageCollect()
,07-18 08:07:52.264 10040 10040 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-2/base.apk / 1.0 running in com.example.hello rsrc of package com.example.hello
,07-18 08:07:52.264  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe38047b8
,07-18 08:07:52.264 10040 10040 I CordovaLog: Changing log level to DEBUG(3)
,07-18 08:07:52.264 10040 10040 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-18 08:07:52.264 10040 10040 D CordovaActivity: CordovaActivity.onCreate()
,07-18 08:07:52.274 10040 10040 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
,07-18 08:07:52.294 10040 10040 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.example.hello rsrc of package com.google.android.webview
,07-18 08:07:52.294 10040 10040 D ResourcesManager: For user 0 new overlays fetched Null
,07-18 08:07:52.294 10040 10040 I InjectionManager: Inside getClassLibPath caller 
,07-18 08:07:52.294 10040 10040 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm64
,07-18 08:07:52.304 10040 10040 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 7808-7810)
,07-18 08:07:52.304 10040 10040 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,07-18 08:07:52.304 10040 10040 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {79ef63b}
07-18 08:07:52.304 10040 10040 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,07-18 08:07:52.314 10040 10056 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.example.hello/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-18 08:07:52.324 10040 10040 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,07-18 08:07:52.334 10040 10040 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-18 08:07:52.384 10040 10040 D libEGL  : eglInitialize EGLDisplay = 0x7feae3a1b8
,07-18 08:07:52.414  3497  4560 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10172
,07-18 08:07:52.414  3497  4560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
07-18 08:07:52.414 10040 10079 W cr_media: Requires BLUETOOTH permission
,07-18 08:07:52.454 10040 10040 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-18 08:07:52.454 10040 10040 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-18 08:07:52.454 10040 10040 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-18 08:07:52.464 10040 10040 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-18 08:07:52.464 10040 10040 D PluginManager: init()
,07-18 08:07:52.474 10040 10040 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-18 08:07:52.474  3497  3876 D MdnieScenarioControlService:  packageName : com.example.hello    className : com.example.hello.MainActivity
07-18 08:07:52.484 10040 10040 I cr_Ime  : ImeThread is not enabled.
07-18 08:07:52.484 10040 10040 D Activity: performCreate Call Injection manager
07-18 08:07:52.484 10040 10040 D CordovaActivity: Started the activity.
07-18 08:07:52.484 10040 10040 I InjectionManager: dispatchOnViewCreated > Target : com.example.hello.MainActivity isFragment :false
07-18 08:07:52.484 10040 10040 D CordovaActivity: Resumed the activity.
07-18 08:07:52.484 10040 10040 D SecWifiDisplayUtil: Metadata value : SecSettings2
07-18 08:07:52.484 10040 10040 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{76ba02a I.E...... R.....ID 0,0-0,0}
07-18 08:07:52.494 10040 10089 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-18 08:07:52.494  3497  4408 D ISSUE_DEBUG: InputChannelName : 98ffdff com.example.hello/com.example.hello.MainActivity
07-18 08:07:52.494  3497  4151 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-18 08:07:52.494  3497  4151 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-18 08:07:52.494  3497  3497 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-18 08:07:52.494 10040 10040 D CordovaActivity: Paused the activity.
07-18 08:07:52.494  3497  3497 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-18 08:07:52.504 10040 10056 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.example.hello/shared_prefs/com.example.hello_preferences.xml.bak
,07-18 08:07:52.514 10040 10040 D SecWifiDisplayUtil: Metadata value : SecSettings2
,07-18 08:07:52.514  3006  3006 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,07-18 08:07:52.534 10040 10089 D libEGL  : eglInitialize EGLDisplay = 0x7f7dd40178
07-18 08:07:52.534 10040 10089 I OpenGLRenderer: Initialized EGL, version 1.4
,07-18 08:07:52.534 10040 10089 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,07-18 08:07:52.544 10040 10040 V ActivityThread: updateVisibility : ActivityRecord{5fb94f6 token=android.os.BinderProxy@7adeabe {com.example.hello/com.example.hello.MainActivity}} show : true
07-18 08:07:52.544 10040 10040 D CordovaActivity: Stopped the activity.
,07-18 08:07:52.574  3497  3876 I MdnieScenarioControlService: mGameModeLauncher : false
,07-18 08:07:52.574  3497  3876 I MdnieScenarioControlService: setUIMode
,07-18 08:07:52.624 10040 10040 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-18 08:07:52.624 10040 10093 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-18 08:07:52.624 10040 10093 D libEGL  : eglInitialize EGLDisplay = 0x7f7d6fea28
,07-18 08:07:52.634 10040 10093 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.example.hello
,07-18 08:07:52.644  3497  3978 V WindowStateAnimator: Finishing drawing window Window{98ffdff u0 d0 com.example.hello/com.example.hello.MainActivity}: mDrawState=DRAW_PENDING
07-18 08:07:52.644 10040 10040 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,07-18 08:07:52.654  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fe3804698
,07-18 08:07:52.654  3497  3848 V WindowStateAnimator: Finishing drawing window Window{98ffdff u0 d0 com.example.hello/com.example.hello.MainActivity}: mDrawState=HAS_DRAWN
07-18 08:07:52.654  3497  3601 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-18 08:07:52.654  3497  3497 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-18 08:07:52.654  3497  3601 I ActivityManager: Displayed com.example.hello/.MainActivity: +430ms (total +778ms)
07-18 08:07:52.654  3497  3601 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3497  tag : ACTIVITY_RESUME_BOOSTER@3
07-18 08:07:52.654 10040 10040 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
07-18 08:07:52.654 10040 10040 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7adeabe time:158165
07-18 08:07:52.654  3497  3601 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2ec5340 u0 com.example.hello/.MainActivity t4} time:158165
07-18 08:07:52.654  3497  3601 D ActivityManager: mDVFSHelper.release()
07-18 08:07:52.654  3497  3601 D ViewRootImpl: #3 mView = null
07-18 08:07:52.654  3497  3580 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3497  pkgName : ACTIVITY_RESUME_BOOSTER@9
07-18 08:07:52.654  3006  4461 I SurfaceFlinger: id=16 Removed iello (6/10)
07-18 08:07:52.654  3006  3015 I SurfaceFlinger: id=16 Removed iello (-2/10)
07-18 08:07:52.654  3497  3497 I KnoxTimeoutHandler: SD activityfalse
,07-18 08:07:52.664 10040 10040 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10040
,07-18 08:07:52.664  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe38047b8
,07-18 08:07:52.664 10040 10040 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-18 08:07:52.694 10040 10040 D SystemWebChromeClient: file:///android_asset/www/index.html: Line 10 : The key "target-densitydpi" is not supported.
07-18 08:07:52.694 10040 10040 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,07-18 08:07:52.704  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fe3804698
,07-18 08:07:52.714  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fe3804698
,07-18 08:07:52.744 10040 10040 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-18 08:07:52.754 10040 10081 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,07-18 08:07:52.844 10040 10040 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-18 08:07:52.954  3497  3497 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3497  tag : ACTIVITY_RESUME_BOOSTER@9
,07-18 08:07:53.224  3497  6360 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-2/base.apk / 1.0 running in null rsrc of package com.example.hello
,07-18 08:07:53.494  4017  4017 D Recents : onTaskStackChanged
,07-18 08:07:53.504  4017  4017 W ResourcesManager: getTopLevelResources: /data/app/com.example.hello-2/base.apk / 1.0 running in com.android.systemui rsrc of package com.example.hello
,07-18 08:07:53.514  4017  4017 D ResourcesManager: For user 0 new overlays fetched Null
,07-18 08:07:54.894  3497  3902 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,07-18 08:07:55.244  3497  6358 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 08:07:55.534  3497  3809 V AlarmManager: Expired Alarm result :4
,07-18 08:07:55.554  3497  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c8d4b8 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8d2ca3 4263:com.google.android.gms.persistent/u0a19}
,07-18 08:07:55.574  3497  4560 V AlarmManager:  remove PendingIntent] PendingIntent{2a2d291: PendingIntentRecord{9ab64a8 com.google.android.gms broadcastIntent}}
,07-18 08:07:55.684  4572 10100 D UdcContextInitService: registered all accounts: true
,07-18 08:07:55.794  3497  4886 V AlarmManager:  remove PendingIntent] PendingIntent{d11adf7: PendingIntentRecord{9ab64a8 com.google.android.gms broadcastIntent}}
,07-18 08:07:55.864  3153  3615 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:07:56.274  4263 10103 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-18 08:07:56.284  4263 10103 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-18 08:07:56.724  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:56.724  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-18 08:07:56.724  3153  3619 D EnterpriseController: netId is 0
07-18 08:07:56.724  3153  3619 D Netd    : getNetworkForDns: using netid 502 for uid 10019
,07-18 08:07:56.784  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:56.844  4263 10103 I qtaguid : Tagging socket 67 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:57.534  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.534  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.534  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:57.644  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.644  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.644  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:57.764  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.764  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.764  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:57.784  3497  4409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-18 08:07:57.784  3497  4409 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-18 08:07:57.784  3497  4409 D BatteryService: online:4, current avg:128, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:172
07-18 08:07:57.784  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-18 08:07:57.784  3497  3497 I MotionRecognitionService: Plugged
07-18 08:07:57.784  3497  3497 D MotionRecognitionService:   cableConnection= 1
07-18 08:07:57.784  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-18 08:07:57.784  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,07-18 08:07:57.784  3497  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-18 08:07:57.794  3935  3935 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-18 08:07:57.794  3935  3935 D KeyguardUpdateMonitor: handleBatteryUpdate
07-18 08:07:57.794  3935  3935 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-18 08:07:57.804  5064  5064 D CommonServiceConfiguration: getStringValueSetting
,07-18 08:07:57.804  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-18 08:07:57.804  5027  5411 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-18 08:07:57.814  5064  5064 D BatteryMonitor: new battery level: 100
,07-18 08:07:57.824  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 08:07:57.824  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 08:07:57.874  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.874  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.874  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:57.984  4263 10103 W Uploader: GMM_PRIMES no longer exists, so no auth token.
,07-18 08:07:57.994  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.994  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:57.994  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:58.114  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:58.114  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:58.124  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:58.244  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:58.244  4263 10103 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 08:07:58.244  4263 10103 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4263, getuid(): 10019
,07-18 08:07:58.284  3497  4121 E Watchdog: !@Sync 5 [07-18 08:07:58.285]
,07-18 08:07:58.284  3497  6358 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-18 08:07:58.424  3497  3848 V AlarmManager:  remove PendingIntent] PendingIntent{ae2610b: PendingIntentRecord{9ab64a8 com.google.android.gms broadcastIntent}}
,07-18 08:07:58.914  3497  3604 I PowerManagerService: [PWL] On : 0 (164427 ms ago)
07-18 08:07:58.914  3497  3604 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-18 08:07:59.994  3497  3809 V AlarmManager: Expired Alarm result :8
,07-18 08:08:00.004  3935  3935 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-18 08:08:00.004  3935  3935 D KeyguardUpdateMonitor: handleTimeUpdate
,07-18 08:08:00.024  3935  3935 D Clock   : received broadcast android.intent.action.TIME_TICK
,07-18 08:08:00.084  3935  3935 D DateView: received broadcast android.intent.action.TIME_TICK
,07-18 08:08:00.114  4689  4689 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,07-18 08:08:00.114  4689  4689 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,07-18 08:08:00.114  4689  4689 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,07-18 08:08:00.124  4689  4689 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,07-18 08:08:00.124  4689  4689 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0C471787A98F7DD7D3924300438F66FFD236DCC6D0A0E4472006322FA1E91BFC19871E5BC22B8A5C7C627C0DF988DD34D]}
07-18 08:08:00.124  4689  4689 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,07-18 08:08:00.224  9687  9711 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,07-18 08:08:01.454  3497  6358 D SSRM:n  : SIOP:: AP = 270, PST = 269 (W:6), CP = 222, CUR = 128, LCD = 57
,07-18 08:08:01.924  3497  3611 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-18 08:08:01.954  3497  3611 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-18 08:08:06.174  3497  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-18 08:08:07.844  3497  4560 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-18 08:08:07.844  3497  4560 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-18 08:08:07.844  3497  4560 D BatteryService: online:4, current avg:135, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:136
07-18 08:08:07.844  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-18 08:08:07.854  3497  3497 I MotionRecognitionService: Plugged
07-18 08:08:07.854  3497  3497 D MotionRecognitionService:   cableConnection= 1
07-18 08:08:07.854  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-18 08:08:07.854  3497  3497 D MotionRecognitionService: skip setTransmitPower. 
,07-18 08:08:07.864  3497  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-18 08:08:07.864  3935  3935 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-18 08:08:07.864  3935  3935 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-18 08:08:07.864  3935  3935 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-18 08:08:07.884  5064  5064 D CommonServiceConfiguration: getStringValueSetting
,07-18 08:08:07.884  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-18 08:08:07.884  5027  5411 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-18 08:08:07.894  5064  5064 D BatteryMonitor: new battery level: 100
,07-18 08:08:07.904  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 08:08:07.904  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 08:08:11.484  3497  6358 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:6), CP = 221, CUR = 135, LCD = 57
,07-18 08:08:13.454  3153  3615 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:08:15.864  3153  3615 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:08:17.904  3497  3974 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-18 08:08:17.904  3497  3974 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-18 08:08:17.904  3497  3974 D BatteryService: online:4, current avg:135, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:129
07-18 08:08:17.904  3497  3497 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-18 08:08:17.914  3497  3497 I MotionRecognitionService: Plugged
,07-18 08:08:17.914  3497  3497 D MotionRecognitionService:   cableConnection= 1
07-18 08:08:17.914  3497  3497 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-18 08:08:17.914  3497  3497 D MotionRecognitionService: skip setTransmitPower. ,
,07-18 08:08:17.924  3497  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-18 08:08:17.924  3935  3935 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-18 08:08:17.924  3935  3935 D KeyguardUpdateMonitor: handleBatteryUpdate
07-18 08:08:17.924  3935  3935 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-18 08:08:17.934  5064  5064 D CommonServiceConfiguration: getStringValueSetting
,07-18 08:08:17.944  5027  5027 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-18 08:08:17.944  5027  5411 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-18 08:08:17.954  5064  5064 D BatteryMonitor: new battery level: 100
,07-18 08:08:17.964  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 08:08:17.964  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-18 08:08:21.504  3497  6358 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:6), CP = 219, CUR = 135, LCD = 57
,07-18 08:08:26.174  3497  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-18 08:08:28.284  3497  4121 E Watchdog: !@Sync 6 [07-18 08:08:28.287]
,07-18 08:08:29.554  4341  4443 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-18 08:08:29.554  4341  4443 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-18 08:08:29.654  4341  4443 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 100ms lastUpdatedAfter : 127467ms
,07-18 08:08:31.524  3497  6358 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:6), CP = 218, CUR = 135, LCD = 57

```
