#### Test 86373152291968c_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-23 10:27:49.943  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:50.123  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:50.303  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:50.473  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:50.663  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:50.683  9306  9306 I FIPS_bssl: FIPS approved mode (1) | 9306 | app_process
09-23 10:27:50.693  9306  9306 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 10:27:50.693  9306  9306 D AndroidRuntime: CheckJNI is OFF
09-23 10:27:50.693  9306  9306 D AndroidRuntime: readGMSProperty: start
09-23 10:27:50.693  9306  9306 D AndroidRuntime: readGMSProperty: already setted!!
09-23 10:27:50.693  9306  9306 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 10:27:50.693  9306  9306 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 10:27:50.693  9306  9306 D AndroidRuntime: readGMSProperty: end
09-23 10:27:50.693  9306  9306 D AndroidRuntime: addProductProperty: start
09-23 10:27:50.713  9306  9306 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 10:27:50.733  9306  9306 I Radio-JNI: register_android_hardware_Radio DONE
09-23 10:27:50.733  9306  9306 E AffinityControl: AffinityControl: registerfunction enter
09-23 10:27:50.743  9306  9306 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-23 10:27:50.773  3457  4424 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-23 10:27:50.773  3457  4424 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 10:27:50.793  3457  4424 D ResourcesManager: For user 0 new overlays fetched Null
09-23 10:27:50.793  3457  4424 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 10:27:50.793  3457  4424 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-23 10:27:50.803  3457  4424 D ActivityManager: mDVFSHelper.acquire()
09-23 10:27:50.803  3457  4424 V WindowManager: addAppToken: AppWindowToken{d0f377906 token=Token{2c8e7e1 ActivityRecord{22fad48 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-23 10:27:50.813  3457  3566 I InjectionManager: Inside getClassLibPath caller 
09-23 10:27:50.823  3457  3566 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 10:27:50.823  3457  3566 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9dea2de V.E...... R.....ID 0,0-0,0}
09-23 10:27:50.823  3457  3566 W WindowManager: Failed looking up window
09-23 10:27:50.823  3457  3566 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@f1f2cbf does not exist
09-23 10:27:50.823  3457  3566 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 10:27:50.823  3457  3566 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 10:27:50.823  9315  9315 E Zygote  : v2
09-23 10:27:50.823  9315  9315 I libpersona: KNOX_SDCARD checking this for 10171
09-23 10:27:50.823  3457  3566 D ISSUE_DEBUG: InputChannelName : aa26f8c Starting com.test.thalitest
09-23 10:27:50.823  9315  9315 I libpersona: KNOX_SDCARD not a persona
09-23 10:27:50.823  9315  9315 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 10:27:50.823  3457  4424 I ActivityManager: Start proc 9315:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-23 10:27:50.833  3457  4424 D InputDispatcher: Focused application set to: xxxx
09-23 10:27:50.833  9315  9315 E Zygote  : accessInfo : 0
09-23 10:27:50.833  9315  9315 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-23 10:27:50.833  9306  9306 D AndroidRuntime: Shutting down VM
09-23 10:27:50.833  3457  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-23 10:27:50.833  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:50.843  3005  3005 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-23 10:27:50.863  9315  9315 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 10:27:50.863  9315  9315 D ActivityThread: Added TimaKeyStore provider
09-23 10:27:50.873  6027  6027 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 10:27:50.883  3457  3473 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3457
09-23 10:27:50.883  3457  3473 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 10:27:50.883  3457  3473 D PowerManagerService: mDisplayReady: false
09-23 10:27:50.883  3457  3473 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 10:27:50.883  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 10:27:50.883  6027  6027 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 10:27:50.883  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:27:50.883  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb6c03c00
09-23 10:27:50.883  3457  3473 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 10:27:50.883  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 10:27:50.883  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:50.883  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:50.883  3457  3584 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 10:27:50.883  3457  4407 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3457
09-23 10:27:50.883  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 10:27:50.883  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:27:50.883  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:50.883  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 10:27:50.883  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:50.883  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 10:27:50.883  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 10:27:50.883  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:27:50.883  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:50.883  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:50.883  3457  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 10:27:50.883  3457  3571 D PowerManagerService: mDisplayReady: true
09-23 10:27:50.883  3457  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 10:27:50.893  3457  4409 D ActivityManager:  Launching com.test.thalitest, updated priority
09-23 10:27:50.903  4283  4283 V ActivityThread: updateVisibility : ActivityRecord{cccfc16 token=android.os.BinderProxy@eff7c4b {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-23 10:27:50.913  3457  4159 V WindowStateAnimator: Finishing drawing window Window{17695d2 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 10:27:50.913  3457  3543 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-23 10:27:50.923  3005  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fb66fee78
09-23 10:27:50.913  3457  3457 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-23 10:27:50.923  3005  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fb66fee78
09-23 10:27:50.943  3005  3650 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-23 10:27:50.943  3005  4353 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-23 10:27:50.943  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fc986f438
09-23 10:27:50.953  4283  4283 D Launcher: onTrimMemory. Level: 20
09-23 10:27:50.953  3457  3968 V WindowStateAnimator: Finishing drawing window Window{b81d234 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 10:27:50.953  6027  6027 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 10:27:50.953  6027  6027 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 10:27:50.953  6027  6027 V ActivityThread: updateVisibility : ActivityRecord{4c45cbf token=android.os.BinderProxy@aef9510 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-23 10:27:50.953  3005  3902 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-23 10:27:50.953  3005  3014 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-23 10:27:50.963  3005  3014 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-23 10:27:50.963  3005  3016 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-23 10:27:50.983  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fc986f438
09-23 10:27:50.983  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fc986f408
09-23 10:27:50.983  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fc986f438
09-23 10:27:51.013  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:51.033  3457  3457 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3457 (0x0)
09-23 10:27:51.033  3457  3457 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3457 (0x0)
09-23 10:27:51.033  3457  3457 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 10:27:51.033  3457  3457 D PowerManagerService: mDisplayReady: false
09-23 10:27:51.033  3457  3457 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 10:27:51.033  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:27:51.043  3457  3457 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 10:27:51.043  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:27:51.043  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb6c03c00
09-23 10:27:51.043  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:51.043  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 10:27:51.043  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:51.043  3457  3584 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 10:27:51.043  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:27:51.043  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:27:51.043  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:51.043  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 10:27:51.043  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:51.043  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 10:27:51.043  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:27:51.043  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:27:51.043  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:51.043  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:51.043  3457  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 10:27:51.043  3457  3571 D PowerManagerService: mDisplayReady: true
09-23 10:27:51.043  3457  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 10:27:51.203  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:51.253  3457  4409 I WindowManager: Screenshot max retries 4 of Token{2c8e7e1 ActivityRecord{22fad48 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{aa26f8c u0 d0 Starting com.test.thalitest} drawState=1
09-23 10:27:51.253  3457  3566 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 10:27:51.253  3457  3457 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 10:27:51.253  3457  3566 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 10:27:51.263  3457  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-23 10:27:51.263  3457  5936 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 10:27:51.263  3457  5936 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 10:27:51.273  3457  3457 I KnoxTimeoutHandler: SD activityfalse
09-23 10:27:51.283  9315  9315 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 10:27:51.293  3457  5936 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 10:27:51.303  3457  3566 V WindowStateAnimator: Finishing drawing window Window{aa26f8c u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-23 10:27:51.303  3457  3566 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 10:27:51.303  3457  3457 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 10:27:51.303  3457  3457 I KnoxTimeoutHandler: SD activityfalse
09-23 10:27:51.303  3457  5936 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 10:27:51.303  3457  3968 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-23 10:27:51.303  9315  9315 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-23 10:27:51.303  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fc986f318
09-23 10:27:51.303  3457  3566 D ActivityManager: mDVFSHelper.release()
09-23 10:27:51.303  3457  3566 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b31dc6e u0 com.samsung.android.MtpApplication/.USBConnection t3} time:257438
09-23 10:27:51.313  3457  5936 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 10:27:51.313  3457  5936 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 10:27:51.313  3457  5936 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 10:27:51.323  9315  9315 D ResourcesManager: For user 0 new overlays fetched Null
09-23 10:27:51.323  9315  9315 I InjectionManager: Inside getClassLibPath caller 
09-23 10:27:51.343  9315  9315 D InjectionManager: InjectionManager
09-23 10:27:51.343  9315  9315 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-23 10:27:51.343  9315  9315 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-23 10:27:51.343  9315  9315 I InjectionManager: featureStore :{}
09-23 10:27:51.343  9315  9315 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 10:27:51.353  9315  9315 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-23 10:27:51.353  9315  9315 D RelationGraph: garbageCollect()
09-23 10:27:51.353  9315  9315 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 10:27:51.373  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:51.383  9315  9315 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-23 10:27:51.423  9315  9315 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-23 10:27:51.423  9315  9315 D ResourcesManager: For user 0 new overlays fetched Null
09-23 10:27:51.423  9315  9315 I InjectionManager: Inside getClassLibPath caller 
09-23 10:27:51.433  9315  9315 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-23 10:27:51.483  9315  9315 I cr_LibraryLoader: Time to load native libraries: 34 ms (timestamps 7581-7615)
09-23 10:27:51.483  9315  9315 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 10:27:51.513  3457  3877 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-23 10:27:51.553  9315  9330 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-23 10:27:51.553  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:51.583  9315  9315 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d56386}
09-23 10:27:51.583  9315  9315 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 10:27:51.603  9315  9315 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 10:27:51.613  3457  3877 I MdnieScenarioControlService: mGameModeLauncher : false
09-23 10:27:51.613  3457  3877 I MdnieScenarioControlService: setUIMode
09-23 10:27:51.653  9315  9315 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-23 10:27:51.743  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:51.753  3457  3543 W ActivityManager: Activity pause timeout for ActivityRecord{22fad48 u0 com.test.thalitest/.MainActivity t4}
09-23 10:27:51.853  9315  9315 D libEGL  : eglInitialize EGLDisplay = 0xfff61cfc
,09-23 10:27:51.913  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:51.933  3457  4410 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
,09-23 10:27:51.933  3457  4410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-23 10:27:52.013  9315  9315 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-23 10:27:52.033  9315  9315 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 10:27:52.033  9315  9315 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-23 10:27:52.063  9315  9315 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-23 10:27:52.103  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:52.143  9315  9315 D Activity: performCreate Call Injection manager
,09-23 10:27:52.143  9315  9315 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-23 10:27:52.153  9315  9315 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 10:27:52.153  9315  9315 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d507e7d I.E...... R.....ID 0,0-0,0}
,09-23 10:27:52.163  9315  9367 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 10:27:52.173  3457  4295 W WindowManager: Failed looking up window
09-23 10:27:52.173  3457  4295 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@1b1f69f does not exist
09-23 10:27:52.173  3457  4295 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 10:27:52.173  3457  4295 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 10:27:52.173  3457  4295 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 10:27:52.173  3457  4295 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-23 10:27:52.173  3457  4295 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-23 10:27:52.173  3457  4295 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 10:27:52.173  3457  3968 D ISSUE_DEBUG: InputChannelName : fe4a3ec com.test.thalitest/com.test.thalitest.MainActivity
,09-23 10:27:52.183  3457  4413 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-23 10:27:52.183  3457  4413 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 10:27:52.183  3457  3457 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-23 10:27:52.183  3457  3457 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-23 10:27:52.183  9315  9315 V ActivityThread: updateVisibility : ActivityRecord{b1129c3 token=android.os.BinderProxy@a7ec6e5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-23 10:27:52.193  9315  9330 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-23 10:27:52.223  9315  9315 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9315
,09-23 10:27:52.233  3457  4413 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9315 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 10:27:52.233  3457  3865 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-23 10:27:52.233  3457  3865 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 10:27:52.243  3457  3865 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-23 10:27:52.243  3457  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 10:27:52.253  3457  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-23 10:27:52.253  9315  9315 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 10:27:52.253  3457  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 10:27:52.263  3457  5937 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-23 10:27:52.263  3457  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-23 10:27:52.263  3457  3865 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 10:27:52.273  3005  3005 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-23 10:27:52.273  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:52.313  9315  9367 D libEGL  : eglInitialize EGLDisplay = 0xdc63f7c4
,09-23 10:27:52.313  9315  9367 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 10:27:52.323  9315  9367 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-23 10:27:52.323  3457  3473 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3457
,09-23 10:27:52.323  3457  3473 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 10:27:52.323  3457  3473 D PowerManagerService: mDisplayReady: false
09-23 10:27:52.323  3457  3473 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 10:27:52.323  3457  3473 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 10:27:52.323  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 10:27:52.323  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:27:52.323  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb6c03c00
09-23 10:27:52.323  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:52.323  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 10:27:52.323  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:52.323  3457  3584 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,09-23 10:27:52.333  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-23 10:27:52.333  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:27:52.333  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:52.333  3005  3051 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=258462418699)
09-23 10:27:52.333  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-23 10:27:52.333  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 10:27:52.333  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 10:27:52.333  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 10:27:52.333  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-23 10:27:52.333  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:52.333  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:52.333  3457  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 10:27:52.333  3457  3571 D PowerManagerService: mDisplayReady: true
,09-23 10:27:52.333  3457  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 10:27:52.333  3457  3566 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 10:27:52.333  3457  3566 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-23 10:27:52.373  9315  9315 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-23 10:27:52.393  9315  9371 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 10:27:52.393  3457  4409 V WindowStateAnimator: Finishing drawing window Window{fe4a3ec u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-23 10:27:52.393  9315  9371 D libEGL  : eglInitialize EGLDisplay = 0xdbb1f3f4
,09-23 10:27:52.393  9315  9315 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-23 10:27:52.403  3457  4224 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3457
09-23 10:27:52.403  3457  3566 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 10:27:52.403  3457  3566 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s151ms (total +1s597ms)
09-23 10:27:52.403  3457  3566 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22fad48 u0 com.test.thalitest/.MainActivity t4} time:258535
09-23 10:27:52.403  3457  3457 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 10:27:52.403  3457  3566 D ViewRootImpl: #3 mView = null
,09-23 10:27:52.403  3005  3016 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
,09-23 10:27:52.403  3005  3014 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-23 10:27:52.403  3457  3457 I KnoxTimeoutHandler: SD activityfalse
,09-23 10:27:52.413  9315  9371 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-23 10:27:52.413  3457  4407 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3457
,09-23 10:27:52.413  3457  3473 V WindowStateAnimator: Finishing drawing window Window{fe4a3ec u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-23 10:27:52.413  9315  9315 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a7ec6e5 time:258549
09-23 10:27:52.423  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fc986f438
,09-23 10:27:52.453  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:52.463  9315  9315 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9315
,09-23 10:27:52.563  3457  3457 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3457 (0x0)
09-23 10:27:52.563  3457  3457 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 10:27:52.563  3457  3457 D PowerManagerService: mDisplayReady: false
09-23 10:27:52.563  3457  3457 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 10:27:52.563  3457  3457 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 10:27:52.563  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:27:52.563  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:27:52.563  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:52.563  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:52.563  3457  3584 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-23 10:27:52.563  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb6c03c00
09-23 10:27:52.563  3457  3566 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 10:27:52.563  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-23 10:27:52.563  3457  3566 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-23 10:27:52.583  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:27:52.583  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:27:52.583  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:52.583  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 10:27:52.583  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:52.583  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 10:27:52.583  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:27:52.583  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:27:52.583  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:27:52.583  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:27:52.583  3457  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 10:27:52.583  3457  3571 D PowerManagerService: mDisplayReady: true
09-23 10:27:52.583  3457  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 10:27:52.633  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:52.693  9315  9315 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 10:27:52.753  4019  4019 D Recents : onTaskStackChanged
,09-23 10:27:52.763  4019  4019 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-23 10:27:52.773  4019  4019 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 10:27:52.793  9315  9378 D jxcore_app_log: JniHelper::setJavaVM(0xf4cb4000), pthread_self() = -632293072
,09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6300ed added. We now have 1 listener(s)
,09-23 10:27:52.803  9315  9378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-23 10:27:52.803  9315  9378 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 10:27:52.803  9315  9378 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 10:27:52.803  9315  9378 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-23 10:27:52.803  9315  9378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76adb70 added. We now have 1 listener(s)
09-23 10:27:52.803  9315  9378 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 10:27:52.813  9315  9378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 10:27:52.813  9315  9378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 10:27:52.813  9315  9378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 10:27:52.813  9315  9378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 10:27:52.813  9315  9378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 10:27:52.813  9315  9378 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:27:52.813  9315  9378 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-23 10:27:52.813  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:52.823  9315  9378 D BluetoothAdapter: STATE_ON
,09-23 10:27:52.823  9315  9378 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:27:52.823  9315  9378 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 10:27:52.823  9315  9378 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 10:27:52.823  9315  9378 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:27:52.823  9315  9378 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 10:27:52.833  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:52.833  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:52.853  9315  9315 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 10:27:52.993  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:53.153  9315  9379 W jxcore-log: Initializing JXcore engine
09-23 10:27:53.153  9315  9379 W jxcore-log: JXcore engine is ready
,09-23 10:27:53.173  5000  5000 E audit   : type=1400 msg=audit(1474619273.173:262): avc:  denied  { ioctl } for  pid=9379 comm="Thread-164" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2212 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 10:27:53.173  5000  5000 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 10:27:53.173  5000  5000 E audit   : type=1300 msg=audit(1474619273.173:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d9c7f3c8 items=0 ppid=3174 pid=9379 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 10:27:53.173  5000  5000 E audit   : type=1327 msg=audit(1474619273.173:262): proctitle="com.test.thalitest"
09-23 10:27:53.173  5000  5000 E audit   : type=1320 msg=audit(1474619273.173:262): 
09-23 10:27:53.173  5000  5000 E audit   : type=1400 msg=audit(1474619273.173:263): avc:  denied  { ioctl } for  pid=9379 comm="Thread-164" path="socket:[39984]" dev="sockfs" ino=39984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 10:27:53.173  5000  5000 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 10:27:53.173  5000  5000 E audit   : type=1300 msg=audit(1474619273.173:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d9c7f3c8 items=0 ppid=3174 pid=9379 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 10:27:53.173  5000  5000 E audit   : type=1327 msg=audit(1474619273.173:263): proctitle="com.test.thalitest"
09-23 10:27:53.173  5000  5000 E audit   : type=1320 msg=audit(1474619273.173:263): 
,09-23 10:27:53.173  9315  9379 W jxcore-log: Starting JXcore engine
,09-23 10:27:53.173  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:53.213  9315  9379 W jxcore-log: Platform android
09-23 10:27:53.213  9315  9379 W jxcore-log: 
09-23 10:27:53.213  9315  9379 W jxcore-log: Process ARCH arm
09-23 10:27:53.213  9315  9379 W jxcore-log: 
,09-23 10:27:53.283  9315  9379 I jxcore-log: JXcore Cordova bridge is ready!
09-23 10:27:53.283  9315  9379 I jxcore-log: 
09-23 10:27:53.283  9315  9379 W jxcore-log: JXcore engine is started
,09-23 10:27:53.293  9315  9378 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 10:27:53.293  9315  9315 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 10:27:53.353  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:53.543  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:53.723  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:53.813  3457  3903 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-23 10:27:53.903  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:54.083  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:54.263  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:54.273  3457  5936 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-23 10:27:54.433  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:54.613  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:54.803  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:54.983  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:55.163  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:55.343  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:55.513  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:55.523  3457  5936 D SSRM:n  : SIOP:: AP = 290, PST = 260 (W:6), CP = 219, LCD = 1
,09-23 10:27:55.703  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:55.883  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:56.053  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:56.233  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:56.413  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:56.593  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:56.773  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:56.953  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:57.133  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:57.313  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:57.323  3457  5936 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 10:27:57.493  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:57.673  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:57.853  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:58.033  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:58.213  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:58.393  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:58.573  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:58.753  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:58.933  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:59.113  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:59.293  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:59.413  9315  9379 I jxcore-log: 2016-09-23 08:27:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 10:27:59.413  9315  9379 I jxcore-log: 
,09-23 10:27:59.413  9315  9379 I jxcore-log: 2016-09-23 08:27:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 10:27:59.413  9315  9379 I jxcore-log: 
,09-23 10:27:59.423  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:27:59.423  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:27:59.433  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.433  9315  9379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:27:59.433  9315  9379 I jxcore-log: 2016-09-23 08:27:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 10:27:59.433  9315  9379 I jxcore-log: 
,09-23 10:27:59.433  9315  9379 I jxcore-log: 2016-09-23 08:27:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 10:27:59.433  9315  9379 I jxcore-log: 
,09-23 10:27:59.473  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:59.593  9315  9379 I jxcore-log: Running unit tests
09-23 10:27:59.593  9315  9379 I jxcore-log: 
09-23 10:27:59.593  9315  9379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 10:27:59.593  9315  9379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e8e875 added. We now have 2 listener(s)
09-23 10:27:59.593  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 10:27:59.593  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 10:27:59.593  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 10:27:59.593  9315  9379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 10:27:59.593  9315  9379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17cd00a added. We now have 2 listener(s)
09-23 10:27:59.593  9315  9379 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 10:27:59.593  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 10:27:59.593  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:27:59.603  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:27:59.613  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:27:59.613  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.613  9315  9379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:27:59.613  9315  9379 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:27:59.613  9315  9379 D executeNativeTests: Running unit tests
,09-23 10:27:59.623  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:59.633  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:59.653  9315  9379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 10:27:59.653  9315  9379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fadc8 added. We now have 3 listener(s)
09-23 10:27:59.653  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 10:27:59.653  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 10:27:59.653  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 10:27:59.653  9315  9379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 10:27:59.653  9315  9379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 added. We now have 3 listener(s)
09-23 10:27:59.653  9315  9379 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 10:27:59.653  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:27:59.653  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 10:27:59.663  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:27:59.673  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:27:59.673  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:27:59.683  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.683  9315  9379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:27:59.683  9315  9379 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 10:27:59.683  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 10:27:59.683  9315  9379 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 10:27:59.683  9315  9379 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 10:27:59.683  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:27:59.683  9315  9379 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 10:27:59.683  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 10:27:59.683  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 10:27:59.683  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 10:27:59.683  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:27:59.683  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 10:27:59.683  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fadc8 removed from the list
09-23 10:27:59.683  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:27:59.683  9315  9379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 removed from the list
09-23 10:27:59.683  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:59.693  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:59.693  9315  9379 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:27:59.693  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:27:59.693  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:27:59.693  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:27:59.693  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
09-23 10:27:59.693  9315  9379 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 10:27:59.693  9315  9379 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 10:27:59.693  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 10:27:59.693  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 10:27:59.693  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:27:59.693  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:27:59.693  9315  9379 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fadc8 not in the list
09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:27:59.693  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
09-23 10:27:59.693  9315  9379 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:27:59.693  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:27:59.693  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:27:59.693  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 10:27:59.693  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 10:27:59.693  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:27:59.693  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
,09-23 10:27:59.693  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 10:27:59.703  9315  9379 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 10:27:59.703  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 10:27:59.703  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 10:27:59.703  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 10:27:59.703  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:27:59.703  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:27:59.703  9315  9379 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fadc8 not in the list
09-23 10:27:59.703  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:27:59.703  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
09-23 10:27:59.703  9315  9379 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 10:27:59.703  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:27:59.703  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:27:59.703  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:27:59.703  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:27:59.703  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 10:27:59.703  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 10:27:59.703  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:27:59.703  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
09-23 10:27:59.703  9315  9379 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 10:27:59.703  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:27:59.713  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:27:59.713  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:27:59.713  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.713  9315  9379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 10:27:59.713  9315  9379 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:27:59.713  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 10:27:59.713  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-23 10:27:59.713  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 10:27:59.713  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:27:59.713  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 10:27:59.723  9315  9379 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:27:59.723  9315  9379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 10:27:59.723  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:59.723  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.723  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.723  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.733  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:27:59.733  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 10:27:59.733  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.733  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.733  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 10:27:59.733  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 10:27:59.743  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.743  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.743  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-23 10:27:59.743  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.753  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.753  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-23 10:27:59.753  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 10:27:59.753  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-23 10:27:59.753  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 10:27:59.753  9315  9379 D BluetoothLeScanner: Start Scan
,09-23 10:27:59.753  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.753  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.763  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.763  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.763  4992  5397 D BtGatt.GattService: registerClient() - UUID=b416e7dd-d52c-4ea9-9240-f94391c87c31
,09-23 10:27:59.813  4992  5111 D BtGatt.GattService: onClientRegistered() - UUID=b416e7dd-d52c-4ea9-9240-f94391c87c31, clientIf=7
,09-23 10:27:59.813  9315  9326 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-23 10:27:59.813  4992  5010 D BtGatt.GattService: start scan with filters
09-23 10:27:59.813  4992  5010 D BtGatt.GattService: getScanSettings
,09-23 10:27:59.823  4992  5010 D BtGatt.GattService: Is it foreground application = true
,09-23 10:27:59.823  4992  5010 D BtGatt.GattService: not a background application
,09-23 10:27:59.833  4992  5010 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 10:27:59.833  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:27:59.843  4992  5010 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 10:27:59.843  4992  5010 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 10:27:59.843  4992  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 10:27:59.843  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 10:27:59.843  4992  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 10:27:59.843  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 10:27:59.843  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-23 10:27:59.843  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 10:27:59.843  4992  5153 D BtGatt.ScanManager: handling starting scan
09-23 10:27:59.853  4992  5153 D BtGatt.ScanManager: isFilteringSupported
09-23 10:27:59.853  4992  5153 D BluetoothAdapter: enableStandAloneBleMode=
,09-23 10:27:59.853  4992  5153 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.853  4992  5153 D BluetoothAdapter: STATE_ON
,09-23 10:27:59.853  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 10:27:59.853  4992  5153 D BluetoothAdapter: STATE_ON
09-23 10:27:59.853  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 10:27:59.853  9315  9315 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 10:27:59.853  4992  5153 D BluetoothAdapter: STATE_ON
09-23 10:27:59.863  4992  5153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d56386
09-23 10:27:59.863  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 10:27:59.863  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 14
09-23 10:27:59.863  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-23 10:27:59.863  9315  9379 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 10:27:59.863  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{5d5b2dd: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1
,09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24576987
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 10:27:59.873  4992  5111 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-23 10:27:59.873  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:27:59.873  4992  5153 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
,09-23 10:27:59.873  4992  5153 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 10:27:59.873  4992  5153 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 10:27:59.873  4992  5153 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-23 10:27:59.873  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{c6aae52: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 10:27:59.883  3457  3473 V AlarmManager:  remove PendingIntent] PendingIntent{ff56523: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:27:59.873  4992  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 10:27:59.873  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-23 10:27:59.873  4992  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24576987
,09-23 10:27:59.873  4992  5153 D BtGatt.ScanManager: Starting BLE batch scan
09-23 10:27:59.873  4992  5153 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-23 10:27:59.883  4992  5111 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 10:27:59.883  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 10:27:59.883  4992  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-23 10:27:59.883  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:27:59.883  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{c5eea20: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:27:59.883  3457  3981 V AlarmManager:  remove PendingIntent] PendingIntent{47f9fd9: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.893  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{baf307f: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.903  3457  4159 V AlarmManager:  remove PendingIntent] PendingIntent{b98884c: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.903  3457  4295 V AlarmManager:  remove PendingIntent] PendingIntent{416095: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.913  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{f81b5aa: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.913  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{b10559b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.923  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{ebdd38: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.923  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{3247111: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.933  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{51d8276: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.943  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{894b077: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:27:59.993  3457  3814 V AlarmManager: Expired Alarm result :8
,09-23 10:28:00.013  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:00.203  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:00.283  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:00.283  3457  3814 V AlarmManager: Send whitelist package alarm :PendingIntent{6601beb: PendingIntentRecord{c9934e1 com.samsung.android.app.aodservice broadcastIntent}}
,09-23 10:28:00.293  3934  3934 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-23 10:28:00.293  3934  3934 D KeyguardUpdateMonitor: handleTimeUpdate
,09-23 10:28:00.313  3934  3934 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-23 10:28:00.363  9315  9315 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 10:28:00.363  9315  9315 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 10:28:00.363  9315  9315 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 10:28:00.363  3934  3934 D DateView: received broadcast android.intent.action.TIME_TICK
,09-23 10:28:00.373  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:00.393  4735  4735 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-23 10:28:00.403  4735  4735 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-23 10:28:00.403  4693  4693 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-23 10:28:00.403  4693  4693 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-23 10:28:00.403  3457  4409 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-23 10:28:00.413  3457  4409 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-23 10:28:00.413  3457  4409 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
,09-23 10:28:00.413  3457  4409 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-23 10:28:00.413  3164  7683 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-23 10:28:00.413  3457  4409 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-23 10:28:00.413  3457  4409 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-23 10:28:00.413  3457  4409 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-23 10:28:00.413  4693  4693 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@613f2a4, service=Device Physical Context Monitor
09-23 10:28:00.413  4693  4693 I AlpmModeManager: startAlpmMode : state  = BLANK
,09-23 10:28:00.413  4693  4693 D DefaultClockView: Window showed. Time views updating
09-23 10:28:00.423  3457  4224 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3457
09-23 10:28:00.423  3457  4224 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 10:28:00.423  3457  4224 D PowerManagerService: mDisplayReady: false
,09-23 10:28:00.423  3457  4224 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 10:28:00.423  3457  4224 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 10:28:00.423  4693  4693 D AODUpdatePositionController: updatePosition: direction[1] updatePosition: X[32] Y[26] NewPositionTimer[56]
09-23 10:28:00.423  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 10:28:00.423  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb6c03c00
09-23 10:28:00.423  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:28:00.423  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 10:28:00.423  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:28:00.423  4693  4693 D DefaultClockView: LocalTime Pattern : HH:mm
09-23 10:28:00.423  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:28:00.423  3457  3584 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 10:28:00.423  3457  3566 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 10:28:00.423  3457  3566 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-23 10:28:00.423  4693  4693 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 10:28 time02: null ampm: null
,09-23 10:28:00.433  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-23 10:28:00.433  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:28:00.433  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 10:28:00.433  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-23 10:28:00.433  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 10:28:00.433  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:28:00.433  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 10:28:00.433  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 10:28:00.433  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:28:00.433  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:28:00.433  3457  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-23 10:28:00.433  3457  3571 D PowerManagerService: mDisplayReady: true
09-23 10:28:00.433  3457  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display,
,09-23 10:28:00.443  4693  4693 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-23 10:28:00.443  4693  4693 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-23 10:28:00.443  4693  4693 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pt., 23 wrz 10:28
09-23 10:28:00.443  4693  4693 I AODService.ClockTimer: startAlarm : TICK
,09-23 10:28:00.443  3457  3968 V AlarmManager: Add whitelist package alarm :PendingIntent{3d75002: PendingIntentRecord{c9934e1 com.samsung.android.app.aodservice broadcastIntent}}
,09-23 10:28:00.453  4693  4693 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,09-23 10:28:00.453  4693  4693 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
09-23 10:28:00.453  3457  3967 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-23 10:28:00.453  3457  3967 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-23 10:28:00.453  4693  4693 D DefaultClockView: RootView invalidate()
,09-23 10:28:00.453  3457  3474 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3457
,09-23 10:28:00.473  3164  3207 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,09-23 10:28:00.473  3457  3817 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,09-23 10:28:00.473  3457  3816 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 8, 28, 0,
09-23 10:28:00.473  3457  3816 D SensorHubManager: SendSensorHubData: send data = -63, 14, 8, 28, 0
,09-23 10:28:00.473  3164  3164 D Sensorhubs: sendContextData: -63, 14, 8, 28, 0
,09-23 10:28:00.483  3457  3816 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-23 10:28:00.483  3457  3816 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-23 10:28:00.483  3457  3816 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-23 10:28:00.483  3457  3816 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,09-23 10:28:00.483  3457  3816 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,09-23 10:28:00.483  3457  3819 D SContextService: updateSContext() : event = Device Physical Context Monitor
09-23 10:28:00.483  4693  4693 I AODService: onSContextChanged: AODScreenShown state is already true
,09-23 10:28:00.553  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:00.603  3457  3457 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3457 (0x0)
,09-23 10:28:00.603  3457  3457 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 10:28:00.603  3457  3457 D PowerManagerService: mDisplayReady: false
09-23 10:28:00.603  3457  3457 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 10:28:00.603  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-23 10:28:00.603  3457  3457 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 10:28:00.603  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb6c03c00
,09-23 10:28:00.603  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:28:00.603  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:28:00.613  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-23 10:28:00.603  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-23 10:28:00.603  3457  3584 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 10:28:00.613  3457  3566 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,09-23 10:28:00.613  3457  3566 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-23 10:28:00.643  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:28:00.643  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:28:00.643  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:28:00.643  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 10:28:00.643  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:28:00.643  3457  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 10:28:00.643  3457  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 10:28:00.643  3457  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 10:28:00.643  3457  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 10:28:00.643  3457  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 10:28:00.643  3457  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 10:28:00.643  3457  3571 D PowerManagerService: mDisplayReady: true
09-23 10:28:00.643  3457  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 10:28:00.743  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:00.853  3457  3591 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-23 10:28:00.883  3457  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 10:28:00.893  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:00.893  4992  4992 D BtGatt.ScanManager: awakened up at time 267026
,09-23 10:28:00.893  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-23 10:28:00.903  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{2911b50: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.903  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
09-23 10:28:00.903  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:00.903  4992  5111 D BtGatt.GattService: current time is 267038503577
09-23 10:28:00.903  4992  5111 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -77, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -87, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
09-23 10:28:00.903  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{dfb3149: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.913  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-23 10:28:00.913  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:00.913  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:00.913  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-23 10:28:00.913  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:00.913  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:00.913  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 10:28:00.913  4992  5111 D ScanRecord: parseFromBytes
,09-23 10:28:00.913  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:00.913  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 10:28:00.913  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:00.913  4992  5111 D ScanRecord: first manudata for manu ID
,09-23 10:28:00.913  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 10:28:00.913  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:00.913  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:00.913  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-23 10:28:00.913  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:00.913  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:00.913  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:28:00.923  9315  9325 D ScanRecord: parseFromBytes
,09-23 10:28:00.923  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:00.923  9315  9325 D ScanRecord: parseFromBytes
,09-23 10:28:00.923  9315  9325 D ScanRecord: first manudata for manu ID
,09-23 10:28:00.923  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:00.923  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:00.923  9315  9325 D ScanRecord: parseFromBytes
,09-23 10:28:00.923  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{46e6a4e: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:00.923  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:00.923  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:00.923  9315  9325 D ScanRecord: first manudata for manu ID
,09-23 10:28:00.923  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:00.923  9315  9325 D ScanRecord: first manudata for manu ID
,09-23 10:28:00.933  3457  3981 V AlarmManager:  remove PendingIntent] PendingIntent{dbb376f: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.943  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{2749c7c: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.943  3457  3473 V AlarmManager:  remove PendingIntent] PendingIntent{73c9905: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.953  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{a4add5a: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.953  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{eeddb8b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.963  3457  4295 V AlarmManager:  remove PendingIntent] PendingIntent{cad0468: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:00.963  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{d72c081: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:01.103  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:01.283  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:01.453  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:01.633  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:01.813  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:01.913  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:01.913  4992  4992 D BtGatt.ScanManager: awakened up at time 268046
,09-23 10:28:01.913  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 10:28:01.923  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{35ca567: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:01.933  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
,09-23 10:28:01.933  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:01.933  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{d81ff14: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
,09-23 10:28:01.933  4992  5111 D BtGatt.GattService: current time is 268063516153
,09-23 10:28:01.933  4992  5111 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -77, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -88, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,09-23 10:28:01.933  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-23 10:28:01.933  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:01.933  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:01.933  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-23 10:28:01.933  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:01.933  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:01.933  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 10:28:01.933  4992  5111 D ScanRecord: parseFromBytes
,09-23 10:28:01.933  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:01.933  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-23 10:28:01.933  4992  5111 D ScanRecord: parseFromBytes
,09-23 10:28:01.943  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{989e3bd: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:01.933  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:01.933  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-23 10:28:01.933  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:01.933  4992  5111 D ScanRecord: first manudata for manu ID
,09-23 10:28:01.943  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:01.943  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:01.943  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:01.943  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:01.943  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:01.943  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:01.943  9315  9326 D ScanRecord: parseFromBytes
,09-23 10:28:01.943  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:01.943  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:01.943  9315  9326 D ScanRecord: first manudata for manu ID
,09-23 10:28:01.953  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{447bdb2: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:01.953  3457  3474 V AlarmManager:  remove PendingIntent] PendingIntent{8043103: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:01.963  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{c09f880: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:01.963  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{cf5feb9: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:01.993  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:02.113  3149  3632 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 10:28:02.183  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:02.353  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:02.533  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:02.583  3457  5972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-23 10:28:02.723  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:02.893  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:02.933  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:02.943  4992  4992 D BtGatt.ScanManager: awakened up at time 269073
,09-23 10:28:02.943  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 10:28:02.943  3457  3981 V AlarmManager:  remove PendingIntent] PendingIntent{30eda5f: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:02.953  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-23 10:28:02.953  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:02.953  4992  5111 D BtGatt.GattService: current time is 269083244114
09-23 10:28:02.953  4992  5111 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -52, 11, 57, -70, 107, -17, 1, 0, -99, 3, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 10:28:02.953  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 10:28:02.953  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{8561cac: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:02.953  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:02.953  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:02.953  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 10:28:02.953  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:02.953  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:02.953  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 10:28:02.953  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:02.953  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:02.963  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:02.963  9315  9325 D ScanRecord: first manudata for manu ID
,09-23 10:28:02.963  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:02.963  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:02.963  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:02.963  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:02.963  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{26ecd75: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:02.973  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{945510a: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:02.983  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{8f0bd7b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:02.983  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{5e5798: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:02.993  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{e6bcbf1: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:03.073  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:03.253  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:03.443  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:03.623  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:03.803  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:03.953  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:03.963  4992  4992 D BtGatt.ScanManager: awakened up at time 270091
,09-23 10:28:03.973  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 10:28:03.973  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{743b657: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:03.983  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
,09-23 10:28:03.983  3457  3473 V AlarmManager:  remove PendingIntent] PendingIntent{7ad5544: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:03.983  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:03.983  4992  5111 D BtGatt.GattService: current time is 270113172960
09-23 10:28:03.983  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:03.983  4992  5111 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -95, 2, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 71, -122, -77, 84, 69, -12, 1, -128, -79, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -91, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 10:28:03.983  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 10:28:03.983  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:03.983  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:03.983  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,09-23 10:28:03.983  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:03.983  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:03.983  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 10:28:03.983  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:03.983  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:03.983  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 10:28:03.983  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:03.983  4992  5111 D ScanRecord: first manudata for manu ID
,09-23 10:28:03.983  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 10:28:03.983  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:03.983  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:03.983  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 10:28:03.983  4992  5111 D ScanRecord: parseFromBytes
,09-23 10:28:03.983  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:03.993  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:03.993  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:03.993  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:03.993  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:03.993  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:03.993  9315  9326 D ScanRecord: first manudata for manu ID
,09-23 10:28:03.993  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:04.003  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{b60362d: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:03.993  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:03.993  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:03.993  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:03.993  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:03.993  9315  9326 D ScanRecord: first manudata for manu ID
,09-23 10:28:04.013  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{c46f762: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.023  3457  3474 V AlarmManager:  remove PendingIntent] PendingIntent{16360f3: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.033  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{dcc81b0: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.043  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{db70829: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.053  3457  4295 V AlarmManager:  remove PendingIntent] PendingIntent{42127ae: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.063  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{ac9194f: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.073  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{f7008dc: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.163  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:04.343  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:04.513  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:04.703  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:04.873  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.873  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:04.883  9315  9379 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 10:28:04.883  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 10:28:04.883  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 10:28:04.883  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:28:04.883  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 10:28:04.883  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 10:28:04.883  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 10:28:04.883  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:28:04.883  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 10:28:04.883  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-23 10:28:04.883  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-23 10:28:04.893  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.893  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.893  9315  9379 D BluetoothLeScanner: Stop Scan
,09-23 10:28:04.903  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 10:28:04.903  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 10:28:04.903  4992  5397 D BtGatt.GattService: stopScan() - queue size =1
09-23 10:28:04.903  4992  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-23 10:28:04.903  4992  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,09-23 10:28:04.903  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 1
,09-23 10:28:04.913  4992  5010 D BtGatt.GattService: unregisterClient() - clientIf=7
09-23 10:28:04.913  4992  5153 D BtGatt.ScanManager: filter size is 1
09-23 10:28:04.913  4992  5153 D BtGatt.ScanManager: delete FilterIndex - 3
,09-23 10:28:04.913  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 10:28:04.913  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 10:28:04.913  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{b8efde5: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:04.913  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 10:28:04.913  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-23 10:28:04.913  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-23 10:28:04.913  4992  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-23 10:28:04.913  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:04.913  4992  5153 D BtGatt.ScanManager: stopping BLe Batch
,09-23 10:28:04.923  4992  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-23 10:28:04.923  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 10:28:04.923  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:28:04.923  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 10:28:04.923  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 1
09-23 10:28:04.923  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.933  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,09-23 10:28:04.933  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:04.933  4992  5111 D BtGatt.GattService: current time is 271060624690
09-23 10:28:04.933  4992  5111 D BtGatt.GattService: Batch record : [-52, 11, 57, -70, 107, -17, 1, 0, -97, 16, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 10:28:04.933  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.933  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{15c10ba: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:04.933  9315  9379 D BluetoothLeAdvertiser: stop advertising
09-23 10:28:04.933  9315  9379 D BluetoothLeAdvertiser: wrapper is null
09-23 10:28:04.933  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 10:28:04.933  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 10:28:04.933  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,09-23 10:28:04.933  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:04.933  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 10:28:04.933  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:04.933  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 10:28:04.933  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 10:28:04.933  9315  9315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:28:04.933  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:28:04.933  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 10:28:04.943  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{b27fb6b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:04.933  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:28:04.933  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 10:28:04.933  9315  9379 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fadc8 not in the list
09-23 10:28:04.933  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:28:04.933  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
,09-23 10:28:04.933  9315  9379 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:28:04.933  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 10:28:04.943  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 1
,09-23 10:28:04.943  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{848e347: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:04.943  4992  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-23 10:28:04.943  4992  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-23 10:28:04.953  9315  9315 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:28:04.953  9315  9315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 10:28:04.953  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{c329774: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.953  9315  9315 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.953  9315  9315 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.963  9315  9315 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.963  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{368049d: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.963  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 10:28:04.963  9315  9315 D BluetoothAdapter: STATE_ON
,09-23 10:28:04.963  9315  9315 D BluetoothAdapter: STATE_ON
09-23 10:28:04.963  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{31ffd12: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:04.963  9315  9315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 10:28:04.963  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 10:28:04.963  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 10:28:04.963  9315  9315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:28:04.973  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{1a66ce3: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.973  9315  9315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:28:04.973  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:28:04.973  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 10:28:04.983  9315  9315 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:28:04.983  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 10:28:04.983  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{9c8f43f: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.983  9315  9315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:28:04.983  9315  9315 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 10:28:04.983  3457  3981 V AlarmManager:  remove PendingIntent] PendingIntent{cb5610c: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.993  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{8142a55: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:04.993  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{83a1c6a: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:05.003  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{962955b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:05.003  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{7dd81f8: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:05.063  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:05.243  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:05.423  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:05.483  9315  9315 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 10:28:05.543  3457  5936 D SSRM:n  : SIOP:: AP = 290, PST = 263 (W:6), CP = 229, LCD = 1
,09-23 10:28:05.603  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:05.783  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:05.953  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:06.143  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:06.313  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:06.493  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:06.683  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:06.853  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:07.043  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:07.073  3149  3632 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 10:28:07.223  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:07.333  3457  4407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-23 10:28:07.333  3457  4407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-23 10:28:07.333  3457  4407 D BatteryService: online:4, current avg:-52, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-23 10:28:07.333  3457  4407 D BatteryService: stay LED for fully charged
09-23 10:28:07.333  3457  3457 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-23 10:28:07.343  3457  3457 I MotionRecognitionService: Plugged
09-23 10:28:07.343  3457  3457 D MotionRecognitionService:   cableConnection= 1
09-23 10:28:07.343  3457  3457 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-23 10:28:07.343  3457  3457 D MotionRecognitionService: skip setTransmitPower. 
,09-23 10:28:07.353  3457  3859 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-23 10:28:07.353  3934  3934 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-23 10:28:07.353  3934  3934 D KeyguardUpdateMonitor: handleBatteryUpdate
09-23 10:28:07.353  3934  3934 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-23 10:28:07.373  5034  5034 D CommonServiceConfiguration: getStringValueSetting
,09-23 10:28:07.373  4992  4992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-23 10:28:07.373  4992  5396 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-23 10:28:07.383  4693  4693 D BatteryController: saveBatteryData : level[100], status[5]
,09-23 10:28:07.383  5034  5034 D BatteryMonitor: new battery level: 100
,09-23 10:28:07.393  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:07.403  3934  3934 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 10:28:07.403  3934  3934 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 10:28:07.573  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:07.753  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:07.933  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:08.113  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:08.293  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:08.473  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:08.653  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:08.833  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:09.013  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:09.193  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:09.373  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:09.553  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:09.733  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:09.913  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:09.943  9315  9379 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 10:28:09.943  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:28:09.963  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:28:09.973  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:28:09.973  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:09.983  9315  9379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:28:09.983  9315  9379 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:28:09.983  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 10:28:09.983  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-23 10:28:09.983  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 10:28:09.983  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:28:09.983  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 10:28:10.003  9315  9379 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:28:10.003  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:28:10.003  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.013  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.013  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:28:10.013  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.023  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.023  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 10:28:10.023  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 10:28:10.023  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 10:28:10.023  9315  9379 D BluetoothLeScanner: Start Scan
,09-23 10:28:10.023  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.023  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.033  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.033  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.043  4992  5010 D BtGatt.GattService: registerClient() - UUID=864a9ee3-5865-4297-ab40-2ae0dca442ae
,09-23 10:28:10.083  4992  5111 D BtGatt.GattService: onClientRegistered() - UUID=864a9ee3-5865-4297-ab40-2ae0dca442ae, clientIf=7
,09-23 10:28:10.083  9315  9325 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-23 10:28:10.083  4992  5397 D BtGatt.GattService: start scan with filters
,09-23 10:28:10.093  4992  5397 D BtGatt.GattService: getScanSettings
,09-23 10:28:10.093  4992  5397 D BtGatt.GattService: Is it foreground application = true
09-23 10:28:10.093  4992  5397 D BtGatt.GattService: not a background application
,09-23 10:28:10.093  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:10.103  4992  5397 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 10:28:10.113  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 10:28:10.113  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 10:28:10.113  4992  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 10:28:10.113  4992  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 10:28:10.113  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 10:28:10.113  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 10:28:10.113  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 10:28:10.113  4992  5153 D BtGatt.ScanManager: handling starting scan
09-23 10:28:10.113  4992  5153 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.113  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 10:28:10.113  4992  5153 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.123  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{77c54d3: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.123  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 15
,09-23 10:28:10.123  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-23 10:28:10.123  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 10:28:10.123  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 10:28:10.123  9315  9315 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 10:28:10.123  4992  5111 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-23 10:28:10.123  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.133  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{ffa9810: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.133  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 10:28:10.133  4992  5153 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
09-23 10:28:10.133  4992  5153 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 10:28:10.133  4992  5153 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,09-23 10:28:10.133  4992  5153 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-23 10:28:10.133  4992  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 10:28:10.133  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.133  4992  5153 D BtGatt.ScanManager: Starting BLE batch scan
09-23 10:28:10.133  4992  5153 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-23 10:28:10.133  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 2
,09-23 10:28:10.133  4992  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24576988
,09-23 10:28:10.133  4992  5171 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 10:28:10.133  4992  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 10:28:10.133  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-23 10:28:10.143  4992  5111 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 10:28:10.143  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{467cf09: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.143  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 10:28:10.143  9315  9379 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 10:28:10.143  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{b3e150e: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:10.143  4992  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-23 10:28:10.143  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 10:28:10.143  4992  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24576988
,09-23 10:28:10.143  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.153  9315  9379 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 10:28:10.153  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{aad6b2f: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.153  9315  9379 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 10:28:10.153  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 10:28:10.153  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 10:28:10.153  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:28:10.153  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-23 10:28:10.153  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 10:28:10.153  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 10:28:10.153  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:28:10.153  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 10:28:10.153  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 10:28:10.153  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 10:28:10.153  9315  9379 D BluetoothAdapter: STATE_ON
09-23 10:28:10.153  9315  9379 D BluetoothAdapter: STATE_ON
09-23 10:28:10.153  9315  9379 D BluetoothLeScanner: Stop Scan
,09-23 10:28:10.153  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{7d9253c: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.163  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 10:28:10.163  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 10:28:10.163  4992  5397 D BtGatt.GattService: stopScan() - queue size =1
09-23 10:28:10.163  4992  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-23 10:28:10.163  4992  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 10:28:10.163  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-23 10:28:10.163  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 10:28:10.163  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 10:28:10.163  4992  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-23 10:28:10.163  4992  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-23 10:28:10.163  4992  5018 D BtGatt.GattService: unregisterClient() - clientIf=7
09-23 10:28:10.163  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{93552c5: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.163  4992  5153 D BtGatt.ScanManager: filter size is 1
09-23 10:28:10.163  4992  5153 D BtGatt.ScanManager: delete FilterIndex - 4
,09-23 10:28:10.163  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 10:28:10.163  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 10:28:10.163  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 10:28:10.163  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 10:28:10.163  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 10:28:10.163  4992  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
,09-23 10:28:10.163  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.163  4992  5153 D BtGatt.ScanManager: stopping BLe Batch
,09-23 10:28:10.173  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 10:28:10.173  4992  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-23 10:28:10.173  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 10:28:10.173  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-23 10:28:10.173  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.173  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.173  9315  9379 D BluetoothLeAdvertiser: stop advertising
09-23 10:28:10.173  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{44a741a: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.173  9315  9379 D BluetoothLeAdvertiser: wrapper is null
09-23 10:28:10.173  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{92f8b4b: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:10.173  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 10:28:10.173  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{cb15928: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:10.173  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 10:28:10.173  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 10:28:10.173  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-23 10:28:10.173  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.173  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 10:28:10.173  9315  9315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:28:10.173  9315  9379 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 10:28:10.173  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:28:10.173  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 10:28:10.173  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:28:10.173  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 10:28:10.173  9315  9379 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fadc8 not in the list
09-23 10:28:10.173  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 10:28:10.173  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
09-23 10:28:10.173  9315  9379 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:28:10.173  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 10:28:10.183  9315  9315 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:28:10.183  9315  9315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 10:28:10.183  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{56dfd4: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.183  9315  9315 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.183  9315  9315 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.183  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{f28157d: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.183  9315  9315 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.193  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 10:28:10.193  9315  9315 D BluetoothAdapter: STATE_ON
09-23 10:28:10.193  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{64b6c72: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.193  9315  9315 D BluetoothAdapter: STATE_ON
09-23 10:28:10.193  9315  9315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 10:28:10.193  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 10:28:10.193  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 10:28:10.193  9315  9315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:28:10.193  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{b5418c3: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.193  9315  9379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:28:10.193  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:28:10.203  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 10:28:10.203  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.203  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{c2c2540: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.203  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.203  9315  9379 D BluetoothLeAdvertiser: stop advertising
09-23 10:28:10.203  9315  9379 D BluetoothLeAdvertiser: wrapper is null
,09-23 10:28:10.203  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 10:28:10.203  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 10:28:10.203  9315  9379 D BluetoothAdapter: STATE_ON
09-23 10:28:10.203  9315  9379 D BluetoothAdapter: STATE_ON
09-23 10:28:10.203  9315  9379 D BluetoothLeScanner: could not find callback wrapper
09-23 10:28:10.203  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 10:28:10.203  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:28:10.203  9315  9379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b001e61 not in the list
09-23 10:28:10.203  9315  9315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:28:10.203  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:28:10.203  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 10:28:10.203  9315  9379 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 10:28:10.213  3457  3473 V AlarmManager:  remove PendingIntent] PendingIntent{b4e556c: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.213  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:28:10.213  9315  9315 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:28:10.213  9315  9315 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 10:28:10.213  9315  9315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 10:28:10.223  3457  4159 V AlarmManager:  remove PendingIntent] PendingIntent{b815c58: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.223  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.223  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{44751b1: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:28:10.223  9315  9379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:28:10.223  9315  9315 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 10:28:10.223  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.233  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{d27e696: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.233  9315  9379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 10:28:10.233  9315  9379 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:28:10.233  9315  9379 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 10:28:10.233  9315  9379 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 10:28:10.233  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 10:28:10.233  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:28:10.233  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 10:28:10.233  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{cf3d622: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.233  9315  9379 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:28:10.243  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.243  3457  3473 V AlarmManager:  remove PendingIntent] PendingIntent{f5cb8b3: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.243  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:28:10.243  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.243  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.243  3457  3981 V AlarmManager:  remove PendingIntent] PendingIntent{8335e70: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.243  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.253  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 10:28:10.253  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 10:28:10.253  9315  9379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 10:28:10.253  9315  9379 D BluetoothLeScanner: Start Scan
09-23 10:28:10.253  9315  9315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:28:10.253  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.253  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.253  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{f4585e9: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.253  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.253  9315  9379 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.253  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{a9d326e: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.253  4992  5448 D BtGatt.GattService: registerClient() - UUID=1b61ac93-1683-4d76-85fd-97b5bcf6aa12
,09-23 10:28:10.263  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{9602d0f: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.263  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{447f19c: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.273  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:10.303  4992  5111 D BtGatt.GattService: onClientRegistered() - UUID=1b61ac93-1683-4d76-85fd-97b5bcf6aa12, clientIf=7
,09-23 10:28:10.303  9315  9326 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-23 10:28:10.303  4992  5397 D BtGatt.GattService: start scan with filters
,09-23 10:28:10.303  4992  5397 D BtGatt.GattService: getScanSettings
,09-23 10:28:10.303  4992  5397 D BtGatt.GattService: Is it foreground application = true
,09-23 10:28:10.303  4992  5397 D BtGatt.GattService: not a background application
,09-23 10:28:10.303  4992  5397 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 10:28:10.313  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 10:28:10.313  4992  5397 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 10:28:10.313  4992  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 10:28:10.313  4992  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,09-23 10:28:10.313  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 10:28:10.313  9315  9379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 10:28:10.313  9315  9379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-23 10:28:10.313  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 10:28:10.313  4992  5153 D BtGatt.ScanManager: handling starting scan
09-23 10:28:10.313  4992  5153 D BluetoothAdapter: STATE_ON
,09-23 10:28:10.313  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 10:28:10.313  9315  9379 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 10:28:10.313  4992  5153 D BluetoothAdapter: STATE_ON
09-23 10:28:10.313  9315  9315 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 10:28:10.313  9315  9379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 10:28:10.313  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 16
,09-23 10:28:10.313  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-23 10:28:10.323  3457  4295 V AlarmManager:  remove PendingIntent] PendingIntent{8e797a5: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.323  4992  5111 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-23 10:28:10.323  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.323  4992  5153 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
,09-23 10:28:10.323  4992  5153 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 10:28:10.323  4992  5153 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 10:28:10.323  4992  5153 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-23 10:28:10.323  4992  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 10:28:10.323  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.323  4992  5153 D BtGatt.ScanManager: Starting BLE batch scan
09-23 10:28:10.323  4992  5153 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-23 10:28:10.323  9315  9379 I io.jxcore.node.ConnectionHelper: start: OK
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 3
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24576988
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 10:28:10.323  4992  5111 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 10:28:10.323  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 10:28:10.323  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{96e077a: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
,09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-23 10:28:10.333  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{c7c8b2b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 10:28:10.323  4992  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24576988
09-23 10:28:10.323  4992  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-23 10:28:10.323  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 10:28:10.333  3457  4159 V AlarmManager:  remove PendingIntent] PendingIntent{1b08b88: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.333  3457  4408 V AlarmManager:  remove PendingIntent] PendingIntent{5df0921: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.343  3457  3981 V AlarmManager:  remove PendingIntent] PendingIntent{5452146: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.343  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{b6af07: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.343  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{d86d834: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.353  3457  3474 V AlarmManager:  remove PendingIntent] PendingIntent{482165d: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.353  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{7220bd2: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.353  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{f8534a3: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.363  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{ad343a0: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.363  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{84ebb59: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.363  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{671131e: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.373  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{92c77ff: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:10.453  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:10.633  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:10.813  9315  9315 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 10:28:10.813  9315  9315 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 10:28:10.813  9315  9315 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 10:28:10.813  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:10.993  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:11.173  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:11.333  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:11.333  4992  4992 D BtGatt.ScanManager: awakened up at time 277465
,09-23 10:28:11.333  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 10:28:11.343  3457  4295 V AlarmManager:  remove PendingIntent] PendingIntent{4a6b415: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.343  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
09-23 10:28:11.343  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:11.343  4992  5111 D BtGatt.GattService: current time is 277479569877
09-23 10:28:11.353  4992  5111 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -77, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, -52, 11, 57, -70, 107, -17, 1, 0, -102, 7, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -87, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-23 10:28:11.353  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 10:28:11.353  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:11.353  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-23 10:28:11.353  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:11.353  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 10:28:11.353  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:11.353  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 10:28:11.353  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:11.353  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 10:28:11.353  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:11.353  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 10:28:11.353  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:11.353  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{317432a: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.353  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 10:28:11.353  9315  9325 D ScanRecord: parseFromBytes
,09-23 10:28:11.353  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:11.353  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:11.353  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:11.353  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:11.363  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{3da951b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:11.353  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:11.353  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:11.353  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:11.353  9315  9325 D ScanRecord: first manudata for manu ID
,09-23 10:28:11.373  3457  3474 V AlarmManager:  remove PendingIntent] PendingIntent{b61e6b8: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.373  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{74b7c91: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.383  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{43e67f6: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.383  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{8367f7: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.393  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{1aab664: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.393  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{e9a50cd: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.403  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{7e10d82: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:11.533  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:11.713  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:11.893  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:12.073  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:12.253  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:12.363  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:12.363  4992  4992 D BtGatt.ScanManager: awakened up at time 278496
,09-23 10:28:12.363  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 10:28:12.373  3457  4224 V AlarmManager:  remove PendingIntent] PendingIntent{18ed4d0: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.383  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
,09-23 10:28:12.383  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 10:28:12.383  4992  5111 D BtGatt.GattService: current time is 278514758800
09-23 10:28:12.383  4992  5111 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -88, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -103, 13, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 81, 34, 97, 112, -14, -5, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
09-23 10:28:12.383  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{7882cc9: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:12.383  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-23 10:28:12.383  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:12.383  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:12.383  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 10:28:12.383  4992  5111 D ScanRecord: parseFromBytes
,09-23 10:28:12.383  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:12.383  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 10:28:12.383  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:12.383  4992  5111 D ScanRecord: first manudata for manu ID
,09-23 10:28:12.393  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-23 10:28:12.393  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:12.393  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:12.393  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-23 10:28:12.393  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:12.393  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:12.393  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:12.393  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:12.393  9315  9326 D ScanRecord: parseFromBytes
,09-23 10:28:12.393  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:12.393  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:12.393  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:12.393  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:12.393  9315  9326 D ScanRecord: first manudata for manu ID
09-23 10:28:12.393  9315  9326 D ScanRecord: parseFromBytes
09-23 10:28:12.393  3457  4407 V AlarmManager:  remove PendingIntent] PendingIntent{f167fce: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
09-23 10:28:12.393  9315  9326 D ScanRecord: first manudata for manu ID
,09-23 10:28:12.403  3457  3474 V AlarmManager:  remove PendingIntent] PendingIntent{ed95eef: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.403  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{9546dfc: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.413  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{f5dcc85: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.413  3457  3967 V AlarmManager:  remove PendingIntent] PendingIntent{31ecada: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.423  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{486fb0b: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.433  3457  4424 V AlarmManager:  remove PendingIntent] PendingIntent{3786de8: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.433  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:12.433  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{533ac01: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:12.613  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:12.793  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:12.973  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:13.153  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:13.333  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:13.383  3457  3814 V AlarmManager: Expired Alarm result :4
,09-23 10:28:13.393  4992  4992 D BtGatt.ScanManager: awakened up at time 279524
,09-23 10:28:13.403  4992  5153 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 10:28:13.403  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{6283ce7: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.413  4992  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
09-23 10:28:13.413  4992  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 10:28:13.413  4992  5111 D BtGatt.GattService: current time is 279541290876
09-23 10:28:13.413  3457  4409 V AlarmManager:  remove PendingIntent] PendingIntent{35a8094: PendingIntentRecord{7e15d9e com.android.bluetooth broadcastIntent}}
09-23 10:28:13.413  4992  5111 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -78, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -100, 3, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 71, -122, -77, 84, 69, -12, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 10:28:13.413  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 10:28:13.413  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:13.413  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:13.413  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 10:28:13.413  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:13.413  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:13.413  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 10:28:13.413  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:13.413  4992  5111 D ScanRecord: first manudata for manu ID
,09-23 10:28:13.413  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 10:28:13.413  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:13.413  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:13.413  4992  5111 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 10:28:13.413  4992  5111 D ScanRecord: parseFromBytes
09-23 10:28:13.413  4992  5111 D ScanRecord: first manudata for manu ID
09-23 10:28:13.413  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:13.413  9315  9325 D ScanRecord: first manudata for manu ID
,09-23 10:28:13.413  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:13.413  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:13.413  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:13.413  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:13.413  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:13.413  9315  9325 D ScanRecord: first manudata for manu ID
09-23 10:28:13.413  9315  9325 D ScanRecord: parseFromBytes
09-23 10:28:13.413  9315  9325 D ScanRecord: first manudata for manu ID
,09-23 10:28:13.423  3457  3474 V AlarmManager:  remove PendingIntent] PendingIntent{72e073d: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.433  3457  4389 V AlarmManager:  remove PendingIntent] PendingIntent{afbdb32: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.443  3457  4237 V AlarmManager:  remove PendingIntent] PendingIntent{4b1c083: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.453  3457  4413 V AlarmManager:  remove PendingIntent] PendingIntent{a91200: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.463  3457  4410 V AlarmManager:  remove PendingIntent] PendingIntent{778da39: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.473  3457  3473 V AlarmManager:  remove PendingIntent] PendingIntent{208787e: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.483  3457  3968 V AlarmManager:  remove PendingIntent] PendingIntent{1c5e1df: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.493  3457  4295 V AlarmManager:  remove PendingIntent] PendingIntent{d8d4e2c: PendingIntentRecord{adbb328 com.android.bluetooth broadcastIntent}}
,09-23 10:28:13.513  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 10:28:13.693  3457  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
