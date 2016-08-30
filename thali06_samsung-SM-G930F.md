#### Test 83243049e1001da_thali06_samsung-SM-G930F Logs


```
--------- beginning of main
08-30 12:40:41.307  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:41.487  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:41.657  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:41.837  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:41.897  9119  9119 I FIPS_bssl: FIPS approved mode (1) | 9119 | app_process
08-30 12:40:41.897  9119  9119 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 12:40:41.897  9119  9119 D AndroidRuntime: CheckJNI is OFF
08-30 12:40:41.897  9119  9119 D AndroidRuntime: readGMSProperty: start
08-30 12:40:41.907  9119  9119 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:40:41.907  9119  9119 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:40:41.907  9119  9119 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:40:41.907  9119  9119 D AndroidRuntime: readGMSProperty: end
08-30 12:40:41.907  9119  9119 D AndroidRuntime: addProductProperty: start
08-30 12:40:41.917  9119  9119 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 12:40:41.947  9119  9119 I Radio-JNI: register_android_hardware_Radio DONE
08-30 12:40:41.947  9119  9119 E AffinityControl: AffinityControl: registerfunction enter
08-30 12:40:41.957  9119  9119 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 12:40:41.987  3403  3962 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
08-30 12:40:41.987  3403  3962 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
08-30 12:40:42.007  3403  3962 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:40:42.007  3403  3962 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 12:40:42.007  3403  3962 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-30 12:40:42.017  3403  3962 D ActivityManager: mDVFSHelper.acquire()
08-30 12:40:42.017  3403  3962 V WindowManager: addAppToken: AppWindowToken{d08fc65a3 token=Token{62360d2 ActivityRecord{60f9f5d u0 com.test.thalitest/.MainActivity t17}}} to stack=2 task=17 at 0
08-30 12:40:42.017  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:42.017  3403  3530 I InjectionManager: Inside getClassLibPath caller 
08-30 12:40:42.027  3403  3530 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 12:40:42.027  3403  3530 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ce6e61b V.E...... R.....ID 0,0-0,0}
08-30 12:40:42.037  3403  3530 W WindowManager: Failed looking up window
08-30 12:40:42.037  3403  3530 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@c4e63b8 does not exist
08-30 12:40:42.037  3403  3530 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:40:42.037  3403  3530 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:40:42.037  9128  9128 E Zygote  : v2
08-30 12:40:42.037  9128  9128 I libpersona: KNOX_SDCARD checking this for 10170
08-30 12:40:42.037  3403  3530 D ISSUE_DEBUG: InputChannelName : 812b591 Starting com.test.thalitest
08-30 12:40:42.037  9128  9128 I libpersona: KNOX_SDCARD not a persona
08-30 12:40:42.037  9128  9128 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0012
08-30 12:40:42.037  9128  9128 E Zygote  : accessInfo : 0
08-30 12:40:42.037  3403  3962 I ActivityManager: Start proc 9128:com.test.thalitest/u0a170 for activity com.test.thalitest/.MainActivity
08-30 12:40:42.037  9128  9128 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 12:40:42.037  2992  2992 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-30 12:40:42.057  5903  5903 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 12:40:42.067  3403  3962 D InputDispatcher: Focused application set to: xxxx
08-30 12:40:42.067  5903  5903 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 12:40:42.067  3403  4435 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3403
08-30 12:40:42.067  3403  4435 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 12:40:42.067  3403  4435 D PowerManagerService: mDisplayReady: false
08-30 12:40:42.067  3403  4435 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 12:40:42.067  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:40:42.067  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:40:42.067  3403  4435 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 12:40:42.067  3403  3530 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 12:40:42.067  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:42.067  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:42.067  3403  3530 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-30 12:40:42.067  3403  3549 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
08-30 12:40:42.067  3403  3403 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 12:40:42.067  3403  3844 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 12:40:42.067  3403  3530 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
08-30 12:40:42.067  9119  9119 D AndroidRuntime: Shutting down VM
08-30 12:40:42.067  3403  3530 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
08-30 12:40:42.067  2992  2992 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa01c3c00
08-30 12:40:42.067  2992  2992 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
08-30 12:40:42.087  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:40:42.087  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 12:40:42.087  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:40:42.087  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 12:40:42.087  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:42.087  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:42.087  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:40:42.087  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:40:42.087  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:42.087  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:42.087  3403  3535 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 12:40:42.087  3403  3535 D PowerManagerService: mDisplayReady: true
08-30 12:40:42.087  3403  3535 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
08-30 12:40:42.097  3403  3403 I KnoxTimeoutHandler: SD activityfalse
08-30 12:40:42.097  3403  4703 V WindowStateAnimator: Finishing drawing window Window{84125e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-30 12:40:42.097  3403  3444 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3403
08-30 12:40:42.097  9128  9128 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:40:42.097  9128  9128 D ActivityThread: Added TimaKeyStore provider
08-30 12:40:42.107  2992  2992 D libEGL  : eglInitialize EGLDisplay = 0x7fe659f108
08-30 12:40:42.107  3403  3963 V WindowStateAnimator: Finishing drawing window Window{27de0e0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-30 12:40:42.117  5903  5903 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 12:40:42.117  5903  5903 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 12:40:42.127  3403  3530 V WindowStateAnimator: Finishing drawing window Window{812b591 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 12:40:42.127  3403  4354 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 12:40:42.127  2992  2992 D libEGL  : eglInitialize EGLDisplay = 0x7fe659f108
08-30 12:40:42.127  6386  6386 V ActivityThread: updateVisibility : ActivityRecord{171e19a token=android.os.BinderProxy@fde8c93 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-30 12:40:42.137  3403  4567 V WindowStateAnimator: Finishing drawing window Window{27de0e0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=READY_TO_SHOW
08-30 12:40:42.137  3403  3962 V WindowStateAnimator: Finishing drawing window Window{84125e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=READY_TO_SHOW
08-30 12:40:42.137  5903  5903 V ActivityThread: updateVisibility : ActivityRecord{a9300cf token=android.os.BinderProxy@3f74d99 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-30 12:40:42.137  3403  3403 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-30 12:40:42.137  3403  3504 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-30 12:40:42.147  2992  4501 D libEGL  : eglTerminate EGLDisplay = 0x7f982ffe78
08-30 12:40:42.147  2992  4501 D libEGL  : eglTerminate EGLDisplay = 0x7f982ffe78
08-30 12:40:42.157  2992  4501 I SurfaceFlinger: id=17 Removed YUIInstallC (5/14)
08-30 12:40:42.157  2992  3001 I SurfaceFlinger: id=17 Removed YUIInstallC (-2/14)
08-30 12:40:42.167  2992  4501 I SurfaceFlinger: id=19 Removed VSBConnecti (8/13)
08-30 12:40:42.167  2992  3003 D libEGL  : eglTerminate EGLDisplay = 0x7f9fcbee78
08-30 12:40:42.167  2992  3003 D libEGL  : eglTerminate EGLDisplay = 0x7f9fcbee78
08-30 12:40:42.167  2992  3001 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/13)
08-30 12:40:42.167  2992  2992 D libEGL  : eglTerminate EGLDisplay = 0x7fe659f228
08-30 12:40:42.167  2992  4152 I SurfaceFlinger: id=9 Removed MauncherAct (3/12)
08-30 12:40:42.177  2992  3057 I SurfaceFlinger: id=9 Removed MauncherAct (-2/12)
08-30 12:40:42.177  2992  4501 I SurfaceFlinger: id=20 Removed VSBConnecti (4/11)
08-30 12:40:42.177  2992  3057 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/11)
08-30 12:40:42.187  4255  4255 V ActivityThread: updateVisibility : ActivityRecord{6efc5b6 token=android.os.BinderProxy@384955b {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
08-30 12:40:42.187  4255  4255 D Launcher: onTrimMemory. Level: 20
08-30 12:40:42.197  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:42.207  2992  2992 D libEGL  : eglTerminate EGLDisplay = 0x7fe659f228
08-30 12:40:42.207  2992  2992 D libEGL  : eglTerminate EGLDisplay = 0x7fe659f228
08-30 12:40:42.247  3403  3403 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3403 (0x0)
08-30 12:40:42.247  3403  3403 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 12:40:42.247  3403  3403 D PowerManagerService: mDisplayReady: false
08-30 12:40:42.247  3403  3403 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 12:40:42.247  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:40:42.247  3403  3403 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 12:40:42.247  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:40:42.247  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:42.247  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:42.247  3403  3549 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-30 12:40:42.257  2992  2992 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa01c3c00
08-30 12:40:42.257  2992  2992 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-30 12:40:42.257  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:40:42.257  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:40:42.257  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 12:40:42.257  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:42.257  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 12:40:42.257  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:42.257  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:40:42.257  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:40:42.257  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:42.257  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:42.257  3403  3535 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 12:40:42.257  3403  3535 D PowerManagerService: mDisplayReady: true
08-30 12:40:42.257  3403  3535 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 12:40:42.377  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:42.467  3403  4354 I WindowManager: Screenshot max retries 4 of Token{62360d2 ActivityRecord{60f9f5d u0 com.test.thalitest/.MainActivity t17}} appWin=Window{812b591 u0 d0 Starting com.test.thalitest} drawState=4
08-30 12:40:42.477  3403  3530 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 12:40:42.477  3403  3403 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 12:40:42.477  3403  3530 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-30 12:40:42.487  3403  3403 I KnoxTimeoutHandler: SD activityfalse
08-30 12:40:42.477  3403  3530 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
08-30 12:40:42.487  3403  3844 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-30 12:40:42.517  9128  9128 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 12:40:42.527  3403  4706 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 12:40:42.527  9128  9128 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 12:40:42.537  3403  5809 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 12:40:42.537  9128  9128 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:40:42.547  3403  5809 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 12:40:42.547  9128  9128 I InjectionManager: Inside getClassLibPath caller 
08-30 12:40:42.557  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:42.567  9128  9128 D InjectionManager: InjectionManager
08-30 12:40:42.567  9128  9128 D InjectionManager: fillFeatureStoreMap com.test.thalitest
08-30 12:40:42.567  9128  9128 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
08-30 12:40:42.567  9128  9128 I InjectionManager: featureStore :{}
08-30 12:40:42.567  9128  9128 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 12:40:42.577  9128  9128 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 12:40:42.577  9128  9128 D RelationGraph: garbageCollect()
08-30 12:40:42.577  9128  9128 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 12:40:42.607  9128  9128 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410650)
08-30 12:40:42.637  9128  9128 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
08-30 12:40:42.637  9128  9128 D ResourcesManager: For user 0 new overlays fetched Null
08-30 12:40:42.637  9128  9128 I InjectionManager: Inside getClassLibPath caller 
08-30 12:40:42.637  9128  9128 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 12:40:42.677  9128  9128 I cr_LibraryLoader: Time to load native libraries: 21 ms (timestamps 7160-7181)
08-30 12:40:42.677  9128  9128 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-30 12:40:42.687  9128  9144 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-30 12:40:42.697  9128  9128 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8e31ab0}
08-30 12:40:42.697  9128  9128 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-30 12:40:42.707  9128  9128 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:40:42.717  9128  9128 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
08-30 12:40:42.727  3403  3867 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
08-30 12:40:42.737  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:42.837  3403  3867 I MdnieScenarioControlService: mGameModeLauncher : false
08-30 12:40:42.837  3403  3867 I MdnieScenarioControlService: setUIMode
08-30 12:40:42.917  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:42.947  9128  9128 D libEGL  : eglInitialize EGLDisplay = 0xffd3e6ec
08-30 12:40:42.957  9128  9128 D         : ro.exynos.dss isEnabled: 0
08-30 12:40:42.977  3403  3504 W ActivityManager: Activity pause timeout for ActivityRecord{60f9f5d u0 com.test.thalitest/.MainActivity t17}
08-30 12:40:43.017  3403  4703 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10170
08-30 12:40:43.017  3403  4703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29713 com.android.server.am.ActivityManagerService.registerReceiver:22578 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3988 
08-30 12:40:43.097  9128  9128 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
08-30 12:40:43.097  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:43.107  9128  9128 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 12:40:43.107  9128  9128 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-30 12:40:43.107  9128  9128 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
08-30 12:40:43.117  9128  9128 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
08-30 12:40:43.127  9128  9128 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
08-30 12:40:43.137  9128  9128 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 12:40:43.187  9128  9128 D Activity: performCreate Call Injection manager
,08-30 12:40:43.187  9128  9128 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,08-30 12:40:43.197  9128  9128 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-30 12:40:43.197  9128  9128 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{11b7409 I.E...... R.....ID 0,0-0,0}
,08-30 12:40:43.197  9128  9181 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 12:40:43.207  3403  4207 W WindowManager: Failed looking up window
08-30 12:40:43.207  3403  4207 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@1a209f5 does not exist
08-30 12:40:43.207  3403  4207 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 12:40:43.207  3403  4207 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 12:40:43.207  3403  4207 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 12:40:43.207  3403  4207 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-30 12:40:43.207  3403  4207 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-30 12:40:43.207  3403  4207 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 12:40:43.207  3403  4267 D ISSUE_DEBUG: InputChannelName : 985138a com.test.thalitest/com.test.thalitest.MainActivity
,08-30 12:40:43.207  3403  4567 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-30 12:40:43.207  3403  4567 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:40:43.207  3403  3403 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 12:40:43.217  3403  3403 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-30 12:40:43.217  9128  9128 V ActivityThread: updateVisibility : ActivityRecord{b9e182f token=android.os.BinderProxy@e954357 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 12:40:43.237  9128  9128 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10170, CallingPid : 9128
,08-30 12:40:43.247  3403  4567 D ConnectivityService: listenForNetwork for Listen from uid/pid:10170/9128 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:40:43.247  3403  3855 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-30 12:40:43.247  3403  3855 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 12:40:43.247  3403  3855 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 12:40:43.247  3403  3855 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 12:40:43.247  3403  3855 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 12:40:43.247  3403  3855 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-30 12:40:43.247  3403  3855 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 12:40:43.247  3403  3855 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-30 12:40:43.247  3403  3855 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:40:43.267  9128  9128 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 12:40:43.267  9128  9144 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-30 12:40:43.277  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 12:40:43.277  2992  2992 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-30 12:40:43.297  9128  9181 D libEGL  : eglInitialize EGLDisplay = 0xdc8ff7c4
08-30 12:40:43.297  9128  9181 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 12:40:43.297  9128  9181 D         : ro.exynos.dss isEnabled: 0
,08-30 12:40:43.297  9128  9181 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-30 12:40:43.317  3403  3962 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3403
08-30 12:40:43.327  3403  3962 I libsuspend: !@autosuspend_wakeup_count_disable
,08-30 12:40:43.327  3403  3962 D PowerManagerService: mDisplayReady: false
08-30 12:40:43.327  3403  3962 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 12:40:43.327  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:40:43.327  3403  3962 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,08-30 12:40:43.327  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:40:43.327  2992  2992 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa01c3c00
08-30 12:40:43.327  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,08-30 12:40:43.327  2992  2992 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
08-30 12:40:43.327  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:43.327  3403  3549 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
08-30 12:40:43.327  3403  3530 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
08-30 12:40:43.327  3403  3530 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,08-30 12:40:43.337  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:40:43.337  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:40:43.337  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:43.337  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 12:40:43.337  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:43.337  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 12:40:43.337  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 12:40:43.337  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 12:40:43.337  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:43.337  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:43.337  3403  3535 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 12:40:43.337  3403  3535 D PowerManagerService: mDisplayReady: true
08-30 12:40:43.337  3403  3535 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 12:40:43.347  9128  9128 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 12:40:43.367  3403  4298 V WindowStateAnimator: Finishing drawing window Window{985138a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-30 12:40:43.367  9128  9128 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,08-30 12:40:43.377  3403  3530 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:40:43.377  3403  3530 D ActivityManager: mDVFSHelper.release()
08-30 12:40:43.377  3403  3403 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 12:40:43.377  3403  4703 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3403
08-30 12:40:43.377  3403  3530 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +904ms (total +1s358ms)
08-30 12:40:43.377  3403  3530 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{60f9f5d u0 com.test.thalitest/.MainActivity t17} time:297884
08-30 12:40:43.377  3403  3530 D ViewRootImpl: #3 mView = null
,08-30 12:40:43.377  2992  3057 I SurfaceFlinger: id=21 Removed uhalitest (6/11)
,08-30 12:40:43.377  2992  3057 I SurfaceFlinger: id=21 Removed uhalitest (-2/11)
,08-30 12:40:43.387  3403  3403 I KnoxTimeoutHandler: SD activityfalse
,08-30 12:40:43.387  3403  4435 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3403
,08-30 12:40:43.397  3403  4706 V WindowStateAnimator: Finishing drawing window Window{985138a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-30 12:40:43.397  9128  9128 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e954357 time:297902
,08-30 12:40:43.397  9128  9185 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:40:43.397  9128  9185 D libEGL  : eglInitialize EGLDisplay = 0xd9fac3ec
,08-30 12:40:43.407  2992  2992 D libEGL  : eglTerminate EGLDisplay = 0x7fe659f228
,08-30 12:40:43.417  9128  9185 D         : ro.exynos.dss isEnabled: 0
,08-30 12:40:43.427  9128  9185 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,08-30 12:40:43.457  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:43.457  9128  9128 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9128
,08-30 12:40:43.477  3403  5810 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,08-30 12:40:43.537  3403  3403 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3403 (0x0)
08-30 12:40:43.537  3403  3403 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 12:40:43.537  3403  3403 D PowerManagerService: mDisplayReady: false
08-30 12:40:43.537  3403  3403 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 12:40:43.537  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:40:43.537  3403  3403 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 12:40:43.537  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:40:43.537  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:43.537  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:43.537  3403  3549 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-30 12:40:43.537  3403  3530 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-30 12:40:43.537  2992  2992 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa01c3c00
08-30 12:40:43.537  2992  2992 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-30 12:40:43.537  3403  3530 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,08-30 12:40:43.557  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:40:43.557  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:40:43.557  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:43.557  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 12:40:43.557  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:43.557  3403  3535 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 12:40:43.557  3403  3535 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 12:40:43.557  3403  3535 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 12:40:43.557  3403  3535 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 12:40:43.557  3403  3535 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 12:40:43.557  3403  3535 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 12:40:43.557  3403  3535 D PowerManagerService: mDisplayReady: true
08-30 12:40:43.557  3403  3535 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 12:40:43.597  9128  9128 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:40:43.637  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:43.687  9128  9192 D jxcore_app_log: JniHelper::setJavaVM(0xf4db4000), pthread_self() = -644875984
,08-30 12:40:43.687  9128  9192 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:40:43.687  9128  9192 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:40:43.687  9128  9192 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:40:43.687  9128  9192 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:40:43.687  9128  9192 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:40:43.687  9128  9192 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90c7179 added. We now have 1 listener(s)
,08-30 12:40:43.697  9128  9192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,08-30 12:40:43.697  9128  9192 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
08-30 12:40:43.697  9128  9192 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:40:43.697  9128  9192 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:40:43.697  9128  9192 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83a3e6c added. We now have 1 listener(s)
08-30 12:40:43.697  9128  9192 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:40:43.697  9128  9192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:40:43.697  9128  9192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:40:43.697  9128  9192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:40:43.697  9128  9192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:40:43.697  9128  9192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:40:43.707  9128  9192 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:40:43.707  9128  9192 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,08-30 12:40:43.707  9128  9192 D BluetoothAdapter: STATE_ON
,08-30 12:40:43.707  9128  9192 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:40:43.707  9128  9192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:40:43.707  9128  9192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:40:43.707  9128  9192 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:40:43.707  9128  9192 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 12:40:43.717  9128  9128 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:40:43.727  9128  9128 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:40:43.747  9128  9128 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:40:43.817  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:43.977  4009  4009 D Recents : onTaskStackChanged
,08-30 12:40:43.977  4009  4009 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,08-30 12:40:43.987  4009  4009 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 12:40:43.997  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:44.027  9128  9193 W jxcore-log: Initializing JXcore engine
08-30 12:40:44.027  9128  9193 W jxcore-log: JXcore engine is ready
,08-30 12:40:44.047  4879  4879 E audit   : type=1400 msg=audit(1472553644.047:264): avc:  denied  { ioctl } for  pid=9193 comm="Thread-163" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1199 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 12:40:44.047  4879  4879 E audit   :  SEPF_SECMOBILE_6.0.1_0012
08-30 12:40:44.047  4879  4879 E audit   : type=1300 msg=audit(1472553644.047:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=1 a3=d97fa3c8 items=0 ppid=3160 pid=9193 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 tty=(none) ses=4294967295 comm="Thread-163" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 12:40:44.047  4879  4879 E audit   : type=1327 msg=audit(1472553644.047:264): proctitle="com.test.thalitest"
08-30 12:40:44.047  4879  4879 E audit   : type=1320 msg=audit(1472553644.047:264): 
08-30 12:40:44.047  4879  4879 E audit   : type=1400 msg=audit(1472553644.047:265): avc:  denied  { ioctl } for  pid=9193 comm="Thread-163" path="socket:[14040]" dev="sockfs" ino=14040 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 12:40:44.047  4879  4879 E audit   :  SEPF_SECMOBILE_6.0.1_0012
08-30 12:40:44.047  4879  4879 E audit   : type=1300 msg=audit(1472553644.047:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=39 a1=5451 a2=1 a3=d97fa3c8 items=0 ppid=3160 pid=9193 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 tty=(none) ses=4294967295 comm="Thread-163" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 12:40:44.047  4879  4879 E audit   : type=1327 msg=audit(1472553644.047:265): proctitle="com.test.thalitest"
08-30 12:40:44.047  4879  4879 E audit   : type=1320 msg=audit(1472553644.047:265): 
,08-30 12:40:44.057  9128  9193 W jxcore-log: Starting JXcore engine
,08-30 12:40:44.087  9128  9193 W jxcore-log: Platform android
08-30 12:40:44.087  9128  9193 W jxcore-log: 
08-30 12:40:44.087  9128  9193 W jxcore-log: Process ARCH arm
08-30 12:40:44.087  9128  9193 W jxcore-log: 
,08-30 12:40:44.157  9128  9193 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:40:44.157  9128  9193 I jxcore-log: 
08-30 12:40:44.157  9128  9193 W jxcore-log: JXcore engine is started
,08-30 12:40:44.167  9128  9192 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 12:40:44.167  9128  9128 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:40:44.177  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:44.357  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:44.537  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:44.717  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:44.897  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:45.027  3403  3893 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/17_task.xml.bak
,08-30 12:40:45.077  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:45.257  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:45.437  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:45.617  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:45.797  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:45.977  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:46.157  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:46.337  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:46.517  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:46.697  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:46.877  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:47.037  3403  5809 D SSRM:n  : SIOP:: AP = 350, PST = 310 (W:6), CP = 270, LCD = 1
,08-30 12:40:47.057  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:47.237  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:47.417  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:47.597  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:47.777  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:47.957  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:48.137  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:48.317  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:48.497  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:48.567  3403  5809 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 12:40:48.677  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:48.857  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:49.037  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:49.217  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:49.397  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:49.577  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:49.757  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:49.937  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:50.117  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:50.177  9128  9193 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:40:50.177  9128  9193 I jxcore-log: 
,08-30 12:40:50.177  9128  9193 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:40:50.177  9128  9193 I jxcore-log: 
,08-30 12:40:50.187  9128  9193 D BluetoothAdapter: STATE_ON
,08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:40:50.187  9128  9193 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:40:50.197  9128  9193 D BluetoothAdapter: STATE_ON
,08-30 12:40:50.197  9128  9193 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:40:50.197  9128  9193 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:40:50.197  9128  9193 I jxcore-log: 
08-30 12:40:50.197  9128  9193 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:40:50.197  9128  9193 I jxcore-log: 
,08-30 12:40:50.297  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:50.467  9128  9193 I jxcore-log: Running unit tests
08-30 12:40:50.467  9128  9193 I jxcore-log: 
,08-30 12:40:50.467  9128  9193 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 12:40:50.467  9128  9193 I jxcore-log: Failed to execute UT.
08-30 12:40:50.467  9128  9193 I jxcore-log: 
08-30 12:40:50.467  9128  9193 I jxcore-log: Unit Test app is loaded
08-30 12:40:50.467  9128  9193 I jxcore-log: 
,08-30 12:40:50.467  9128  9193 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:40:50.467  9128  9193 I jxcore-log: 
08-30 12:40:50.467  9128  9193 I jxcore-log: My device name is: samsung-SM-G930F
08-30 12:40:50.467  9128  9193 I jxcore-log: 
08-30 12:40:50.467  9128  9193 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:40:50.467  9128  9193 I jxcore-log: 
,08-30 12:40:50.477  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:50.487  9128  9128 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 12:40:50.657  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:50.837  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:51.017  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:51.197  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:51.377  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:51.507  9128  9193 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:40:51.507  9128  9193 I jxcore-log: 
,08-30 12:40:51.557  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:51.697  9128  9193 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:40:51.697  9128  9193 I jxcore-log: 
,08-30 12:40:51.707  9128  9193 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:40:51.707  9128  9193 I jxcore-log: 
,08-30 12:40:51.737  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:51.917  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:52.067  3403  3565 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 12:40:52.087  3403  3565 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 12:40:52.097  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:52.277  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:52.297  9128  9193 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:40:52.297  9128  9193 I jxcore-log: 
,08-30 12:40:52.397  9128  9193 I jxcore-log: ERROR runTests: 
08-30 12:40:52.397  9128  9193 I jxcore-log: 
,08-30 12:40:52.397  9128  9193 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:40:52.397  9128  9193 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 12:40:52.397  9128  9193 I jxcore-log: WARN testUtils: logCallback not set!
08-30 12:40:52.397  9128  9193 I jxcore-log: 
,08-30 12:40:52.397  9128  9193 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _functionName: 'loadFile',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _lineNumber: '26',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _columnNumber: '11',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:40:52.397  9128  9193 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _functionName: '',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _lineNumber: '38',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _columnNumber: '7',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:40:52.397  9128  9193 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _functionName: '',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _lineNumber: '35',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _columnNumber: '3',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:40:52.397  9128  9193 I jxcore-log:   { _fileName: 'module.js',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _lineNumber: '621',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _columnNumber: '8',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:40:52.397  9128  9193 I jxcore-log:   { _fileName: 'module.js',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _lineNumber: '651',
08-30 12:40:52.397  9128  9193 I jxcore-log:     _columnNumber: '1',
08-30 12:40:52.397  9128  9193 I jxcore-log:    
,08-30 12:40:52.397  9128  9193 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:40:52.397  9128  9193 I jxcore-log: 
08-30 12:40:52.397  9128  9193 E jxcore-log: Error: 
08-30 12:40:52.397  9128  9193 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:40:52.397  9128  9193 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:40:52.397  9128  9193 E jxcore-log: 
,08-30 12:40:52.457  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:52.637  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:52.817  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:52.867  9195  9195 I FIPS_bssl: FIPS approved mode (1) | 9195 | app_process
,08-30 12:40:52.867  9195  9195 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 12:40:52.877  9195  9195 D AndroidRuntime: CheckJNI is OFF
08-30 12:40:52.877  9195  9195 D AndroidRuntime: readGMSProperty: start
08-30 12:40:52.877  9195  9195 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:40:52.877  9195  9195 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:40:52.877  9195  9195 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:40:52.877  9195  9195 D AndroidRuntime: readGMSProperty: end
08-30 12:40:52.877  9195  9195 D AndroidRuntime: addProductProperty: start
,08-30 12:40:52.897  9195  9195 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 12:40:52.907  3403  5845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:40:52.917  9195  9195 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 12:40:52.917  9195  9195 E AffinityControl: AffinityControl: registerfunction enter
,08-30 12:40:52.927  9195  9195 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:40:52.927  3403  4267 D PackageManager: START PACKAGE DELETE: observer{108069327}
08-30 12:40:52.927  3403  4267 D PackageManager: pkg{<packageName>}
08-30 12:40:52.927  3403  4267 D PackageManager: user{0}
08-30 12:40:52.927  3403  4267 D PackageManager: caller{2000}
08-30 12:40:52.927  3403  4267 D PackageManager: flags{2}
,08-30 12:40:52.927  3403  4267 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 12:40:52.937  3403  4267 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 12:40:52.937  3403  4267 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 12:40:52.937  3403  4267 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 12:40:52.937  3403  4267 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 12:40:52.937  3403  3565 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 12:40:52.937  3403  3565 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 12:40:52.937  3403  3565 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-30 12:40:52.937  3403  3565 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 12:40:52.937  3403  3565 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-30 12:40:52.937  3403  3565 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 12:40:52.937  3403  3565 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 12:40:52.937  3403  3565 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
08-30 12:40:52.937  3403  3504 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-30 12:40:52.937  3403  3565 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 12:40:52.937  3403  3504 I ActivityManager: Killing 9128:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
08-30 12:40:52.937  3403  3565 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 12:40:52.937  3403  3504 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 12:40:52.947  3403  3504 D ActivityManager: mDVFSHelper.acquire()
,08-30 12:40:52.957  3403  3530 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 12:40:52.957  3403  3530 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-30 12:40:52.957  3403  3530 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-30 12:40:52.957  3403  3530 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-30 12:40:52.957  3403  3530 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
08-30 12:40:52.957  3403  3530 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 12:40:52.957  3403  3530 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:40:52.957  3403  3530 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:40:52.957  3403  3530 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:40:52.957  3403  3530 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 12:40:52.957  3403  3530 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 12:40:52.957  3403  3530 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{88b37e1 V.E...... R.....ID 0,0-0,0}
,08-30 12:40:52.957  3403  3530 W WindowManager: Failed looking up window
08-30 12:40:52.957  3403  3530 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@7538906 does not exist
08-30 12:40:52.957  3403  3530 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
,08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:40:52.957  3403  3530 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:40:52.957  3403  3530 W WindowManager: view not successfully added to wm, removing view
08-30 12:40:52.957  3403  3530 D ViewRootImpl: #3 mView = null
,08-30 12:40:52.967  3403  3504 I ActivityManager: Start proc 9205:com.test.thalitest/u0a170 for activity com.test.thalitest/.MainActivity
08-30 12:40:52.967  9205  9205 E Zygote  : v2
08-30 12:40:52.967  9205  9205 I libpersona: KNOX_SDCARD checking this for 10170
08-30 12:40:52.967  9205  9205 I libpersona: KNOX_SDCARD not a persona
,08-30 12:40:52.967  9205  9205 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0012
,08-30 12:40:52.967  9205  9205 E Zygote  : accessInfo : 0
08-30 12:40:52.967  9205  9205 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-30 12:40:52.977  3403  3504 I ActivityManager:   Force finishing activity ActivityRecord{60f9f5d u0 com.test.thalitest/.MainActivity t17}
,08-30 12:40:52.977  3403  3504 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
08-30 12:40:52.977  3403  3565 D AASAinstall: there is not AASApackages.xml file
,08-30 12:40:52.997  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:52.997  9205  9205 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:40:52.997  9205  9205 D ActivityThread: Added TimaKeyStore provider
,08-30 12:40:53.077  3403  3444 I WindowState: WIN DEATH: Window{985138a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 12:40:53.077  3403  4567 D GraphicsStats: Buffer count: 8
08-30 12:40:53.077  2992  3001 I SurfaceFlinger: id=22 Removed NainActivit (6/10)
08-30 12:40:53.077  3403  4926 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2f55bc7)
,08-30 12:40:53.077  2992  3003 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
08-30 12:40:53.077  3403  3855 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:40:53.077  2992  3003 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
08-30 12:40:53.077  3403  3855 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:40:53.087  3403  3855 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:40:53.097  3134  3741 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,08-30 12:40:53.167  3403  3414 I art     : Background sticky concurrent mark sweep GC freed 173403(12MB) AllocSpace objects, 143(2MB) LOS objects, 24% free, 42MB/56MB, paused 3.011ms total 116.686ms
,08-30 12:40:53.177  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:53.267  3403  3565 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 12:40:53.327  3403  3565 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 12:40:53.337  3147  3147 W keystore: ENTER clear_uid from uid 1000 for 10170
,08-30 12:40:53.337  3403  3565 I art     : Starting a blocking GC Explicit
,08-30 12:40:53.347  2992  2992 I SurfaceFlinger: id=23 createSurf (1528x2641),1 flag=4, VSBConnecti
,08-30 12:40:53.357  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:53.357  5903  8651 D mali_winsys: new_window_surface returns 0x3000,  [1528x2641]-format:1
,08-30 12:40:53.387  4255  4255 D Launcher: onRestart, Launcher: 93282572
,08-30 12:40:53.397  3403  4703 V WindowStateAnimator: Finishing drawing window Window{27de0e0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-30 12:40:53.407  2992  2992 D libEGL  : eglInitialize EGLDisplay = 0x7fe659f108
,08-30 12:40:53.507  3403  3565 I art     : Explicit concurrent mark sweep GC freed 145995(8MB) AllocSpace objects, 6(1960KB) LOS objects, 32% free, 32MB/48MB, paused 1.573ms total 175.828ms
,08-30 12:40:53.537  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:53.557  3403  3565 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 12:40:53.557  3403  3565 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-30 12:40:53.557  3403  3565 D AASAinstall: there is not AASApackages.xml file
,08-30 12:40:53.557  3403  3565 D PackageManager: result of delete: 1{108069327}
,08-30 12:40:53.557  3403  3565 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 12:40:53.557  3403  3565 D PackageManager: userId{-1}
08-30 12:40:53.557  3403  3565 D PackageManager: andCode{true}
08-30 12:40:53.557  9195  9195 I art     : System.exit called, status: 0
08-30 12:40:53.557  9195  9195 I AndroidRuntime: VM exiting with result code 0.
,08-30 12:40:53.677  3403  3504 I WindowManager: Screenshot max retries 4 of Token{885e1ae ActivityRecord{a326a29 u0 com.samsung.android.MtpApplication/.USBConnection t16}} appWin=Window{27de0e0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
,08-30 12:40:53.677  3403  3403 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,08-30 12:40:53.687  4255  4255 D Launcher: onStart, Launcher: 93282572
08-30 12:40:53.687  4255  4255 D Launcher.HomeView: onStart
,08-30 12:40:53.687  6386  6386 V ActivityThread: updateVisibility : ActivityRecord{171e19a token=android.os.BinderProxy@fde8c93 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-30 12:40:53.687  2992  2992 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, YUIInstallC
08-30 12:40:53.697  4255  4255 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,08-30 12:40:53.697  4255  4255 V ActivityThread: updateVisibility : ActivityRecord{6efc5b6 token=android.os.BinderProxy@384955b {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,08-30 12:40:53.697  4255  4255 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
08-30 12:40:53.697  4255  4255 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
08-30 12:40:53.697  4255  4255 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,08-30 12:40:53.697  4255  4255 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
08-30 12:40:53.697  4255  4255 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
08-30 12:40:53.697  4255  4255 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
08-30 12:40:53.697  4255  4255 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
08-30 12:40:53.697  4255  4255 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
08-30 12:40:53.697  4255  4255 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,08-30 12:40:53.707  6386  7498 D mali_winsys: new_window_surface returns 0x3000,  [193x193]-format:1
,08-30 12:40:53.717  3403  3530 I Choreographer: Skipped 36 frames!  The application may be doing too much work on its main thread.
08-30 12:40:53.717  3403  3504 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-30 12:40:53.717  3403  4354 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-30 12:40:53.717  3403  4354 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 12:40:53.717  3403  3403 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 12:40:53.717  3403  3782 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 12:40:53.717  3403  3504 D InputDispatcher: Focused application released
,08-30 12:40:53.727  2992  2992 I SurfaceFlinger: id=25 createSurf (1440x2560),1 flag=4, MauncherAct
,08-30 12:40:53.727  3403  3403 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 12:40:53.727  3403  3403 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-30 12:40:53.727  2992  2992 I SurfaceFlinger: id=26 createSurf (1528x2752),1 flag=4, YUIInstallC
,08-30 12:40:53.737  4255  4565 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-30 12:40:53.747  2992  2992 I SurfaceFlinger: id=27 createSurf (1592x384),1 flag=4, VSBConnecti
,08-30 12:40:53.747  8602  9224 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
08-30 12:40:53.747  6386  7498 D mali_winsys: new_window_surface returns 0x3000,  [1528x2752]-format:1
,08-30 12:40:53.747  3403  3565 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-30 12:40:53.747  3403  3565 I ActivityManager: Killing 9205:com.test.thalitest/u0a170 (adj -100): stop com.test.thalitest cause pkg removed
,08-30 12:40:53.767  8602  9224 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-30 12:40:53.777  5903  8651 D mali_winsys: new_window_surface returns 0x3000,  [1592x384]-format:1
,08-30 12:40:53.777  3403  3565 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 12:40:53.777  8602  9224 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest

```
