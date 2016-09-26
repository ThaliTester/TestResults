#### Test 8670713994ca0ed_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-26 12:24:15.604  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:15.784  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:15.964  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:16.144  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:16.314  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:16.364  9359  9359 I FIPS_bssl: FIPS approved mode (1) | 9359 | app_process
09-26 12:24:16.374  9359  9359 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 12:24:16.374  9359  9359 D AndroidRuntime: CheckJNI is OFF
09-26 12:24:16.374  9359  9359 D AndroidRuntime: readGMSProperty: start
09-26 12:24:16.374  9359  9359 D AndroidRuntime: readGMSProperty: already setted!!
09-26 12:24:16.374  9359  9359 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-26 12:24:16.374  9359  9359 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-26 12:24:16.374  9359  9359 D AndroidRuntime: readGMSProperty: end
09-26 12:24:16.374  9359  9359 D AndroidRuntime: addProductProperty: start
09-26 12:24:16.394  9359  9359 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 12:24:16.414  9359  9359 I Radio-JNI: register_android_hardware_Radio DONE
09-26 12:24:16.414  9359  9359 E AffinityControl: AffinityControl: registerfunction enter
09-26 12:24:16.424  9359  9359 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-26 12:24:16.454  3418  4302 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-26 12:24:16.454  3418  4302 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-26 12:24:16.474  3418  4302 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:16.474  3418  4302 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 12:24:16.474  3418  4302 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-26 12:24:16.484  3418  4302 D ActivityManager: mDVFSHelper.acquire()
09-26 12:24:16.484  3418  4302 V WindowManager: addAppToken: AppWindowToken{d0d270d63 token=Token{cb4cf92 ActivityRecord{6da911d u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-26 12:24:16.494  3418  3559 I InjectionManager: Inside getClassLibPath caller 
09-26 12:24:16.494  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:16.494  3418  3559 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-26 12:24:16.494  3418  3559 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f46c5db V.E...... R.....ID 0,0-0,0}
09-26 12:24:16.504  3418  3559 W WindowManager: Failed looking up window
09-26 12:24:16.504  3418  3559 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@3cd2878 does not exist
09-26 12:24:16.504  3418  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 12:24:16.504  3418  3559 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 12:24:16.504  3418  3559 D ISSUE_DEBUG: InputChannelName : 57efb51 Starting com.test.thalitest
09-26 12:24:16.504  9368  9368 E Zygote  : v2
09-26 12:24:16.504  9368  9368 I libpersona: KNOX_SDCARD checking this for 10171
09-26 12:24:16.504  9368  9368 I libpersona: KNOX_SDCARD not a persona
09-26 12:24:16.504  9368  9368 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-26 12:24:16.514  9368  9368 E Zygote  : accessInfo : 0
09-26 12:24:16.514  9368  9368 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-26 12:24:16.514  3418  4302 I ActivityManager: Start proc 9368:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-26 12:24:16.514  3006  3006 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-26 12:24:16.524  6063  6063 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 12:24:16.534  3418  3973 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3418
09-26 12:24:16.534  3418  3973 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 12:24:16.534  3418  3973 D PowerManagerService: mDisplayReady: false
09-26 12:24:16.534  3418  3973 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 12:24:16.534  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 12:24:16.534  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 12:24:16.534  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:16.544  6063  6063 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 12:24:16.534  3418  3973 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 12:24:16.534  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:16.544  3418  3571 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-26 12:24:16.544  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9a943c00
09-26 12:24:16.544  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-26 12:24:16.544  3418  4981 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3418
09-26 12:24:16.544  3418  4302 D InputDispatcher: Focused application set to: xxxx
09-26 12:24:16.544  3418  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 12:24:16.544  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 12:24:16.544  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 12:24:16.544  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 12:24:16.544  3418  3559 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-26 12:24:16.544  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:16.544  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 12:24:16.544  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:16.544  3418  3418 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 12:24:16.544  3418  3854 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-26 12:24:16.544  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 12:24:16.544  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 12:24:16.544  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:16.544  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:16.544  3418  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 12:24:16.544  3418  3563 D PowerManagerService: mDisplayReady: true
09-26 12:24:16.544  3418  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-26 12:24:16.544  3418  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-26 12:24:16.544  3418  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-26 12:24:16.554  9359  9359 D AndroidRuntime: Shutting down VM
09-26 12:24:16.584  3418  3418 I KnoxTimeoutHandler: SD activityfalse
09-26 12:24:16.584  9368  9368 D TimaKeyStoreProvider: TimaSignature is unavailable
09-26 12:24:16.584  9368  9368 D ActivityThread: Added TimaKeyStore provider
09-26 12:24:16.594  3418  3559 V WindowStateAnimator: Finishing drawing window Window{57efb51 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-26 12:24:16.594  3418  4757 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3418
09-26 12:24:16.604  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd2898a78
09-26 12:24:16.614  3418  4302 V WindowStateAnimator: Finishing drawing window Window{2fe0da0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-26 12:24:16.624  3418  4756 D ActivityManager:  Launching com.test.thalitest, updated priority
09-26 12:24:16.624  3418  3993 V WindowStateAnimator: Finishing drawing window Window{181ed1e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-26 12:24:16.624  6063  6063 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 12:24:16.624  6063  6063 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 12:24:16.634  3418  3418 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-26 12:24:16.654  3006  4355 D libEGL  : eglTerminate EGLDisplay = 0x7f936ffe78
09-26 12:24:16.654  3006  4355 D libEGL  : eglTerminate EGLDisplay = 0x7f936ffe78
09-26 12:24:16.664  3418  3994 V WindowStateAnimator: Finishing drawing window Window{2fe0da0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=READY_TO_SHOW
09-26 12:24:16.674  3006  3829 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-26 12:24:16.674  3006  4355 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-26 12:24:16.674  3418  3520 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-26 12:24:16.674  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd2898b98
09-26 12:24:16.674  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:16.684  3418  4302 V WindowStateAnimator: Finishing drawing window Window{181ed1e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=READY_TO_SHOW
09-26 12:24:16.684  3418  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 12:24:16.684  3418  3418 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 12:24:16.684  3418  3854 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-26 12:24:16.694  3418  6010 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 12:24:16.694  3418  6010 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 12:24:16.694  3418  3418 I KnoxTimeoutHandler: SD activityfalse
09-26 12:24:16.694  3418  3418 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3418 (0x0)
09-26 12:24:16.694  9368  9368 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-26 12:24:16.704  3418  3993 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-26 12:24:16.704  9368  9368 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-26 12:24:16.704  4289  4289 D Launcher: onTrimMemory. Level: 20
09-26 12:24:16.704  4289  4289 V ActivityThread: updateVisibility : ActivityRecord{f53819a token=android.os.BinderProxy@d458a0e {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-26 12:24:16.704  6063  6063 V ActivityThread: updateVisibility : ActivityRecord{511bf92 token=android.os.BinderProxy@118dd37 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-26 12:24:16.704  3006  4438 I SurfaceFlinger: id=16 Removed VSBConnecti (6/12)
09-26 12:24:16.704  3006  3829 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-26 12:24:16.714  3418  3559 D ActivityManager: mDVFSHelper.release()
09-26 12:24:16.714  3418  3559 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{40017a u0 com.samsung.android.MtpApplication/.USBConnection t3} time:247173
09-26 12:24:16.714  3006  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f9a43ee78
09-26 12:24:16.714  3006  3829 I SurfaceFlinger: id=17 Removed VSBConnecti (4/11)
09-26 12:24:16.724  3006  3015 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-26 12:24:16.724  9368  9368 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:16.724  3418  6010 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 12:24:16.724  3418  6010 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 12:24:16.724  9368  9368 I InjectionManager: Inside getClassLibPath caller 
09-26 12:24:16.734  3418  6010 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 12:24:16.734  3418  6010 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 12:24:16.734  3418  6010 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 12:24:16.734  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd2898b98
09-26 12:24:16.734  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd2898b98
09-26 12:24:16.744  9368  9368 D InjectionManager: InjectionManager
09-26 12:24:16.744  9368  9368 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-26 12:24:16.744  9368  9368 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-26 12:24:16.744  9368  9368 I InjectionManager: featureStore :{}
09-26 12:24:16.744  3418  3418 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3418 (0x0)
09-26 12:24:16.744  3418  3418 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 12:24:16.744  3418  3418 D PowerManagerService: mDisplayReady: false
09-26 12:24:16.744  3418  3418 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 12:24:16.744  9368  9368 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-26 12:24:16.744  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 12:24:16.744  3418  3418 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 12:24:16.744  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 12:24:16.744  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:16.744  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:16.744  3418  3571 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-26 12:24:16.744  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9a943c00
09-26 12:24:16.744  3418  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-26 12:24:16.744  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-26 12:24:16.754  3418  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-26 12:24:16.754  9368  9368 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-26 12:24:16.754  9368  9368 D RelationGraph: garbageCollect()
09-26 12:24:16.764  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 12:24:16.764  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 12:24:16.764  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:16.764  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 12:24:16.764  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:16.764  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 12:24:16.764  9368  9368 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-26 12:24:16.764  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 12:24:16.764  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 12:24:16.764  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:16.764  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:16.764  3418  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 12:24:16.764  3418  3563 D PowerManagerService: mDisplayReady: true
09-26 12:24:16.764  3418  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-26 12:24:16.784  9368  9368 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-26 12:24:16.814  9368  9368 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-26 12:24:16.814  9368  9368 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:16.814  9368  9368 I InjectionManager: Inside getClassLibPath caller 
09-26 12:24:16.814  9368  9368 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-26 12:24:16.854  9368  9368 I cr_LibraryLoader: Time to load native libraries: 25 ms (timestamps 7290-7315)
09-26 12:24:16.854  9368  9368 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-26 12:24:16.854  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:16.874  3418  3428 I art     : Background partial concurrent mark sweep GC freed 208490(14MB) AllocSpace objects, 94(3MB) LOS objects, 31% free, 34MB/50MB, paused 1.687ms total 210.428ms
09-26 12:24:16.904  9368  9384 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-26 12:24:16.934  9368  9368 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {429cf41}
09-26 12:24:16.934  9368  9368 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-26 12:24:16.934  3418  3879 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-26 12:24:16.954  9368  9368 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-26 12:24:16.974  9368  9368 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-26 12:24:17.034  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:17.034  3418  3879 I MdnieScenarioControlService: mGameModeLauncher : false
09-26 12:24:17.034  3418  3879 I MdnieScenarioControlService: setUIMode
09-26 12:24:17.094  9368  9368 D libEGL  : eglInitialize EGLDisplay = 0xff9845dc
09-26 12:24:17.164  3418  3459 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-26 12:24:17.164  3418  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-26 12:24:17.174  3418  3520 W ActivityManager: Activity pause timeout for ActivityRecord{6da911d u0 com.test.thalitest/.MainActivity t4}
09-26 12:24:17.214  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:17.244  9368  9368 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-26 12:24:17.264  9368  9368 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-26 12:24:17.264  9368  9368 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-26 12:24:17.294  9368  9368 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-26 12:24:17.344  3149  3629 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-26 12:24:17.344  9368  9368 D Activity: performCreate Call Injection manager
09-26 12:24:17.344  9368  9368 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-26 12:24:17.354  9368  9368 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-26 12:24:17.354  9368  9368 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d82d007 I.E...... R.....ID 0,0-0,0}
09-26 12:24:17.364  9368  9423 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-26 12:24:17.364  3418  4596 W WindowManager: Failed looking up window
09-26 12:24:17.364  3418  4596 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@34642d8 does not exist
09-26 12:24:17.364  3418  4596 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 12:24:17.364  3418  4596 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 12:24:17.364  3418  4596 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 12:24:17.364  3418  4596 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-26 12:24:17.364  3418  4596 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-26 12:24:17.364  3418  4596 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-26 12:24:17.364  3418  3993 D ISSUE_DEBUG: InputChannelName : 8587631 com.test.thalitest/com.test.thalitest.MainActivity
09-26 12:24:17.374  3418  4981 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-26 12:24:17.374  3418  4981 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 12:24:17.374  3418  3418 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 12:24:17.374  3418  3418 I KnoxTimeoutHandler: Shared devices show user statefalse
09-26 12:24:17.394  9368  9384 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-26 12:24:17.394  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:17.414  9368  9368 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9368
09-26 12:24:17.424  3418  4981 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9368 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-26 12:24:17.424  3418  3865 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-26 12:24:17.424  3418  3865 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-26 12:24:17.424  9368  9368 V ActivityThread: updateVisibility : ActivityRecord{611d459 token=android.os.BinderProxy@7f6123c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-26 12:24:17.434  3418  3865 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-26 12:24:17.434  3418  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-26 12:24:17.434  3418  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-26 12:24:17.444  3418  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-26 12:24:17.444  9368  9368 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-26 12:24:17.444  3418  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-26 12:24:17.444  3418  3865 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-26 12:24:17.464  3006  3006 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
09-26 12:24:17.484  9368  9423 D libEGL  : eglInitialize EGLDisplay = 0xdc47f7c4
09-26 12:24:17.484  9368  9423 I OpenGLRenderer: Initialized EGL, version 1.4
09-26 12:24:17.484  9368  9423 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-26 12:24:17.484  3418  3460 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3418
09-26 12:24:17.484  3418  3460 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 12:24:17.484  3418  3460 D PowerManagerService: mDisplayReady: false
09-26 12:24:17.484  3418  3460 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 12:24:17.484  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 12:24:17.484  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 12:24:17.484  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9a943c00
09-26 12:24:17.484  3418  3460 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 12:24:17.484  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-26 12:24:17.484  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:17.484  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:17.484  3418  3571 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-26 12:24:17.484  3418  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-26 12:24:17.484  3418  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-26 12:24:17.504  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 12:24:17.504  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 12:24:17.504  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:17.504  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 12:24:17.504  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:17.504  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 12:24:17.504  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 12:24:17.504  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 12:24:17.504  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:17.504  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:17.504  3418  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 12:24:17.504  3418  3563 D PowerManagerService: mDisplayReady: true
09-26 12:24:17.504  3418  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-26 12:24:17.514  9368  9368 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-26 12:24:17.534  3418  3973 V WindowStateAnimator: Finishing drawing window Window{8587631 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-26 12:24:17.534  9368  9368 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-26 12:24:17.544  3418  4981 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3418
09-26 12:24:17.544  3418  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 12:24:17.544  3418  3418 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 12:24:17.544  3418  3559 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +872ms (total +1s61ms)
09-26 12:24:17.544  3418  3559 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6da911d u0 com.test.thalitest/.MainActivity t4} time:248008
09-26 12:24:17.544  3418  3559 D ViewRootImpl: #3 mView = null
09-26 12:24:17.544  3418  3418 I KnoxTimeoutHandler: SD activityfalse
09-26 12:24:17.544  3006  4355 I SurfaceFlinger: id=18 Removed uhalitest (7/11)
09-26 12:24:17.544  3006  4438 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
09-26 12:24:17.554  3418  4757 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3418
09-26 12:24:17.554  3418  4756 V WindowStateAnimator: Finishing drawing window Window{8587631 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-26 12:24:17.564  9368  9427 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 12:24:17.564  9368  9427 D libEGL  : eglInitialize EGLDisplay = 0xda8ec3f4
09-26 12:24:17.564  9368  9368 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7f6123c time:248021
09-26 12:24:17.574  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd2898b98
09-26 12:24:17.584  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:17.594  9368  9427 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-26 12:24:17.644  9368  9368 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9368
,09-26 12:24:17.694  3418  6011 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-26 12:24:17.704  3418  3418 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3418 (0x0)
09-26 12:24:17.704  3418  3418 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 12:24:17.704  3418  3418 D PowerManagerService: mDisplayReady: false
09-26 12:24:17.704  3418  3418 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 12:24:17.704  3418  3418 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 12:24:17.704  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 12:24:17.704  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 12:24:17.704  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:17.704  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-26 12:24:17.704  3418  3571 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-26 12:24:17.704  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9a943c00
09-26 12:24:17.704  3418  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-26 12:24:17.704  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-26 12:24:17.704  3418  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-26 12:24:17.724  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-26 12:24:17.724  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 12:24:17.724  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 12:24:17.724  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:17.724  3418  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-26 12:24:17.724  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:17.724  3418  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 12:24:17.724  3418  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 12:24:17.724  3418  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 12:24:17.724  3418  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 12:24:17.724  3418  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-26 12:24:17.724  3418  3563 D PowerManagerService: mDisplayReady: true
09-26 12:24:17.724  3418  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-26 12:24:17.754  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:17.864  9368  9368 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-26 12:24:17.934  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:17.974  9368  9434 D jxcore_app_log: JniHelper::setJavaVM(0xf4b74000), pthread_self() = -648021712
,09-26 12:24:17.974  9368  9434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-26 12:24:17.974  9368  9434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-26 12:24:17.974  9368  9434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-26 12:24:17.974  9368  9434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-26 12:24:17.974  9368  9434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-26 12:24:17.974  9368  9434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d19c8f7 added. We now have 1 listener(s)
,09-26 12:24:17.984  9368  9434 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-26 12:24:17.984  9368  9434 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-26 12:24:17.984  9368  9434 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-26 12:24:17.984  9368  9434 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-26 12:24:17.984  9368  9434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6fa282 added. We now have 1 listener(s)
09-26 12:24:17.984  9368  9434 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 12:24:17.984  9368  9434 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 12:24:17.984  9368  9434 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-26 12:24:17.984  9368  9434 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-26 12:24:17.984  9368  9434 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-26 12:24:17.984  9368  9434 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-26 12:24:17.994  9368  9434 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:24:17.994  9368  9434 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-26 12:24:18.004  9368  9434 D BluetoothAdapter: STATE_ON
,09-26 12:24:18.004  9368  9434 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:24:18.004  9368  9434 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:24:18.004  9368  9434 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-26 12:24:18.004  9368  9434 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:24:18.004  9368  9434 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-26 12:24:18.004  9368  9368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:24:18.014  9368  9368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:24:18.034  9368  9368 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-26 12:24:18.114  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:18.124  3418  6046 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-26 12:24:18.174  4019  4019 D Recents : onTaskStackChanged
,09-26 12:24:18.184  4019  4019 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-26 12:24:18.194  4019  4019 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:18.294  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:18.394  9368  9435 W jxcore-log: Initializing JXcore engine
09-26 12:24:18.394  9368  9435 W jxcore-log: JXcore engine is ready
,09-26 12:24:18.414  4973  4973 E audit   : type=1400 msg=audit(1474885458.414:262): avc:  denied  { ioctl } for  pid=9435 comm="Thread-156" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2213 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-26 12:24:18.414  4973  4973 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-26 12:24:18.414  4973  4973 E audit   : type=1300 msg=audit(1474885458.414:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d8a053c8 items=0 ppid=3174 pid=9435 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-26 12:24:18.414  4973  4973 E audit   : type=1327 msg=audit(1474885458.414:262): proctitle="com.test.thalitest"
09-26 12:24:18.414  4973  4973 E audit   : type=1320 msg=audit(1474885458.414:262): 
09-26 12:24:18.414  4973  4973 E audit   : type=1400 msg=audit(1474885458.414:263): avc:  denied  { ioctl } for  pid=9435 comm="Thread-156" path="socket:[37922]" dev="sockfs" ino=37922 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-26 12:24:18.414  4973  4973 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-26 12:24:18.414  4973  4973 E audit   : type=1300 msg=audit(1474885458.414:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d8a053c8 items=0 ppid=3174 pid=9435 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-26 12:24:18.414  4973  4973 E audit   : type=1327 msg=audit(1474885458.414:263): proctitle="com.test.thalitest"
09-26 12:24:18.414  4973  4973 E audit   : type=1320 msg=audit(1474885458.414:263): 
,09-26 12:24:18.424  9368  9435 W jxcore-log: Starting JXcore engine
,09-26 12:24:18.454  9368  9435 W jxcore-log: Platform android
09-26 12:24:18.454  9368  9435 W jxcore-log: 
09-26 12:24:18.454  9368  9435 W jxcore-log: Process ARCH arm
09-26 12:24:18.454  9368  9435 W jxcore-log: 
,09-26 12:24:18.474  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:18.524  9368  9435 I jxcore-log: JXcore Cordova bridge is ready!
09-26 12:24:18.524  9368  9435 I jxcore-log: 
09-26 12:24:18.524  9368  9435 W jxcore-log: JXcore engine is started
,09-26 12:24:18.534  9368  9434 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-26 12:24:18.534  9368  9368 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-26 12:24:18.654  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:18.834  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:19.014  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:19.194  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:19.374  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:19.494  3418  3904 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-26 12:24:19.554  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:19.704  3418  6010 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-26 12:24:19.734  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:19.914  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:20.094  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:20.274  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:20.454  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:20.634  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:20.814  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:20.874  3418  6010 D SSRM:n  : SIOP:: AP = 320, PST = 288 (W:6), CP = 243, LCD = 1
,09-26 12:24:20.994  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:21.174  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:21.224  3149  3629 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-26 12:24:21.354  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:21.534  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:21.714  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:21.894  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:22.074  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:22.254  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:22.434  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:22.614  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:22.664  3418  4134 E Watchdog: !@Sync 8 [09-26 12:24:22.670]
,09-26 12:24:22.754  3418  6010 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-26 12:24:22.794  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:22.974  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:23.154  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:23.334  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:23.514  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:23.694  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:23.874  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:24.054  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:24.164  4372  4453 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-26 12:24:24.164  4372  4453 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-26 12:24:24.234  4372  4453 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 72ms lastUpdatedAfter : 146949ms
,09-26 12:24:24.234  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:24.414  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:24.514  9368  9435 I jxcore-log: 2016-09-26 10:24:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-26 12:24:24.514  9368  9435 I jxcore-log: 
,09-26 12:24:24.514  9368  9435 I jxcore-log: 2016-09-26 10:24:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-26 12:24:24.514  9368  9435 I jxcore-log: 
,09-26 12:24:24.524  9368  9435 D BluetoothAdapter: STATE_ON
,09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:24:24.524  9368  9435 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:24:24.524  9368  9435 D BluetoothAdapter: STATE_ON
,09-26 12:24:24.534  9368  9435 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:24:24.534  9368  9435 I jxcore-log: 2016-09-26 10:24:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-26 12:24:24.534  9368  9435 I jxcore-log: 
09-26 12:24:24.534  9368  9435 I jxcore-log: 2016-09-26 10:24:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-26 12:24:24.534  9368  9435 I jxcore-log: 
,09-26 12:24:24.594  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:24.694  8200  8223 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-26 12:24:24.704  9368  9435 E jxcore  : Error!: logger is not a function
09-26 12:24:24.704  9368  9435 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"20","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:20:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"}]
,09-26 12:24:24.704  9368  9435 I jxcore-log: 2016-09-26 10:24:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:24:24.704  9368  9435 I jxcore-log: 
,09-26 12:24:24.714  9368  9368 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "logger is not a function\nTypeError: logger is not a function\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:20:3\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7"", source: file:///android_asset/www/js/thali_main.js (56)
,09-26 12:24:24.714  9368  9368 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,09-26 12:24:24.714  3418  4596 W VirtualScreenManagerService: failed to move task TaskRecord{e7b89fa #4 A=com.test.thalitest U=0 sz=1}
09-26 12:24:24.724  3418  4596 D InputDispatcher: Focused application set to: xxxx
,09-26 12:24:24.734  3418  4596 I ActivityManager: Killing 8567:com.android.providers.calendar/u0a47 (adj 15): DHA:empty #33
,09-26 12:24:24.754  9368  9434 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 38ms. Plugin should use CordovaInterface.getThreadPool().
,09-26 12:24:24.754  9368  9368 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-26 12:24:24.754  9368  9368 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
09-26 12:24:24.754  9368  9368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:24:24.754  9368  9368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:24:24.754  9368  9368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-26 12:24:24.754  9368  9368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 12:24:24.754  9368  9368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d19c8f7 removed from the list
09-26 12:24:24.754  9368  9368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:24:24.754  9368  9368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6fa282 removed from the list
09-26 12:24:24.754  9368  9368 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:24:24.754  9368  9368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,09-26 12:24:24.764  9368  9368 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-26 12:24:24.764  3418  6010 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 12:24:24.764  9368  9368 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,09-26 12:24:24.784  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:24.784  9368  9368 D ViewRootImpl: #3 mView = null
,09-26 12:24:24.784  3418  4756 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,09-26 12:24:24.794  3006  4438 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
09-26 12:24:24.794  3006  4355 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-26 12:24:24.804  3418  6010 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-26 12:24:24.804  3418  6010 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 12:24:24.804  3418  3459 D ActivityManager: mDVFSHelper.acquire()
,09-26 12:24:24.834  3006  3006 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-26 12:24:24.874  4289  4289 D Launcher: onRestart, Launcher: 1316307
,09-26 12:24:24.904  3418  4875 V WindowStateAnimator: Finishing drawing window Window{2fe0da0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-26 12:24:24.904  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd2898a78
,09-26 12:24:24.954  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:25.134  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:25.144  3418  3459 I WindowManager: Screenshot max retries 4 of Token{a0ffd2b ActivityRecord{40017a u0 com.samsung.android.MtpApplication/.USBConnection t3}} appWin=Window{2fe0da0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
,09-26 12:24:25.144  3418  3418 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-26 12:24:25.164  3418  3520 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
09-26 12:24:25.164  4289  4289 D Launcher: onStart, Launcher: 1316307
09-26 12:24:25.164  4289  4289 D Launcher.HomeView: onStart
09-26 12:24:25.164  3418  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 12:24:25.164  3418  3418 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 12:24:25.164  3418  3559 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{40017a u0 com.samsung.android.MtpApplication/.USBConnection t3} time:255628
09-26 12:24:25.164  3418  3879 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
09-26 12:24:25.164  3418  3994 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-26 12:24:25.164  3418  3559 D ActivityManager: mDVFSHelper.release()
09-26 12:24:25.164  3418  3994 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 12:24:25.174  4289  4289 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-26 12:24:25.174  3418  3418 I KnoxTimeoutHandler: SD activityfalse
,09-26 12:24:25.174  3418  3418 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 12:24:25.174  4289  4289 V ActivityThread: updateVisibility : ActivityRecord{f53819a token=android.os.BinderProxy@d458a0e {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-26 12:24:25.184  4289  4289 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-26 12:24:25.184  4289  4289 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-26 12:24:25.184  4289  4289 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,09-26 12:24:25.184  3418  3418 I KnoxTimeoutHandler: Shared devices show user statefalse
09-26 12:24:25.184  4289  4289 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-26 12:24:25.184  3418  3418 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
09-26 12:24:25.184  4289  4289 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-26 12:24:25.184  4289  4289 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
,09-26 12:24:25.184  3006  3006 I SurfaceFlinger: id=21 createSurf (1592x384),1 flag=4, VSBConnecti
09-26 12:24:25.184  4289  4289 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-26 12:24:25.184  4289  4289 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-26 12:24:25.184  4289  4289 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
09-26 12:24:25.184  3418  6010 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 12:24:25.184  9438  9438 I FIPS_bssl: FIPS approved mode (1) | 9438 | app_process
,09-26 12:24:25.184  3418  6010 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-26 12:24:25.184  3418  6010 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 12:24:25.194  9438  9438 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 12:24:25.194  3006  3006 I SurfaceFlinger: id=22 createSurf (1440x2560),1 flag=4, MauncherAct
,09-26 12:24:25.194  9438  9438 D AndroidRuntime: CheckJNI is OFF
,09-26 12:24:25.194  9438  9438 D AndroidRuntime: readGMSProperty: start
09-26 12:24:25.194  9438  9438 D AndroidRuntime: readGMSProperty: already setted!!
09-26 12:24:25.194  9438  9438 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-26 12:24:25.194  9438  9438 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-26 12:24:25.194  9438  9438 D AndroidRuntime: readGMSProperty: end
09-26 12:24:25.194  9438  9438 D AndroidRuntime: addProductProperty: start
,09-26 12:24:25.204  4289  4609 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-26 12:24:25.214  3418  3994 V WindowStateAnimator: Finishing drawing window Window{181ed1e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-26 12:24:25.214  6063  6063 V ActivityThread: updateVisibility : ActivityRecord{511bf92 token=android.os.BinderProxy@118dd37 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-26 12:24:25.214  9438  9438 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 12:24:25.214  6063  6063 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@118dd37 time:255674
,09-26 12:24:25.224  3418  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 12:24:25.224  3418  3418 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 12:24:25.234  3418  3418 I KnoxTimeoutHandler: SD activityfalse
,09-26 12:24:25.234  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd2898a78
,09-26 12:24:25.234  9438  9438 I Radio-JNI: register_android_hardware_Radio DONE
,09-26 12:24:25.234  9438  9438 E AffinityControl: AffinityControl: registerfunction enter
,09-26 12:24:25.244  9438  9438 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-26 12:24:25.244  3418  3851 D PackageManager: START PACKAGE DELETE: observer{7083}
09-26 12:24:25.244  3418  3851 D PackageManager: pkg{<packageName>}
09-26 12:24:25.244  3418  3851 D PackageManager: user{0}
09-26 12:24:25.244  3418  3851 D PackageManager: caller{2000}
09-26 12:24:25.244  3418  3851 D PackageManager: flags{2}
09-26 12:24:25.244  3418  3851 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-26 12:24:25.244  3418  3851 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-26 12:24:25.244  3418  3851 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-26 12:24:25.244  3418  3851 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-26 12:24:25.244  3418  3851 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-26 12:24:25.244  3418  3577 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-26 12:24:25.244  3418  3577 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-26 12:24:25.244  3418  3577 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-26 12:24:25.244  3418  3577 D ApplicationPolicy: getApplicationUninstallationEnabled
09-26 12:24:25.244  3418  3577 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-26 12:24:25.244  3418  4301 V WindowStateAnimator: Finishing drawing window Window{afc40ad u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,09-26 12:24:25.244  4289  4289 D Launcher.HomeView: onStop
09-26 12:24:25.244  3418  3577 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-26 12:24:25.244  4289  4289 D capture : ----destroy
09-26 12:24:25.244  3418  3577 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-26 12:24:25.254  3418  3577 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
09-26 12:24:25.254  3418  3577 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-26 12:24:25.254  3418  3577 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-26 12:24:25.254  3418  3520 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-26 12:24:25.254  3418  3520 I ActivityManager: Killing 9368:com.test.thalitest/u0a171 (adj 9): stop com.test.thalitest cause uninstall pkg
09-26 12:24:25.254  3418  3520 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-26 12:24:25.264  3418  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 12:24:25.264  3418  3418 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-26 12:24:25.264  3418  3418 I KnoxTimeoutHandler: SD activityfalse
,09-26 12:24:25.264  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd2898a78
09-26 12:24:25.264  3418  3577 D AASAinstall: there is not AASApackages.xml file
09-26 12:24:25.264  3418  3879 I MdnieScenarioControlService: mGameModeLauncher : false
09-26 12:24:25.264  3418  3879 I MdnieScenarioControlService: setUIMode
09-26 12:24:25.264  3418  3559 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{640ce7d u0 com.sec.android.app.launcher/.activities.LauncherActivity t1} time:255729
,09-26 12:24:25.314  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:25.384  3418  4368 D GraphicsStats: Buffer count: 5
,09-26 12:24:25.384  3418  4875 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@9bc1208)
09-26 12:24:25.384  3418  3865 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-26 12:24:25.384  3418  3865 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 12:24:25.394  3418  3865 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 12:24:25.494  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:25.534  3418  3577 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-26 12:24:25.604  3418  3577 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
09-26 12:24:25.614  3162  3162 W keystore: ENTER clear_uid from uid 1000 for 10171
09-26 12:24:25.614  3418  3879 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
09-26 12:24:25.614  3418  3577 I art     : Starting a blocking GC Explicit
,09-26 12:24:25.674  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:25.714  3418  3879 I MdnieScenarioControlService: mGameModeLauncher : false
09-26 12:24:25.714  3418  3879 I MdnieScenarioControlService: setUIMode
,09-26 12:24:25.784  3418  3577 I art     : Explicit concurrent mark sweep GC freed 111736(5MB) AllocSpace objects, 15(300KB) LOS objects, 32% free, 33MB/49MB, paused 5.062ms total 170.170ms
,09-26 12:24:25.824  3418  3577 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-26 12:24:25.824  3418  3577 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-26 12:24:25.824  3418  3577 D AASAinstall: there is not AASApackages.xml file
09-26 12:24:25.824  3418  3577 D PackageManager: result of delete: 1{7083}
,09-26 12:24:25.834  3418  3577 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-26 12:24:25.834  3418  3577 D PackageManager: userId{-1}
09-26 12:24:25.834  3418  3577 D PackageManager: andCode{true}
,09-26 12:24:25.834  9438  9438 I art     : System.exit called, status: 0
09-26 12:24:25.834  9438  9438 I AndroidRuntime: VM exiting with result code 0.
,09-26 12:24:25.844  3418  3577 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-26 12:24:25.854  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-26 12:24:25.884  8877  9450 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-26 12:24:25.884  8877  9450 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-26 12:24:25.894  8877  9450 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
09-26 12:24:25.894  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 12:24:25.904  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-26 12:24:25.904  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:25.904  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 12:24:25.904  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 12:24:25.914  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.914  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:25.914  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.914  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-26 12:24:25.914  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.914  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-26 12:24:25.914  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.914  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 12:24:25.914  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 12:24:25.914  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-26 12:24:25.924  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.924  3935  3935 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-26 12:24:25.924  3935  3935 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
09-26 12:24:25.924  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:25.924  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
09-26 12:24:25.924  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 12:24:25.924  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-26 12:24:25.934  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.934  3418  3559 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.934  3418  3559 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.934  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 12:24:25.934  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 12:24:25.934  3418  3559 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.934  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-26 12:24:25.934  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-26 12:24:25.934  3418  3827 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-26 12:24:25.934  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 12:24:25.934  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-26 12:24:25.944  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:25.944  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-26 12:24:25.944  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-26 12:24:25.944  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:25.944  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-26 12:24:25.944  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.944  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-26 12:24:25.944  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-26 12:24:25.944  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-26 12:24:25.944  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 12:24:25.944  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,09-26 12:24:25.954  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:25.954  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.954  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 12:24:25.954  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-26 12:24:25.954  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 12:24:25.954  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 12:24:25.954  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 12:24:25.954  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-26 12:24:25.954  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,09-26 12:24:25.954  4253  4765 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-26 12:24:25.964  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.964  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.964  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,09-26 12:24:25.964  3418  3516 D AccessibilityManagerService: onUserStateChangedLocked()
09-26 12:24:25.964  3418  3516 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.964  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:25.974  5010  5236 D PresenceModule: onReceive: package removed
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-26 12:24:25.974  5010  5236 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
09-26 12:24:25.974  5010  5236 D PresenceModule: Application package removed
09-26 12:24:25.974  5010  5236 D PresenceModule: onAppPkgRemoved: com.test.thalitest
09-26 12:24:25.974  5010  5236 D PresenceModule: onApplicationPackageRemoved: invalid package
09-26 12:24:25.974  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-26 12:24:25.974  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 12:24:25.974  8200  8219 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
09-26 12:24:25.974  8200  8219 I ControllerEventHandler: [#CMH#] onPackageRemoved  null
09-26 12:24:25.974  8200  8219 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
09-26 12:24:25.984  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 12:24:25.984  3418  3516 D EnterpriseDeviceManagerService: Package has changed for user 0
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 12:24:25.984  3418  3516 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.984  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-26 12:24:25.984  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.984  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.984  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.984  3418  3520 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f48c0ba u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8753044 6482:com.samsung.klmsagent/u0a26}
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-26 12:24:25.994  6482  6482 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Mon Sep 26 12:24:26 GMT+02:00 2016
09-26 12:24:25.994  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.994  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:25.994  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-26 12:24:25.994  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 12:24:26.004  3418  3853 D NtpTrustedTime: currentTimeMillis() cache hit
09-26 12:24:25.994  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-26 12:24:25.994  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.004  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-26 12:24:26.004  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-26 12:24:26.004  3418  3853 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-26 12:24:26.004  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.004  3418  3853 V NetworkStats: performPollLocked(flags=0x3)
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-26 12:24:26.004  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.004  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.004  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 12:24:26.004  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 12:24:26.004  3418  3853 D NetworkStatsRecorder: entry.iface is null
09-26 12:24:26.004  3418  3853 D NetworkStatsRecorder: entry.iface is null
09-26 12:24:26.004  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.004  3418  3854 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
09-26 12:24:26.004  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.004  3418  3854 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-26 12:24:26.004  3418  3853 D NetworkStatsRecorder: entry.iface is null
09-26 12:24:26.004  3418  3853 D NetworkStatsRecorder: entry.iface is null
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-26 12:24:26.004  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 12:24:26.004  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 12:24:26.004  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-26 12:24:26.014  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.014  3418  3418 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.014  3418  3418 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-26 12:24:26.014  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-26 12:24:26.014  3418  4368 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4827, uid=10124 that is not exported from uid 10122
09-26 12:24:26.014  3418  3418 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
09-26 12:24:26.014  3418  3418 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-26 12:24:26.014  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-26 12:24:26.014  4019  4019 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-26 12:24:26.014  3418  3418 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-26 12:24:26.014  3418  3418 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-26 12:24:26.014  3418  3418 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-26 12:24:26.014  3418  3418 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-26 12:24:26.014  3418  3418 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
09-26 12:24:26.014  3418  3418 I OTPFW   : ProvisionData::getAllEntries Enter
09-26 12:24:26.014  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.014  3418  3418 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-26 12:24:26.014  3418  3418 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
09-26 12:24:26.014  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-26 12:24:26.014  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-26 12:24:26.014  3418  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708- -> /data/system/netstats/uid.1473847817708-.backup
09-26 12:24:26.014  3418  3418 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
09-26 12:24:26.014  3418  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-
09-26 12:24:26.014  3418  3418 D UcmService: Package update in userId-0 and uid-10171
09-26 12:24:26.014  3418  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-.backup -> /data/system/netstats/uid.1473847817708-
09-26 12:24:26.014  3418  3418 D InjectionManagerService -AppFeature:  Info before com.test.thalitest removal target ={} 
09-26 12:24:26.014  3418  3418 D InjectionManagerService -AppFeature:  source ={}
09-26 12:24:26.014  3418  3418 W SQLiteLog: (28) failed to open "/data/system/gamemanager.db" with flag (131138) and mode_t (0) due to error (30)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: Failed to open database '/data/system/gamemanager.db'.
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: #################################################################
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: #################################################################
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-26 12:24:26.024  3418  3418 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-26 12:24:26.024  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.024  3418  3418 D AndroidRuntime: Shutting down VM
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:26.024  3418  3418 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
09-26 12:24:26.024  3418  3418 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } in com.samsung.android.game.GameManagerService$UninstallReceiver@2f58d81
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1003)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-26 12:24:26.024  3418  3418 E AndroidRuntime: #################################################################
09-26 12:24:26.024  3418  3418 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-26 12:24:26.024  3418  3418 E AndroidRuntime: #################################################################
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-26 12:24:26.024  3418  3418 E AndroidRuntime: 	... 8 more
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-26 12:24:26.024  4276  4276 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-26 12:24:26.024  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-26 12:24:26.034  6482  6482 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive().END.
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 12:24:26.034  3418  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-26 12:24:26.034  3418  3853 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-26 12:24:26.024  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
09-26 12:24:26.034  3418  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-
09-26 12:24:26.034  3418  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201655233-1473847639678
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-26 12:24:26.034  6482  6482 I KLMS-2.6.201: : KLMSIntentService(): onCreate()
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-26 12:24:26.034  3418  3904 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/4_task.xml
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 12:24:26.034  6482  6482 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-26 12:24:26.044  3418  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474883348145- -> /data/system/netstats/uid_tag.1474883348145-.backup
09-26 12:24:26.034  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: Can't write: netstats_dump
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1222)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 12:24:26.034  3418  3853 E DropBoxManagerService: 	... 16 more
09-26 12:24:26.044  3418  3904 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/4_task_thumbnail.png
09-26 12:24:26.034  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-26 12:24:26.044  3418  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474883348145-
09-26 12:24:26.044  3418  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474883348145-.backup -> /data/system/netstats/uid_tag.1474883348145-
09-26 12:24:26.044  6482  6482 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-26 12:24:26.044  6482  9455 I KLMS-2.6.201: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: Can't write: netstats_dump
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1223)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 12:24:26.044  3418  3853 E DropBoxManagerService: 	... 16 more
09-26 12:24:26.044  3418  3853 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-26 12:24:26.044  3418  4302 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f48c0ba u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ab9f284 3418:system/1000}
,09-26 12:24:26.044  3418  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474883348145-
09-26 12:24:26.044  3418  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157707-1474873077928
09-26 12:24:26.044  3418  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1473847817708-1474285028441
09-26 12:24:26.044  3418  3853 D NtpTrustedTime: currentTimeMillis() cache hit
09-26 12:24:26.044  3418  3853 V NetworkStats: performPollLocked() took 46ms
09-26 12:24:26.044  6482  9455 D KLMS-2.6.201: : KLMSIntentService(): PACKAGE_REMOVED
09-26 12:24:26.044  6482  9455 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().START
09-26 12:24:26.054  6482  9455 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-26 12:24:26.054  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-26 12:24:26.054  6482  9455 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-26 12:24:26.054  6482  9455 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
09-26 12:24:26.054  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-26 12:24:26.054  3418  3418 E android.os.Debug: THIS IS SYSTEM_SERVER.. store dumpState!!
09-26 12:24:26.054  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-26 12:24:26.054  3418  3516 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-26 12:24:26.054  6482  9455 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-26 12:24:26.054  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-26 12:24:26.054  6482  9455 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-26 12:24:26.054  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-26 12:24:26.054  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 12:24:26.054  3418  3854 D NtpTrustedTime: currentTimeMillis() cache hit
09-26 12:24:26.054  3418  3854 D NtpTrustedTime: currentTimeMillis() cache hit
09-26 12:24:26.064  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
09-26 12:24:26.064  6482  9455 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
09-26 12:24:26.064  4264  9456 D RegisteredComponentCache: Collect Tech packages for Knox
09-26 12:24:26.064  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.064  4264  9456 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
09-26 12:24:26.064  4264  9456 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
09-26 12:24:26.064  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
09-26 12:24:26.064  4264  9456 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
09-26 12:24:26.064  4264  9456 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
09-26 12:24:26.064  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
09-26 12:24:26.064  6482  9455 D KLMS-2.6.201: : Systemprocess(): arrayLicenseInfo is null
09-26 12:24:26.064  3418  3516 D ResourcesManager: For user 0 new overlays fetched Null
09-26 12:24:26.074  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
09-26 12:24:26.074  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
09-26 12:24:26.074  3418  3516 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
09-26 12:24:26.074  6482  9455 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)

```
