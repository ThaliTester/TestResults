#### Test 855940258c32634_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-21 10:37:20.870  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:21.050  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:21.230  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:21.410  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:21.540  9947  9947 I FIPS_bssl: FIPS approved mode (1) | 9947 | app_process
09-21 10:37:21.550  9947  9947 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 10:37:21.550  9947  9947 D AndroidRuntime: CheckJNI is OFF
09-21 10:37:21.550  9947  9947 D AndroidRuntime: readGMSProperty: start
09-21 10:37:21.550  9947  9947 D AndroidRuntime: readGMSProperty: already setted!!
09-21 10:37:21.550  9947  9947 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-21 10:37:21.550  9947  9947 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-21 10:37:21.550  9947  9947 D AndroidRuntime: readGMSProperty: end
09-21 10:37:21.550  9947  9947 D AndroidRuntime: addProductProperty: start
09-21 10:37:21.570  9947  9947 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 10:37:21.590  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:21.590  9947  9947 I Radio-JNI: register_android_hardware_Radio DONE
09-21 10:37:21.600  9947  9947 E AffinityControl: AffinityControl: registerfunction enter
09-21 10:37:21.610  9947  9947 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-21 10:37:21.660  3443  4409 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-21 10:37:21.660  3443  4409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-21 10:37:21.680  3443  4409 D ResourcesManager: For user 0 new overlays fetched Null
09-21 10:37:21.680  3443  4409 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:37:21.680  3443  4409 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-21 10:37:21.690  3443  4409 D ActivityManager: mDVFSHelper.acquire()
09-21 10:37:21.690  3443  4409 V WindowManager: addAppToken: AppWindowToken{d08e6620d token=Token{cc344a4 ActivityRecord{8084737 u0 com.test.thalitest/.MainActivity t9}}} to stack=2 task=9 at 0
09-21 10:37:21.700  3443  3559 I InjectionManager: Inside getClassLibPath caller 
09-21 10:37:21.700  3443  3559 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-21 10:37:21.700  3443  3559 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a72c5c5 V.E...... R.....ID 0,0-0,0}
09-21 10:37:21.710  3443  3559 W WindowManager: Failed looking up window
09-21 10:37:21.710  3443  3559 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@67e6b1a does not exist
09-21 10:37:21.710  3443  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 10:37:21.710  3443  3559 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 10:37:21.710  3443  3559 D ISSUE_DEBUG: InputChannelName : 891b64b Starting com.test.thalitest
09-21 10:37:21.710  3443  4409 I ActivityManager: Start proc 9956:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-21 10:37:21.710  3443  4409 D InputDispatcher: Focused application set to: xxxx
09-21 10:37:21.710  3443  3859 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-21 10:37:21.710  9947  9947 D AndroidRuntime: Shutting down VM
09-21 10:37:21.710  9956  9956 E Zygote  : v2
09-21 10:37:21.710  9956  9956 I libpersona: KNOX_SDCARD checking this for 10171
09-21 10:37:21.710  9956  9956 I libpersona: KNOX_SDCARD not a persona
09-21 10:37:21.710  9956  9956 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-21 10:37:21.720  9956  9956 E Zygote  : accessInfo : 0
09-21 10:37:21.720  9956  9956 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-21 10:37:21.720  3007  3007 I SurfaceFlinger: id=32 createSurf (1x1),1 flag=404, uhalitest
09-21 10:37:21.750  9701  9701 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 10:37:21.760  3443  4408 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443
09-21 10:37:21.760  3443  4408 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 10:37:21.760  3443  4408 D PowerManagerService: mDisplayReady: false
09-21 10:37:21.760  3443  4408 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 10:37:21.760  3443  4408 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 10:37:21.760  3443  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 10:37:21.760  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 10:37:21.760  9701  9701 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 10:37:21.760  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 10:37:21.760  3443  3443 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 10:37:21.760  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:21.760  3443  3559 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-21 10:37:21.760  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:21.760  3443  3443 I KnoxTimeoutHandler: SD activityfalse
09-21 10:37:21.760  3443  4378 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443
09-21 10:37:21.760  3443  3577 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-21 10:37:21.760  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f81d83c00
09-21 10:37:21.760  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-21 10:37:21.760  3443  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-21 10:37:21.760  3443  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-21 10:37:21.760  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 10:37:21.760  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 10:37:21.760  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:21.760  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:21.760  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 10:37:21.760  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 10:37:21.760  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 10:37:21.760  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 10:37:21.760  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:21.760  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:21.760  3443  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 10:37:21.760  3443  3563 D PowerManagerService: mDisplayReady: true
09-21 10:37:21.760  3443  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 10:37:21.770  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:21.790  9956  9956 D TimaKeyStoreProvider: TimaSignature is unavailable
09-21 10:37:21.790  9956  9956 D ActivityThread: Added TimaKeyStore provider
09-21 10:37:21.790  3443  4246 V WindowStateAnimator: Finishing drawing window Window{5ad068b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-21 10:37:21.810  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc36d1218
09-21 10:37:21.810  3443  4390 D ActivityManager:  Launching com.test.thalitest, updated priority
09-21 10:37:21.820  3443  3559 V WindowStateAnimator: Finishing drawing window Window{891b64b u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-21 10:37:21.830  3007  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f81b00e78
09-21 10:37:21.830  3007  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f81b00e78
09-21 10:37:21.840  3007  4128 I SurfaceFlinger: id=9 Removed MauncherAct (4/13)
09-21 10:37:21.840  3007  3835 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-21 10:37:21.840  3443  3443 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-21 10:37:21.840  3443  4409 V WindowStateAnimator: Finishing drawing window Window{74f0c05 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-21 10:37:21.840  9701  9701 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 10:37:21.840  9701  9701 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 10:37:21.840  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc36d1338
09-21 10:37:21.840  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc36d1218
09-21 10:37:21.850  4300  4300 V ActivityThread: updateVisibility : ActivityRecord{ba9c72f token=android.os.BinderProxy@55d1d77 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-21 10:37:21.850  9701  9701 V ActivityThread: updateVisibility : ActivityRecord{8a5b87a token=android.os.BinderProxy@604d14c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-21 10:37:21.850  4300  4300 D Launcher: onTrimMemory. Level: 20
09-21 10:37:21.860  3007  4128 I SurfaceFlinger: id=29 Removed VSBConnecti (5/12)
09-21 10:37:21.860  3007  3016 I SurfaceFlinger: id=29 Removed VSBConnecti (-2/12)
09-21 10:37:21.860  3007  3835 D libEGL  : eglTerminate EGLDisplay = 0x7f7a5fee78
09-21 10:37:21.860  3007  3016 I SurfaceFlinger: id=28 Removed VSBConnecti (6/11)
09-21 10:37:21.860  3007  4375 I SurfaceFlinger: id=28 Removed VSBConnecti (-2/11)
09-21 10:37:21.870  3007  4128 D libEGL  : eglTerminate EGLDisplay = 0x7f7a4ffe78
09-21 10:37:21.870  3007  4128 D libEGL  : eglTerminate EGLDisplay = 0x7f7a4ffe78
09-21 10:37:21.880  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc36d1338
09-21 10:37:21.880  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc36d1338
09-21 10:37:21.910  3443  3443 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443 (0x0)
09-21 10:37:21.910  3443  3443 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443 (0x0)
09-21 10:37:21.910  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 10:37:21.910  3443  3443 D PowerManagerService: mDisplayReady: false
09-21 10:37:21.910  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 10:37:21.910  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 10:37:21.910  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 10:37:21.910  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f81d83c00
09-21 10:37:21.910  3443  3443 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 10:37:21.910  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-21 10:37:21.910  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:21.910  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:21.910  3443  3577 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-21 10:37:21.920  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 10:37:21.920  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 10:37:21.920  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:21.920  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 10:37:21.920  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:21.920  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 10:37:21.920  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 10:37:21.920  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 10:37:21.920  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:21.920  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:21.920  3443  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 10:37:21.920  3443  3563 D PowerManagerService: mDisplayReady: true
09-21 10:37:21.920  3443  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 10:37:21.950  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:22.130  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:22.160  3443  4390 I WindowManager: Screenshot max retries 4 of Token{cc344a4 ActivityRecord{8084737 u0 com.test.thalitest/.MainActivity t9}} appWin=Window{891b64b u0 d0 Starting com.test.thalitest} drawState=4
09-21 10:37:22.170  3443  3532 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-21 10:37:22.170  3443  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 10:37:22.170  3443  3443 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 10:37:22.180  3443  5920 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:37:22.180  3443  3859 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-21 10:37:22.180  3443  5920 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:37:22.180  3443  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-21 10:37:22.180  3443  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-21 10:37:22.190  3443  3443 I KnoxTimeoutHandler: SD activityfalse
09-21 10:37:22.210  9956  9956 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 10:37:22.220  3443  4963 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-21 10:37:22.220  9956  9956 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-21 10:37:22.230  3443  5920 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 10:37:22.230  9956  9956 D ResourcesManager: For user 0 new overlays fetched Null
09-21 10:37:22.240  3443  5920 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:37:22.240  9956  9956 I InjectionManager: Inside getClassLibPath caller 
09-21 10:37:22.240  3443  5920 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 10:37:22.250  3443  5920 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:37:22.250  3443  5920 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:37:22.260  9956  9956 D InjectionManager: InjectionManager
09-21 10:37:22.260  9956  9956 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-21 10:37:22.260  9956  9956 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-21 10:37:22.260  9956  9956 I InjectionManager: featureStore :{}
09-21 10:37:22.270  9956  9956 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 10:37:22.270  9956  9956 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-21 10:37:22.270  9956  9956 D RelationGraph: garbageCollect()
09-21 10:37:22.280  9956  9956 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 10:37:22.310  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:22.320  9956  9956 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-21 10:37:22.390  9956  9956 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-21 10:37:22.400  9956  9956 D ResourcesManager: For user 0 new overlays fetched Null
09-21 10:37:22.400  9956  9956 I InjectionManager: Inside getClassLibPath caller 
09-21 10:37:22.410  9956  9956 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-21 10:37:22.420  3443  3883 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-21 10:37:22.450  9956  9956 I cr_LibraryLoader: Time to load native libraries: 25 ms (timestamps 6608-6633)
09-21 10:37:22.450  9956  9956 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 10:37:22.490  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:22.490  9956  9971 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-21 10:37:22.510  9956  9956 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {315e73}
09-21 10:37:22.510  9956  9956 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 10:37:22.520  3443  3883 I MdnieScenarioControlService: mGameModeLauncher : false
09-21 10:37:22.520  3443  3883 I MdnieScenarioControlService: setUIMode
09-21 10:37:22.540  9956  9956 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-21 10:37:22.570  9956  9956 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-21 10:37:22.670  3443  3532 W ActivityManager: Activity pause timeout for ActivityRecord{8084737 u0 com.test.thalitest/.MainActivity t9}
09-21 10:37:22.670  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:22.730  9956  9956 D libEGL  : eglInitialize EGLDisplay = 0xff81973c
09-21 10:37:22.810  3443  3982 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
,09-21 10:37:22.810  3443  3982 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-21 10:37:22.850  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:22.900  9956  9956 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-21 10:37:22.920  9956  9956 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 10:37:22.920  9956  9956 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-21 10:37:22.960  9956  9956 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-21 10:37:23.010  9956  9956 D Activity: performCreate Call Injection manager
,09-21 10:37:23.010  9956  9956 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-21 10:37:23.020  9956  9956 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 10:37:23.030  9956  9956 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{550108e I.E...... R.....ID 0,0-0,0}
,09-21 10:37:23.030  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:23.030  9956 10008 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 10:37:23.040  3443  4390 W WindowManager: Failed looking up window
09-21 10:37:23.040  3443  4390 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@6e97e7a does not exist
09-21 10:37:23.040  3443  4390 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 10:37:23.040  3443  4390 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 10:37:23.040  3443  4390 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 10:37:23.040  3443  4390 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-21 10:37:23.040  3443  4390 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-21 10:37:23.040  3443  4390 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-21 10:37:23.050  3443  4378 D ISSUE_DEBUG: InputChannelName : 250362b com.test.thalitest/com.test.thalitest.MainActivity
,09-21 10:37:23.060  3443  4326 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-21 10:37:23.060  3443  4326 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 10:37:23.060  3443  3443 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 10:37:23.060  3443  3443 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-21 10:37:23.060  9956  9956 V ActivityThread: updateVisibility : ActivityRecord{1844cbc token=android.os.BinderProxy@1581571 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-21 10:37:23.070  9956  9971 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-21 10:37:23.100  9956  9956 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9956
,09-21 10:37:23.110  3443  4326 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9956 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 10:37:23.110  3443  3871 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-21 10:37:23.110  3443  3871 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-21 10:37:23.120  3443  4933 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-21 10:37:23.120  3443  4933 D BatteryService: level:100, scale:100, status:3, health:9, present:true, voltage: 4293, temperature: 272, technology: Li-ion, AC powered:false, USB powered:false, POGO powered:false, Wireless powered:false, icon:17303399, invalid charger:0, maxChargingCurrent:0
09-21 10:37:23.120  3443  4933 D BatteryService: online:4, current avg:-103, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-233
09-21 10:37:23.120  3443  3443 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-21 10:37:23.120  3443  3871 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-21 10:37:23.130  3443  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-21 10:37:23.130  3443  3443 I MotionRecognitionService: On Battery, 0
09-21 10:37:23.130  3443  3443 D MotionRecognitionService:   cableConnection= 0
,09-21 10:37:23.130  3443  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-21 10:37:23.130  3443  3865 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-21 10:37:23.140  9956  9956 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-21 10:37:23.140  3951  3951 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-21 10:37:23.140  3951  3951 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-21 10:37:23.140  3951  3951 D PowerUI : priorPlugType = 0 mPlugType =  0
,09-21 10:37:23.140  3443  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 10:37:23.150  4946  4946 D CommonServiceConfiguration: getStringValueSetting
,09-21 10:37:23.150  4900  4900 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-21 10:37:23.150  4900  5316 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-21 10:37:23.160  3443  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-21 10:37:23.160  3443  3871 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 10:37:23.160  4946  4946 D BatteryMonitor: new battery level: 100
,09-21 10:37:23.160  3007  3007 I SurfaceFlinger: id=33 createSurf (1x1),1 flag=404, NainActivit
,09-21 10:37:23.160  4732  4732 D BatteryController: saveBatteryData : level[100], status[3]
,09-21 10:37:23.170  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:9
09-21 10:37:23.170  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,09-21 10:37:23.170  3443  5921 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-21 10:37:23.200  9956 10008 D libEGL  : eglInitialize EGLDisplay = 0xdc63f7c4
,09-21 10:37:23.200  9956 10008 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 10:37:23.210  9956 10008 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-21 10:37:23.210  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:23.210  3443  4409 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443
,09-21 10:37:23.210  3443  4409 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 10:37:23.210  3443  4409 D PowerManagerService: mDisplayReady: false
09-21 10:37:23.210  3443  4409 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 10:37:23.210  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-21 10:37:23.210  3443  4409 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 10:37:23.210  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 10:37:23.210  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:23.210  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:23.210  3443  3577 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,09-21 10:37:23.210  3443  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-21 10:37:23.210  3443  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-21 10:37:23.220  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f81d83c00
09-21 10:37:23.220  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-21 10:37:23.240  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 10:37:23.240  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 10:37:23.240  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 10:37:23.240  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:23.240  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 10:37:23.240  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:23.240  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 10:37:23.240  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 10:37:23.240  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:23.240  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:23.240  3443  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 10:37:23.240  3443  3563 D PowerManagerService: mDisplayReady: true
09-21 10:37:23.240  3443  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-21 10:37:23.250  9956  9956 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-21 10:37:23.260  9956 10013 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 10:37:23.260  9956 10013 D libEGL  : eglInitialize EGLDisplay = 0xd9d6c3f4
,09-21 10:37:23.270  3443  3464 V WindowStateAnimator: Finishing drawing window Window{250362b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-21 10:37:23.270  9956  9956 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-21 10:37:23.270  3443  4246 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443
09-21 10:37:23.270  3443  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 10:37:23.270  3443  3443 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 10:37:23.270  3443  3559 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s109ms (total +1s584ms)
,09-21 10:37:23.280  3443  3559 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8084737 u0 com.test.thalitest/.MainActivity t9} time:257460
09-21 10:37:23.280  3443  3559 D ActivityManager: mDVFSHelper.release()
09-21 10:37:23.280  3443  3559 D ViewRootImpl: #3 mView = null
,09-21 10:37:23.280  3443  3443 I KnoxTimeoutHandler: SD activityfalse
,09-21 10:37:23.280  3007  3016 I SurfaceFlinger: id=32 Removed uhalitest (6/11)
,09-21 10:37:23.280  3007  3835 I SurfaceFlinger: id=32 Removed uhalitest (-2/11)
09-21 10:37:23.280  9956 10013 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-21 10:37:23.290  3443  4415 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443
,09-21 10:37:23.300  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc36d1338
,09-21 10:37:23.300  3443  4409 V WindowStateAnimator: Finishing drawing window Window{250362b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-21 10:37:23.300  9956  9956 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1581571 time:257487
,09-21 10:37:23.330  9956  9956 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9956
,09-21 10:37:23.390  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:23.440  3443  3443 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443 (0x0)
09-21 10:37:23.440  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable
,09-21 10:37:23.440  3443  3443 D PowerManagerService: mDisplayReady: false
09-21 10:37:23.440  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable done
,09-21 10:37:23.440  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 10:37:23.440  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f81d83c00
09-21 10:37:23.440  3443  3443 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 10:37:23.440  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-21 10:37:23.440  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 10:37:23.440  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:23.440  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:23.440  3443  3577 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-21 10:37:23.440  3443  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-21 10:37:23.440  3443  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-21 10:37:23.450  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 10:37:23.450  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 10:37:23.450  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 10:37:23.450  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:23.450  3443  3563 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 10:37:23.450  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:23.450  3443  3563 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 10:37:23.450  3443  3563 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 10:37:23.450  3443  3563 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 10:37:23.450  3443  3563 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 10:37:23.450  3443  3563 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 10:37:23.450  3443  3563 D PowerManagerService: mDisplayReady: true
09-21 10:37:23.450  3443  3563 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-21 10:37:23.560  9956  9956 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 10:37:23.570  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:23.660  9956 10020 D jxcore_app_log: JniHelper::setJavaVM(0xf4c34000), pthread_self() = -650118864
,09-21 10:37:23.660  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 10:37:23.660  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 10:37:23.660  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 10:37:23.660  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 10:37:23.660  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-21 10:37:23.660  9956 10020 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@927b93e added. We now have 1 listener(s)
,09-21 10:37:23.670  4024  4024 D Recents : onTaskStackChanged
,09-21 10:37:23.670  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
09-21 10:37:23.670  9956 10020 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,09-21 10:37:23.670  9956 10020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:37:23.670  9956 10020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 10:37:23.670  9956 10020 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f69a8b5 added. We now have 1 listener(s)
09-21 10:37:23.670  9956 10020 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:37:23.670  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 10:37:23.670  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 10:37:23.670  4024  4024 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-21 10:37:23.670  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 10:37:23.670  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 10:37:23.670  9956 10020 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-21 10:37:23.680  9956 10020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:37:23.680  9956 10020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-21 10:37:23.680  4024  4024 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 10:37:23.680  9956 10020 D BluetoothAdapter: STATE_ON
,09-21 10:37:23.690  9956 10020 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:37:23.690  9956 10020 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:37:23.690  9956 10020 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 10:37:23.690  9956 10020 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:37:23.690  9956 10020 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 10:37:23.700  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:37:23.700  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:37:23.730  9956  9956 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 10:37:23.750  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:23.930  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:24.060  9956 10021 W jxcore-log: Initializing JXcore engine
09-21 10:37:24.060  9956 10021 W jxcore-log: JXcore engine is ready
,09-21 10:37:24.080  4908  4908 E audit   : type=1400 msg=audit(1474447044.080:258): avc:  denied  { ioctl } for  pid=10021 comm="Thread-176" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3108 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 10:37:24.080  4908  4908 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 10:37:24.080  4908  4908 E audit   : type=1300 msg=audit(1474447044.080:258): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d808a3c8 items=0 ppid=3178 pid=10021 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-176" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 10:37:24.080  4908  4908 E audit   : type=1327 msg=audit(1474447044.080:258): proctitle="com.test.thalitest"
09-21 10:37:24.080  4908  4908 E audit   : type=1320 msg=audit(1474447044.080:258): 
09-21 10:37:24.080  4908  4908 E audit   : type=1400 msg=audit(1474447044.080:259): avc:  denied  { ioctl } for  pid=10021 comm="Thread-176" path="socket:[14189]" dev="sockfs" ino=14189 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 10:37:24.080  4908  4908 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 10:37:24.080  4908  4908 E audit   : type=1300 msg=audit(1474447044.080:259): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d808a3c8 items=0 ppid=3178 pid=10021 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-176" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 10:37:24.080  4908  4908 E audit   : type=1327 msg=audit(1474447044.080:259): proctitle="com.test.thalitest"
09-21 10:37:24.080  4908  4908 E audit   : type=1320 msg=audit(1474447044.080:259): 
,09-21 10:37:24.090  9956 10021 W jxcore-log: Starting JXcore engine
,09-21 10:37:24.110  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:24.120  9956 10021 W jxcore-log: Platform android
09-21 10:37:24.120  9956 10021 W jxcore-log: 
09-21 10:37:24.120  9956 10021 W jxcore-log: Process ARCH arm
09-21 10:37:24.120  9956 10021 W jxcore-log: 
,09-21 10:37:24.190  9956 10021 I jxcore-log: JXcore Cordova bridge is ready!
09-21 10:37:24.190  9956 10021 I jxcore-log: 
09-21 10:37:24.190  9956 10021 W jxcore-log: JXcore engine is started
,09-21 10:37:24.200  9956 10020 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 10:37:24.200  9956  9956 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 10:37:24.290  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:24.470  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:24.650  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:24.700  3443  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/9_task.xml.bak
,09-21 10:37:24.830  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:25.010  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:25.100  3443  5920 D SSRM:n  : SIOP:: AP = 300, PST = 285 (W:6), CP = 243, CUR = -103, LCD = 1
,09-21 10:37:25.180  3443  5920 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-21 10:37:25.190  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:25.370  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:25.550  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:25.730  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:25.910  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:26.090  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:26.270  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:26.450  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:26.630  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:26.810  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:26.990  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:27.170  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:27.350  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:27.530  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 10:37:27.710  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:27.890  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:28.070  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:28.250  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:28.260  3443  5920 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-21 10:37:28.430  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:28.610  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:28.790  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:28.970  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:29.150  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:29.330  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:29.510  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:29.690  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:29.870  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:30.050  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:30.180  9532  9557 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-21 10:37:30.230  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:30.340  9956 10021 I jxcore-log: 2016-09-21 08:37:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-21 10:37:30.340  9956 10021 I jxcore-log: 
,09-21 10:37:30.340  9956 10021 I jxcore-log: 2016-09-21 08:37:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-21 10:37:30.340  9956 10021 I jxcore-log: 
,09-21 10:37:30.350  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:37:30.350  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 10:37:30.350  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.360  9956 10021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 10:37:30.360  9956 10021 I jxcore-log: 2016-09-21 08:37:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-21 10:37:30.360  9956 10021 I jxcore-log: 
09-21 10:37:30.360  9956 10021 I jxcore-log: 2016-09-21 08:37:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-21 10:37:30.360  9956 10021 I jxcore-log: 
,09-21 10:37:30.410  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:30.510  9956 10021 I jxcore-log: Running unit tests
09-21 10:37:30.510  9956 10021 I jxcore-log: 
,09-21 10:37:30.510  9956 10021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:37:30.510  9956 10021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ece0a39 added. We now have 2 listener(s)
09-21 10:37:30.510  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 10:37:30.510  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:37:30.510  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 10:37:30.510  9956 10021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:37:30.510  9956 10021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ede87e added. We now have 2 listener(s)
09-21 10:37:30.510  9956 10021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:37:30.520  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:37:30.520  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:37:30.530  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:37:30.530  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 10:37:30.540  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.540  9956 10021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 10:37:30.540  9956 10021 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:37:30.540  9956 10021 D executeNativeTests: Running unit tests
,09-21 10:37:30.550  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:37:30.550  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:37:30.580  9956 10021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 10:37:30.580  9956 10021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad8a5c added. We now have 3 listener(s)
09-21 10:37:30.580  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,09-21 10:37:30.580  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:37:30.580  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:37:30.580  9956 10021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:37:30.580  9956 10021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 added. We now have 3 listener(s)
09-21 10:37:30.580  9956 10021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:37:30.580  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:37:30.590  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:30.590  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:37:30.600  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:37:30.600  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 10:37:30.600  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.610  9956 10021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:37:30.610  9956 10021 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-21 10:37:30.610  9956 10021 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-21 10:37:30.610  9956 10021 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 10:37:30.610  9956 10021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:37:30.610  9956 10021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:37:30.610  9956 10021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 10:37:30.610  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:30.610  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad8a5c removed from the list
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:37:30.610  9956 10021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 removed from the list
09-21 10:37:30.610  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:37:30.610  9956 10021 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:37:30.610  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 10:37:30.610  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:30.610  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:37:30.610  9956 10021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 not in the list
09-21 10:37:30.610  9956 10021 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-21 10:37:30.610  9956 10021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 10:37:30.610  9956 10021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:37:30.610  9956 10021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:37:30.610  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 10:37:30.610  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:37:30.610  9956 10021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad8a5c not in the list
09-21 10:37:30.610  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:37:30.620  9956 10021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 not in the list
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:37:30.620  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:30.620  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:37:30.620  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:30.620  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:37:30.620  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:37:30.620  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:37:30.620  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:37:30.620  9956 10021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 not in the list
,09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 10:37:30.620  9956 10021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:37:30.620  9956 10021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:37:30.620  9956 10021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:37:30.620  9956 10021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 10:37:30.620  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:30.620  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:37:30.620  9956 10021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad8a5c not in the list
09-21 10:37:30.620  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:37:30.620  9956 10021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 not in the list
09-21 10:37:30.620  9956 10021 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:37:30.620  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:30.620  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:37:30.620  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:30.620  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:37:30.630  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:37:30.630  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:37:30.630  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:37:30.630  9956 10021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 not in the list
09-21 10:37:30.630  9956 10021 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 10:37:30.630  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:37:30.640  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:37:30.640  9956 10021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:37:30.640  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.650  9956 10021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:37:30.650  9956 10021 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:37:30.650  9956 10021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:37:30.650  9956 10021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 10:37:30.650  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 10:37:30.650  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:37:30.650  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:37:30.650  9956 10021 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 10:37:30.650  9956 10021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 10:37:30.650  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:37:30.660  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.660  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.660  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.660  9956  9956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:37:30.670  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 10:37:30.670  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.670  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.670  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 10:37:30.670  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 10:37:30.680  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.680  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.680  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-21 10:37:30.690  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.690  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.690  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-21 10:37:30.690  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 10:37:30.690  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 10:37:30.690  9956 10021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 10:37:30.690  9956 10021 D BluetoothLeScanner: Start Scan
09-21 10:37:30.690  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.700  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.700  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:30.700  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.710  4900  4913 D BtGatt.GattService: registerClient() - UUID=e2f6625c-bdda-46da-8b3b-8b6aeeaa6806
,09-21 10:37:30.760  4900  5025 D BtGatt.GattService: onClientRegistered() - UUID=e2f6625c-bdda-46da-8b3b-8b6aeeaa6806, clientIf=7
,09-21 10:37:30.760  9956  9967 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-21 10:37:30.760  4900  4914 D BtGatt.GattService: start scan with filters
,09-21 10:37:30.770  4900  4914 D BtGatt.GattService: getScanSettings
,09-21 10:37:30.770  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:30.790  4900  4914 D BtGatt.GattService: Is it foreground application = true
,09-21 10:37:30.790  4900  4914 D BtGatt.GattService: not a background application
,09-21 10:37:30.800  4900  4914 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-21 10:37:30.810  4900  4914 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 10:37:30.810  4900  4914 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 10:37:30.810  4900  5065 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-21 10:37:30.810  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 10:37:30.810  4900  5065 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
,09-21 10:37:30.810  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-21 10:37:30.810  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 10:37:30.810  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 10:37:30.810  4900  5056 D BtGatt.ScanManager: handling starting scan
09-21 10:37:30.810  4900  5056 D BtGatt.ScanManager: isFilteringSupported
09-21 10:37:30.810  4900  5056 D BluetoothAdapter: enableStandAloneBleMode=
,09-21 10:37:30.810  4900  5056 D BluetoothAdapter: STATE_ON
09-21 10:37:30.820  4900  5056 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.820  4900  5056 D BluetoothAdapter: STATE_ON
,09-21 10:37:30.820  4900  5056 D BluetoothAdapter: STATE_ON
09-21 10:37:30.820  9956 10021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 10:37:30.830  9956 10021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-21 10:37:30.830  9956  9956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:37:30.830  4900  5056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc07ae2
09-21 10:37:30.830  4900  5065 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 7
09-21 10:37:30.830  4900  5065 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-21 10:37:30.830  3443  4312 V AlarmManager:  remove PendingIntent] PendingIntent{5d43d0: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
09-21 10:37:30.830  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 10:37:30.840  4900  5025 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-21 10:37:30.840  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 7
,09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574117
09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 10:37:30.840  3443  3978 V AlarmManager:  remove PendingIntent] PendingIntent{53f6fc9: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 10:37:30.840  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 10:37:30.850  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 10:37:30.850  4900  5065 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 10:37:30.850  4900  5065 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 10:37:30.850  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 10:37:30.850  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 10:37:30.850  4900  5065 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574117
09-21 10:37:30.850  4900  5056 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
,09-21 10:37:30.850  4900  5056 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-21 10:37:30.850  4900  5056 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-21 10:37:30.850  4900  5056 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-21 10:37:30.850  9956 10021 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 10:37:30.850  3443  3466 V AlarmManager:  remove PendingIntent] PendingIntent{e8806ce: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.850  4900  5025 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-21 10:37:30.850  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:30.850  4900  5056 D BtGatt.ScanManager: Starting BLE batch scan
09-21 10:37:30.850  4900  5056 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-21 10:37:30.860  3443  4326 V AlarmManager:  remove PendingIntent] PendingIntent{351d9ef: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
09-21 10:37:30.860  4900  5025 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-21 10:37:30.860  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:30.860  4900  5025 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-21 10:37:30.860  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:30.860  3443  4312 V AlarmManager:  remove PendingIntent] PendingIntent{81accfc: PendingIntentRecord{4c63f85 com.android.bluetooth broadcastIntent}}
09-21 10:37:30.860  3443  4390 V AlarmManager:  remove PendingIntent] PendingIntent{5a1c1da: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.870  3443  4378 V AlarmManager:  remove PendingIntent] PendingIntent{78c260b: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.870  3443  4963 V AlarmManager:  remove PendingIntent] PendingIntent{1c5bce8: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.880  3443  4246 V AlarmManager:  remove PendingIntent] PendingIntent{4304f01: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.880  3443  3980 V AlarmManager:  remove PendingIntent] PendingIntent{c6a21a6: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.890  3443  4390 V AlarmManager:  remove PendingIntent] PendingIntent{bd517e7: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.890  3443  4933 V AlarmManager:  remove PendingIntent] PendingIntent{aadbf94: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.900  3443  3978 V AlarmManager:  remove PendingIntent] PendingIntent{cd1da3d: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.900  3443  3466 V AlarmManager:  remove PendingIntent] PendingIntent{e06b232: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:30.950  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:31.130  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:31.310  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:31.330  9956  9956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-21 10:37:31.330  9956  9956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:37:31.330  9956  9956 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-21 10:37:31.490  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:31.670  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:31.740  3443  3582 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-21 10:37:31.760  3443  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-21 10:37:31.850  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:31.860  3443  3819 V AlarmManager: Expired Alarm result :4
,09-21 10:37:31.870  4900  4900 D BtGatt.ScanManager: awakened up at time 266054
,09-21 10:37:31.870  4900  5056 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 10:37:31.880  3443  4312 V AlarmManager:  remove PendingIntent] PendingIntent{3714100: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:31.880  4900  5025 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
09-21 10:37:31.880  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:31.880  4900  5025 D BtGatt.GattService: current time is 266065323232
09-21 10:37:31.880  4900  5025 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-21 10:37:31.880  3443  3464 V AlarmManager:  remove PendingIntent] PendingIntent{f06dd39: PendingIntentRecord{4c63f85 com.android.bluetooth broadcastIntent}}
09-21 10:37:31.880  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-21 10:37:31.880  4900  5025 D ScanRecord: parseFromBytes
,09-21 10:37:31.880  4900  5025 D ScanRecord: first manudata for manu ID
09-21 10:37:31.890  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 10:37:31.890  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:31.890  4900  5025 D ScanRecord: first manudata for manu ID
,09-21 10:37:31.890  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-21 10:37:31.890  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:31.890  4900  5025 D ScanRecord: first manudata for manu ID
09-21 10:37:31.890  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-21 10:37:31.890  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:31.890  4900  5025 D ScanRecord: first manudata for manu ID
09-21 10:37:31.890  9956  9966 D ScanRecord: parseFromBytes
,09-21 10:37:31.890  9956  9966 D ScanRecord: first manudata for manu ID
,09-21 10:37:31.890  9956  9966 D ScanRecord: parseFromBytes
,09-21 10:37:31.890  9956  9966 D ScanRecord: first manudata for manu ID
09-21 10:37:31.890  9956  9966 D ScanRecord: parseFromBytes
09-21 10:37:31.890  9956  9966 D ScanRecord: first manudata for manu ID
,09-21 10:37:31.890  9956  9966 D ScanRecord: parseFromBytes
09-21 10:37:31.890  9956  9966 D ScanRecord: first manudata for manu ID
,09-21 10:37:31.900  3443  4378 V AlarmManager:  remove PendingIntent] PendingIntent{69bf7e: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:31.910  3443  4963 V AlarmManager:  remove PendingIntent] PendingIntent{ed31cdf: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:31.910  3443  4246 V AlarmManager:  remove PendingIntent] PendingIntent{6296d2c: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:31.920  3443  3980 V AlarmManager:  remove PendingIntent] PendingIntent{aef13f5: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:31.920  3443  4326 V AlarmManager:  remove PendingIntent] PendingIntent{45e558a: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:32.030  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:32.210  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:32.390  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:32.570  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:32.750  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:32.880  3443  3819 V AlarmManager: Expired Alarm result :4
,09-21 10:37:32.890  4900  4900 D BtGatt.ScanManager: awakened up at time 267072
,09-21 10:37:32.890  4900  5056 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 10:37:32.890  3443  3978 V AlarmManager:  remove PendingIntent] PendingIntent{3563018: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:32.900  4900  5025 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
09-21 10:37:32.900  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:32.900  4900  5025 D BtGatt.GattService: current time is 267088267077
,09-21 10:37:32.900  4900  5025 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
09-21 10:37:32.900  3443  4409 V AlarmManager:  remove PendingIntent] PendingIntent{8e9fa71: PendingIntentRecord{4c63f85 com.android.bluetooth broadcastIntent}}
09-21 10:37:32.900  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-21 10:37:32.900  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:32.900  4900  5025 D ScanRecord: first manudata for manu ID
,09-21 10:37:32.910  9956  9967 D ScanRecord: parseFromBytes
09-21 10:37:32.910  9956  9967 D ScanRecord: first manudata for manu ID
,09-21 10:37:32.910  3443  4408 V AlarmManager:  remove PendingIntent] PendingIntent{a544056: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:32.920  3443  4312 V AlarmManager:  remove PendingIntent] PendingIntent{9fdc8d7: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:32.920  3443  4390 V AlarmManager:  remove PendingIntent] PendingIntent{18a35c4: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:32.930  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:32.930  3443  3978 V AlarmManager:  remove PendingIntent] PendingIntent{dd2ccad: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:32.940  3443  4933 V AlarmManager:  remove PendingIntent] PendingIntent{7ec0be2: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:33.110  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:33.180  3443  4246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-21 10:37:33.180  3443  4246 D BatteryService: level:100, scale:100, status:3, health:9, present:true, voltage: 4298, temperature: 272, technology: Li-ion, AC powered:false, USB powered:false, POGO powered:false, Wireless powered:false, icon:17303399, invalid charger:0, maxChargingCurrent:0
09-21 10:37:33.180  3443  4246 D BatteryService: online:4, current avg:-356, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-74
09-21 10:37:33.180  3443  3443 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-21 10:37:33.190  3443  3443 I MotionRecognitionService: On Battery, 0
09-21 10:37:33.190  3443  3443 D MotionRecognitionService:   cableConnection= 0
,09-21 10:37:33.190  3443  3865 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-21 10:37:33.190  3951  3951 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-21 10:37:33.200  3951  3951 D PowerUI : priorPlugType = 0 mPlugType =  0
09-21 10:37:33.200  3951  3951 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-21 10:37:33.210  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,09-21 10:37:33.210  4946  4946 D CommonServiceConfiguration: getStringValueSetting
,09-21 10:37:33.220  4900  4900 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-21 10:37:33.220  4900  5316 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-21 10:37:33.220  4946  4946 D BatteryMonitor: new battery level: 100
,09-21 10:37:33.230  4732  4732 D BatteryController: saveBatteryData : level[100], status[3]
,09-21 10:37:33.250  3951  3951 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,09-21 10:37:33.290  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:33.470  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:33.650  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:33.830  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:33.900  3443  5955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-21 10:37:33.910  3443  3819 V AlarmManager: Expired Alarm result :4
,09-21 10:37:33.910  4900  4900 D BtGatt.ScanManager: awakened up at time 268098
,09-21 10:37:33.910  4900  5056 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 10:37:33.920  4900  5025 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-21 10:37:33.920  3443  3466 V AlarmManager:  remove PendingIntent] PendingIntent{bd6ea30: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:33.920  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:33.920  3443  4246 V AlarmManager:  remove PendingIntent] PendingIntent{6fc86a9: PendingIntentRecord{4c63f85 com.android.bluetooth broadcastIntent}}
,09-21 10:37:33.940  3443  4326 V AlarmManager:  remove PendingIntent] PendingIntent{a43042e: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:33.950  3443  4390 V AlarmManager:  remove PendingIntent] PendingIntent{362fbcf: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:34.010  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:34.190  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:34.380  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:34.550  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:34.730  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:34.910  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:34.920  3443  3819 V AlarmManager: Expired Alarm result :4
,09-21 10:37:34.930  4900  4900 D BtGatt.ScanManager: awakened up at time 269113
,09-21 10:37:34.930  4900  5056 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 10:37:34.930  3443  4312 V AlarmManager:  remove PendingIntent] PendingIntent{9ede465: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:34.940  4900  5025 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-21 10:37:34.940  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:34.940  4900  5025 D BtGatt.GattService: current time is 269122921922
09-21 10:37:34.940  4900  5025 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 107, 58, 19, -9, 93, -60, 1, 0, -96, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 81, 34, 97, 112, -14, -5, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-21 10:37:34.940  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-21 10:37:34.940  4900  5025 D ScanRecord: parseFromBytes
,09-21 10:37:34.940  4900  5025 D ScanRecord: first manudata for manu ID
09-21 10:37:34.940  4900  5025 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-21 10:37:34.940  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:34.940  4900  5025 D ScanRecord: first manudata for manu ID
09-21 10:37:34.940  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-21 10:37:34.940  3443  4246 V AlarmManager:  remove PendingIntent] PendingIntent{ff353a: PendingIntentRecord{4c63f85 com.android.bluetooth broadcastIntent}}
09-21 10:37:34.940  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:34.940  4900  5025 D ScanRecord: first manudata for manu ID
,09-21 10:37:34.940  9956  9967 D ScanRecord: parseFromBytes
09-21 10:37:34.940  9956  9967 D ScanRecord: first manudata for manu ID
09-21 10:37:34.940  9956  9967 D ScanRecord: parseFromBytes
09-21 10:37:34.940  9956  9967 D ScanRecord: first manudata for manu ID
,09-21 10:37:34.940  9956  9967 D ScanRecord: parseFromBytes
09-21 10:37:34.940  9956  9967 D ScanRecord: first manudata for manu ID
,09-21 10:37:34.960  3443  3982 V AlarmManager:  remove PendingIntent] PendingIntent{3bd85eb: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:34.970  3443  3464 V AlarmManager:  remove PendingIntent] PendingIntent{541cf48: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:34.970  3443  4378 V AlarmManager:  remove PendingIntent] PendingIntent{3dd61e1: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:34.980  3443  4963 V AlarmManager:  remove PendingIntent] PendingIntent{e1b6b06: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:34.980  3443  4415 V AlarmManager:  remove PendingIntent] PendingIntent{8ec95c7: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.090  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:35.120  3443  5920 D SSRM:n  : SIOP:: AP = 320, PST = 290 (W:6), CP = 253, CUR = -356, LCD = 1
,09-21 10:37:35.270  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:35.450  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:35.630  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:35.810  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:35.860  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:35.870  9956 10021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 10:37:35.870  9956 10021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 10:37:35.870  9956 10021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 10:37:35.870  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:35.870  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 10:37:35.870  9956 10021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 10:37:35.870  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:37:35.870  9956 10021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 10:37:35.870  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-21 10:37:35.870  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 10:37:35.870  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-21 10:37:35.880  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:35.880  9956 10021 D BluetoothAdapter: STATE_ON
,09-21 10:37:35.880  9956 10021 D BluetoothLeScanner: Stop Scan
,09-21 10:37:35.890  4900  4913 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 10:37:35.890  4900  4913 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 10:37:35.890  4900  4913 D BtGatt.GattService: stopScan() - queue size =1
09-21 10:37:35.890  4900  5065 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-21 10:37:35.890  4900  5065 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
,09-21 10:37:35.890  4900  5065 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 10:37:35.890  4900  5056 D BtGatt.ScanManager: filter size is 1
09-21 10:37:35.890  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 10:37:35.900  4900  5056 D BtGatt.ScanManager: delete FilterIndex - 3
,09-21 10:37:35.900  4900  5065 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 10:37:35.900  4900  5065 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-21 10:37:35.900  4900  5065 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-21 10:37:35.900  4900  5025 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-21 10:37:35.900  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 10:37:35.900  4900  4914 D BtGatt.GattService: unregisterClient() - clientIf=7
09-21 10:37:35.900  4900  5056 D BtGatt.ScanManager: stopping BLe Batch
09-21 10:37:35.900  3443  4415 V AlarmManager:  remove PendingIntent] PendingIntent{14897f4: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.900  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-21 10:37:35.900  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 10:37:35.900  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 10:37:35.900  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-21 10:37:35.900  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 10:37:35.900  4900  5025 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-21 10:37:35.900  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:35.910  4900  5056 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 10:37:35.910  4900  5025 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-21 10:37:35.910  3443  4081 V AlarmManager:  remove PendingIntent] PendingIntent{4ed3b1d: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
09-21 10:37:35.910  9956 10021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 10:37:35.920  3443  4390 V AlarmManager:  remove PendingIntent] PendingIntent{6733192: PendingIntentRecord{4c63f85 com.android.bluetooth broadcastIntent}}
09-21 10:37:35.910  4900  5025 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 10:37:35.910  4900  5025 D BtGatt.GattService: current time is 270099012229
09-21 10:37:35.910  4900  5025 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -96, 10, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 35, 97, 126, -92, 22, -56, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-21 10:37:35.910  4900  5025 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-21 10:37:35.920  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:35.920  4900  5025 D ScanRecord: first manudata for manu ID
09-21 10:37:35.920  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-21 10:37:35.920  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:35.920  4900  5025 D ScanRecord: first manudata for manu ID
,09-21 10:37:35.920  4900  5025 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 10:37:35.920  4900  5025 D ScanRecord: parseFromBytes
09-21 10:37:35.920  4900  5025 D ScanRecord: first manudata for manu ID
09-21 10:37:35.920  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:35.920  3443  4312 V AlarmManager:  remove PendingIntent] PendingIntent{112c763: PendingIntentRecord{4c63f85 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.920  9956 10021 D BluetoothAdapter: STATE_ON
09-21 10:37:35.920  9956 10021 D BluetoothLeAdvertiser: stop advertising
09-21 10:37:35.930  9956 10021 D BluetoothLeAdvertiser: wrapper is null
09-21 10:37:35.930  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-21 10:37:35.930  9956 10021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 10:37:35.930  9956 10021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 10:37:35.930  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 10:37:35.930  9956 10021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 10:37:35.930  9956  9956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:37:35.930  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:37:35.930  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:37:35.930  9956 10021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:37:35.930  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 10:37:35.930  9956 10021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad8a5c not in the list
09-21 10:37:35.930  9956 10021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:37:35.930  9956 10021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3342165 not in the list
,09-21 10:37:35.930  9956 10021 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:37:35.930  9956 10021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 10:37:35.930  3443  4933 V AlarmManager:  remove PendingIntent] PendingIntent{fe076bf: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.940  9956  9956 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 10:37:35.940  9956  9956 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 10:37:35.940  3443  4409 V AlarmManager:  remove PendingIntent] PendingIntent{d7af18c: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.940  9956  9956 D BluetoothAdapter: STATE_ON
,09-21 10:37:35.950  9956  9956 D BluetoothAdapter: STATE_ON
,09-21 10:37:35.950  9956  9956 D BluetoothAdapter: STATE_ON
,09-21 10:37:35.950  3443  3978 V AlarmManager:  remove PendingIntent] PendingIntent{139b0d5: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.950  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 10:37:35.950  9956  9956 D BluetoothAdapter: STATE_ON
,09-21 10:37:35.950  9956  9956 D BluetoothAdapter: STATE_ON
09-21 10:37:35.950  9956  9956 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-21 10:37:35.950  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 10:37:35.950  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 10:37:35.950  3443  4409 V AlarmManager:  remove PendingIntent] PendingIntent{32f60ea: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.960  9956  9956 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 10:37:35.960  9956  9956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 10:37:35.960  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:37:35.960  3443  4415 V AlarmManager:  remove PendingIntent] PendingIntent{9afbfdb: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
09-21 10:37:35.960  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 10:37:35.970  9956  9956 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 10:37:35.970  9956  9956 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 10:37:35.970  9956  9956 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:37:35.970  3443  4081 V AlarmManager:  remove PendingIntent] PendingIntent{4607eb7: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.970  9956  9956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 10:37:35.980  3443  3466 V AlarmManager:  remove PendingIntent] PendingIntent{c3be624: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.980  3443  4246 V AlarmManager:  remove PendingIntent] PendingIntent{978258d: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.990  3443  4933 V AlarmManager:  remove PendingIntent] PendingIntent{ba72342: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:35.990  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:35.990  3443  3982 V AlarmManager:  remove PendingIntent] PendingIntent{9f44f53: PendingIntentRecord{9da3c36 com.android.bluetooth broadcastIntent}}
,09-21 10:37:36.170  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:36.350  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:36.480  9956  9956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 10:37:36.530  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:36.710  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:36.890  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:37.070  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 10:37:37.250  3443  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
