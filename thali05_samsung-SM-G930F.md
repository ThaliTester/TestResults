#### Test 87748691f312443_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
10-04 12:01:48.068  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:48.248  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:48.428  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:48.598  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:48.778  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:48.778  9343  9343 I FIPS_bssl: FIPS approved mode (1) | 9343 | app_process
10-04 12:01:48.788  9343  9343 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-04 12:01:48.788  9343  9343 D AndroidRuntime: CheckJNI is OFF
10-04 12:01:48.788  9343  9343 D AndroidRuntime: readGMSProperty: start
10-04 12:01:48.788  9343  9343 D AndroidRuntime: readGMSProperty: already setted!!
10-04 12:01:48.788  9343  9343 D AndroidRuntime: propertySet: couldn't set property (it is from app)
10-04 12:01:48.788  9343  9343 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
10-04 12:01:48.788  9343  9343 D AndroidRuntime: readGMSProperty: end
10-04 12:01:48.788  9343  9343 D AndroidRuntime: addProductProperty: start
10-04 12:01:48.808  9343  9343 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-04 12:01:48.828  9343  9343 I Radio-JNI: register_android_hardware_Radio DONE
10-04 12:01:48.838  9343  9343 E AffinityControl: AffinityControl: registerfunction enter
10-04 12:01:48.848  9343  9343 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-04 12:01:48.878  3438  3958 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
10-04 12:01:48.878  3438  3958 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
10-04 12:01:48.898  3438  3958 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:01:48.898  3438  3958 D GameManagerService: identifyGamePackage. com.test.thalitest
10-04 12:01:48.898  3438  3958 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
10-04 12:01:48.908  3438  3958 D ActivityManager: mDVFSHelper.acquire()
10-04 12:01:48.908  3438  3958 V WindowManager: addAppToken: AppWindowToken{d0c2123b0 token=Token{b7d4af3 ActivityRecord{c4e4962 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
10-04 12:01:48.918  3438  3544 I InjectionManager: Inside getClassLibPath caller 
10-04 12:01:48.918  3438  3544 D SecWifiDisplayUtil: Metadata value : SecSettings2
10-04 12:01:48.918  3438  3544 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a69b8c8 V.E...... R.....ID 0,0-0,0}
10-04 12:01:48.928  9352  9352 E Zygote  : v2
10-04 12:01:48.928  9352  9352 I libpersona: KNOX_SDCARD checking this for 10171
10-04 12:01:48.928  9352  9352 I libpersona: KNOX_SDCARD not a persona
10-04 12:01:48.928  3438  3544 W WindowManager: Failed looking up window
10-04 12:01:48.928  3438  3544 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@800cd61 does not exist
10-04 12:01:48.928  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-04 12:01:48.928  3438  3544 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-04 12:01:48.928  3438  3544 D ISSUE_DEBUG: InputChannelName : f13086 Starting com.test.thalitest
10-04 12:01:48.928  9352  9352 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
10-04 12:01:48.928  9352  9352 E Zygote  : accessInfo : 0
10-04 12:01:48.928  3438  3958 I ActivityManager: Start proc 9352:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
10-04 12:01:48.928  9352  9352 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
10-04 12:01:48.928  3438  3958 D InputDispatcher: Focused application set to: xxxx
10-04 12:01:48.938  9343  9343 D AndroidRuntime: Shutting down VM
10-04 12:01:48.938  3438  3854 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
10-04 12:01:48.948  3006  3006 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
10-04 12:01:48.958  9352  9352 D TimaKeyStoreProvider: TimaSignature is unavailable
10-04 12:01:48.958  9352  9352 D ActivityThread: Added TimaKeyStore provider
10-04 12:01:48.958  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:48.968  6038  6038 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
10-04 12:01:48.968  3438  4305 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3438
10-04 12:01:48.968  3438  4305 D PowerManagerService: mDisplayReady: false
10-04 12:01:48.978  3438  4305 I libsuspend: !@autosuspend_wakeup_count_disable
10-04 12:01:48.978  3438  4305 I libsuspend: !@autosuspend_wakeup_count_disable done
10-04 12:01:48.978  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
10-04 12:01:48.978  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:01:48.978  3438  4305 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
10-04 12:01:48.978  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:48.978  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fac783c00
10-04 12:01:48.978  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:48.978  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
10-04 12:01:48.978  3438  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
10-04 12:01:48.978  6038  6038 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
10-04 12:01:48.978  3438  3958 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3438
10-04 12:01:48.978  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
10-04 12:01:48.978  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:01:48.978  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:48.978  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable
10-04 12:01:48.978  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:48.978  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
10-04 12:01:48.978  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
10-04 12:01:48.978  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:01:48.978  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:48.978  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:48.978  3438  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-04 12:01:48.978  3438  3552 D PowerManagerService: mDisplayReady: true
10-04 12:01:48.978  3438  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
10-04 12:01:48.988  3438  4602 D ActivityManager:  Launching com.test.thalitest, updated priority
10-04 12:01:48.988  3438  4306 V WindowStateAnimator: Finishing drawing window Window{d4eca2c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
10-04 12:01:48.988  4307  4307 V ActivityThread: updateVisibility : ActivityRecord{ef96f76 token=android.os.BinderProxy@613c8cc {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
10-04 12:01:48.998  3438  3438 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
10-04 12:01:48.998  3438  3514 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
10-04 12:01:49.018  3006  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fac500e78
10-04 12:01:49.018  3006  3014 D libEGL  : eglTerminate EGLDisplay = 0x7fac500e78
10-04 12:01:49.018  3438  4932 V WindowStateAnimator: Finishing drawing window Window{a36947e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
10-04 12:01:49.018  6038  6038 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
10-04 12:01:49.018  6038  6038 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
10-04 12:01:49.018  6038  6038 V ActivityThread: updateVisibility : ActivityRecord{c8576f0 token=android.os.BinderProxy@b88d95d {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
10-04 12:01:49.018  3006  4360 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
10-04 12:01:49.018  3006  3068 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
10-04 12:01:49.028  4307  4307 D Launcher: onTrimMemory. Level: 20
10-04 12:01:49.028  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd6fa4be8
10-04 12:01:49.028  3006  4360 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
10-04 12:01:49.028  3006  3068 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
10-04 12:01:49.038  3006  4359 D libEGL  : eglTerminate EGLDisplay = 0x7fa5cffe78
10-04 12:01:49.038  3006  3068 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
10-04 12:01:49.038  3006  3014 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
10-04 12:01:49.068  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd6fa4be8
10-04 12:01:49.068  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd6fa4be8
10-04 12:01:49.128  3438  3438 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3438 (0x0)
10-04 12:01:49.128  3438  3438 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3438 (0x0)
10-04 12:01:49.128  3438  3438 I libsuspend: !@autosuspend_wakeup_count_disable
10-04 12:01:49.128  3438  3438 D PowerManagerService: mDisplayReady: false
10-04 12:01:49.128  3438  3438 I libsuspend: !@autosuspend_wakeup_count_disable done
10-04 12:01:49.128  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:01:49.128  3438  3438 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
10-04 12:01:49.128  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:01:49.128  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:49.128  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:49.128  3438  3563 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
10-04 12:01:49.128  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fac783c00
10-04 12:01:49.128  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
10-04 12:01:49.128  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:01:49.128  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:01:49.128  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:49.128  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable
10-04 12:01:49.128  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:49.128  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
10-04 12:01:49.128  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:01:49.128  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:01:49.128  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:49.128  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:49.128  3438  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-04 12:01:49.128  3438  3552 D PowerManagerService: mDisplayReady: true
10-04 12:01:49.128  3438  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
10-04 12:01:49.138  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:49.318  3438  4602 I WindowManager: Screenshot max retries 4 of Token{b7d4af3 ActivityRecord{c4e4962 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{f13086 u0 d0 Starting com.test.thalitest} drawState=1
10-04 12:01:49.318  3438  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:01:49.318  3438  3438 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:01:49.318  3438  3544 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
10-04 12:01:49.328  3438  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
10-04 12:01:49.328  3438  3438 I KnoxTimeoutHandler: SD activityfalse
10-04 12:01:49.328  3438  3854 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
10-04 12:01:49.328  3438  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
10-04 12:01:49.338  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:49.358  9352  9352 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
10-04 12:01:49.358  3438  3959 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
10-04 12:01:49.358  9352  9352 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
10-04 12:01:49.368  3438  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
10-04 12:01:49.368  3438  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
10-04 12:01:49.378  3438  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
10-04 12:01:49.378  3438  3544 V WindowStateAnimator: Finishing drawing window Window{f13086 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
10-04 12:01:49.378  3438  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:01:49.378  3438  3438 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:01:49.378  3438  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
10-04 12:01:49.378  3438  3438 I KnoxTimeoutHandler: SD activityfalse
10-04 12:01:49.378  3438  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
10-04 12:01:49.378  3438  3544 D ActivityManager: mDVFSHelper.release()
10-04 12:01:49.378  9352  9352 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:01:49.378  3438  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3cea9e8 u0 com.samsung.android.MtpApplication/.USBConnection t3} time:246729
10-04 12:01:49.388  9352  9352 I InjectionManager: Inside getClassLibPath caller 
10-04 12:01:49.398  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd6fa4ac8
10-04 12:01:49.408  9352  9352 D InjectionManager: InjectionManager
10-04 12:01:49.408  9352  9352 D InjectionManager: fillFeatureStoreMap com.test.thalitest
10-04 12:01:49.408  9352  9352 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
10-04 12:01:49.408  9352  9352 I InjectionManager: featureStore :{}
10-04 12:01:49.418  9352  9352 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
10-04 12:01:49.418  9352  9352 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
10-04 12:01:49.418  9352  9352 D RelationGraph: garbageCollect()
10-04 12:01:49.428  9352  9352 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
10-04 12:01:49.448  9352  9352 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
10-04 12:01:49.478  9352  9352 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
10-04 12:01:49.478  9352  9352 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:01:49.478  9352  9352 I InjectionManager: Inside getClassLibPath caller 
10-04 12:01:49.488  9352  9352 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
10-04 12:01:49.498  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:49.538  9352  9352 I cr_LibraryLoader: Time to load native libraries: 32 ms (timestamps 6853-6885)
10-04 12:01:49.538  9352  9352 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
10-04 12:01:49.578  3438  3878 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
10-04 12:01:49.608  9352  9367 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
10-04 12:01:49.628  9352  9352 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {90b7d9c}
10-04 12:01:49.628  9352  9352 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
10-04 12:01:49.658  9352  9352 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
10-04 12:01:49.678  3438  3878 I MdnieScenarioControlService: mGameModeLauncher : false
10-04 12:01:49.678  3438  3878 I MdnieScenarioControlService: setUIMode
10-04 12:01:49.678  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:49.698  9352  9352 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
10-04 12:01:49.818  3438  3514 W ActivityManager: Activity pause timeout for ActivityRecord{c4e4962 u0 com.test.thalitest/.MainActivity t4}
10-04 12:01:49.858  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:49.888  9352  9352 D libEGL  : eglInitialize EGLDisplay = 0xffc392cc
10-04 12:01:49.988  3438  3959 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
10-04 12:01:49.988  3438  3959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,10-04 12:01:50.038  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:50.068  9352  9352 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
10-04 12:01:50.088  9352  9352 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
10-04 12:01:50.088  9352  9352 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
10-04 12:01:50.138  9352  9352 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
10-04 12:01:50.198  9352  9352 D Activity: performCreate Call Injection manager
10-04 12:01:50.208  9352  9352 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
10-04 12:01:50.208  9352  9352 D SecWifiDisplayUtil: Metadata value : SecSettings2
10-04 12:01:50.218  9352  9352 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{246f70b I.E...... R.....ID 0,0-0,0}
10-04 12:01:50.218  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:50.218  9352  9404 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-04 12:01:50.228  3438  3995 W WindowManager: Failed looking up window
10-04 12:01:50.228  3438  3995 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@f0c9041 does not exist
10-04 12:01:50.228  3438  3995 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
10-04 12:01:50.228  3438  3995 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
10-04 12:01:50.228  3438  3995 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
10-04 12:01:50.228  3438  3995 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
10-04 12:01:50.228  3438  3995 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
10-04 12:01:50.228  3438  3995 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
10-04 12:01:50.228  3438  3958 D ISSUE_DEBUG: InputChannelName : f9369e6 com.test.thalitest/com.test.thalitest.MainActivity
10-04 12:01:50.238  3438  4370 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
10-04 12:01:50.238  3438  4370 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
10-04 12:01:50.238  3438  3438 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
10-04 12:01:50.238  3438  3438 I KnoxTimeoutHandler: Shared devices show user statefalse
10-04 12:01:50.238  9352  9352 V ActivityThread: updateVisibility : ActivityRecord{e8a0801 token=android.os.BinderProxy@29b34b3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
10-04 12:01:50.248  9352  9367 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
10-04 12:01:50.268  9352  9352 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9352
10-04 12:01:50.278  3438  4305 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9352 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-04 12:01:50.278  3438  3865 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
10-04 12:01:50.278  3438  3865 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-04 12:01:50.278  3438  3865 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
10-04 12:01:50.288  3438  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
10-04 12:01:50.288  3438  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
10-04 12:01:50.298  9352  9352 D SecWifiDisplayUtil: Metadata value : SecSettings2
10-04 12:01:50.298  3438  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
10-04 12:01:50.298  3438  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
10-04 12:01:50.308  3438  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
10-04 12:01:50.308  3438  3865 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-04 12:01:50.308  3006  3006 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
10-04 12:01:50.328  3438  5948 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
10-04 12:01:50.348  9352  9404 D libEGL  : eglInitialize EGLDisplay = 0xdd4bf7c4
10-04 12:01:50.348  9352  9404 I OpenGLRenderer: Initialized EGL, version 1.4
10-04 12:01:50.348  9352  9404 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
10-04 12:01:50.348  3438  3460 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3438
10-04 12:01:50.348  3438  3460 I libsuspend: !@autosuspend_wakeup_count_disable
10-04 12:01:50.348  3438  3460 D PowerManagerService: mDisplayReady: false
10-04 12:01:50.348  3438  3460 I libsuspend: !@autosuspend_wakeup_count_disable done
10-04 12:01:50.348  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
10-04 12:01:50.348  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:01:50.358  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fac783c00
10-04 12:01:50.348  3438  3460 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
10-04 12:01:50.358  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
10-04 12:01:50.348  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:50.348  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:50.348  3438  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
10-04 12:01:50.348  3438  3544 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
10-04 12:01:50.358  3438  3544 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
10-04 12:01:50.368  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
10-04 12:01:50.368  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:01:50.368  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable
10-04 12:01:50.368  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:50.368  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
10-04 12:01:50.368  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:50.368  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
10-04 12:01:50.368  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:01:50.368  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:50.368  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:50.368  3438  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-04 12:01:50.368  3438  3552 D PowerManagerService: mDisplayReady: true
10-04 12:01:50.368  3438  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
10-04 12:01:50.388  9352  9352 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
10-04 12:01:50.398  3438  4319 V WindowStateAnimator: Finishing drawing window Window{f9369e6 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
10-04 12:01:50.398  9352  9352 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
10-04 12:01:50.408  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:50.408  3438  3462 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3438
10-04 12:01:50.408  3438  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
10-04 12:01:50.408  3438  3438 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
10-04 12:01:50.408  3438  3544 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s94ms (total +1s499ms)
10-04 12:01:50.408  3438  3438 I KnoxTimeoutHandler: SD activityfalse
10-04 12:01:50.408  3438  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c4e4962 u0 com.test.thalitest/.MainActivity t4} time:247756
10-04 12:01:50.408  3438  4595 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3438
10-04 12:01:50.408  3438  3544 D ViewRootImpl: #3 mView = null
10-04 12:01:50.408  3006  4359 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
10-04 12:01:50.408  3006  4360 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
10-04 12:01:50.418  3438  3958 V WindowStateAnimator: Finishing drawing window Window{f9369e6 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
10-04 12:01:50.418  9352  9352 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29b34b3 time:247767
10-04 12:01:50.418  9352  9408 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-04 12:01:50.418  9352  9408 D libEGL  : eglInitialize EGLDisplay = 0xdadac3f4
10-04 12:01:50.448  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fd6fa4be8
10-04 12:01:50.448  9352  9408 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
10-04 12:01:50.498  9352  9352 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9352
10-04 12:01:50.558  3438  3438 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3438 (0x0)
10-04 12:01:50.558  3438  3438 I libsuspend: !@autosuspend_wakeup_count_disable
10-04 12:01:50.558  3438  3438 D PowerManagerService: mDisplayReady: false
10-04 12:01:50.558  3438  3438 I libsuspend: !@autosuspend_wakeup_count_disable done
10-04 12:01:50.558  3438  3438 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
10-04 12:01:50.558  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:01:50.558  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:01:50.558  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fac783c00
10-04 12:01:50.558  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:50.558  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
10-04 12:01:50.558  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:50.558  3438  3563 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
10-04 12:01:50.558  3438  3544 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
10-04 12:01:50.558  3438  3544 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
10-04 12:01:50.578  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:01:50.578  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:01:50.578  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:50.578  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable
10-04 12:01:50.578  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:50.578  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
10-04 12:01:50.578  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:01:50.578  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:01:50.578  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:01:50.578  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:01:50.578  3438  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-04 12:01:50.578  3438  3552 D PowerManagerService: mDisplayReady: true
10-04 12:01:50.578  3438  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
10-04 12:01:50.578  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:50.718  9352  9352 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
10-04 12:01:50.758  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:01:50.818  4016  4016 D Recents : onTaskStackChanged
10-04 12:01:50.818  9352  9415 D jxcore_app_log: JniHelper::setJavaVM(0xf4df4000), pthread_self() = -631768784
10-04 12:01:50.818  9352  9415 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-04 12:01:50.818  9352  9415 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-04 12:01:50.818  9352  9415 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-04 12:01:50.818  9352  9415 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-04 12:01:50.818  9352  9415 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-04 12:01:50.818  9352  9415 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@887b8fb added. We now have 1 listener(s)
10-04 12:01:50.828  9352  9415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
10-04 12:01:50.828  4016  4016 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
10-04 12:01:50.828  9352  9415 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-04 12:01:50.828  9352  9415 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-04 12:01:50.828  9352  9415 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-04 12:01:50.828  9352  9415 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d614556 added. We now have 1 listener(s)
10-04 12:01:50.828  9352  9415 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-04 12:01:50.828  9352  9415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-04 12:01:50.828  9352  9415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-04 12:01:50.828  9352  9415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-04 12:01:50.828  9352  9415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-04 12:01:50.828  9352  9415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-04 12:01:50.838  9352  9415 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-04 12:01:50.838  9352  9415 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
10-04 12:01:50.838  4016  4016 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:01:50.838  9352  9415 D BluetoothAdapter: STATE_ON
10-04 12:01:50.848  9352  9415 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-04 12:01:50.848  9352  9415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-04 12:01:50.848  9352  9415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-04 12:01:50.848  9352  9415 D io.jxcore.node.ConnectivityMonitor: start: OK
10-04 12:01:50.848  9352  9415 I io.jxcore.node.LifeCycleMonitor: start: OK
10-04 12:01:50.848  9352  9352 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-04 12:01:50.858  9352  9352 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-04 12:01:50.868  9352  9352 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-04 12:01:50.938  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:51.118  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:51.218  3438  5983 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,10-04 12:01:51.298  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:51.368  9352  9416 W jxcore-log: Initializing JXcore engine
10-04 12:01:51.368  9352  9416 W jxcore-log: JXcore engine is ready
,10-04 12:01:51.388  4974  4974 E audit   : type=1400 msg=audit(1475575311.388:264): avc:  denied  { ioctl } for  pid=9416 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4113 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-04 12:01:51.388  4974  4974 E audit   :  SEPF_SECMOBILE_6.0.1_0013
10-04 12:01:51.388  4974  4974 E audit   : type=1300 msg=audit(1475575311.388:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da47a3c8 items=0 ppid=3175 pid=9416 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-04 12:01:51.388  4974  4974 E audit   : type=1327 msg=audit(1475575311.388:264): proctitle="com.test.thalitest"
10-04 12:01:51.388  4974  4974 E audit   : type=1320 msg=audit(1475575311.388:264): 
10-04 12:01:51.388  4974  4974 E audit   : type=1400 msg=audit(1475575311.388:265): avc:  denied  { ioctl } for  pid=9416 comm="Thread-160" path="socket:[38954]" dev="sockfs" ino=38954 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-04 12:01:51.388  4974  4974 E audit   :  SEPF_SECMOBILE_6.0.1_0013
10-04 12:01:51.388  4974  4974 E audit   : type=1300 msg=audit(1475575311.388:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da47a3c8 items=0 ppid=3175 pid=9416 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-04 12:01:51.388  4974  4974 E audit   : type=1327 msg=audit(1475575311.388:265): proctitle="com.test.thalitest"
10-04 12:01:51.388  4974  4974 E audit   : type=1320 msg=audit(1475575311.388:265): 
,10-04 12:01:51.398  9352  9416 W jxcore-log: Starting JXcore engine
,10-04 12:01:51.428  9352  9416 W jxcore-log: Platform android
10-04 12:01:51.428  9352  9416 W jxcore-log: 
10-04 12:01:51.428  9352  9416 W jxcore-log: Process ARCH arm
10-04 12:01:51.428  9352  9416 W jxcore-log: 
,10-04 12:01:51.478  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:51.528  9352  9416 I jxcore-log: JXcore Cordova bridge is ready!
10-04 12:01:51.528  9352  9416 I jxcore-log: 
10-04 12:01:51.528  9352  9416 W jxcore-log: JXcore engine is started
,10-04 12:01:51.528  9352  9415 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-04 12:01:51.538  9352  9352 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-04 12:01:51.658  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:51.838  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:51.918  3438  3903 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,10-04 12:01:52.018  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:52.098  3150  3633 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-04 12:01:52.198  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:52.338  3438  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
,10-04 12:01:52.378  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:52.558  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:52.738  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:52.918  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:53.098  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:53.278  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:53.458  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:53.638  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:53.818  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:53.998  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:54.178  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:54.198  3438  5947 D SSRM:n  : SIOP:: AP = 310, PST = 277 (W:6), CP = 233, LCD = 1
,10-04 12:01:54.358  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:54.538  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:54.718  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:54.898  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:55.078  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:55.258  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:55.398  3438  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,10-04 12:01:55.438  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:55.598  3150  3633 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-04 12:01:55.618  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:55.748  3438  4132 E Watchdog: !@Sync 8 [10-04 12:01:55.759]
,10-04 12:01:55.798  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:55.978  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:56.158  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:56.338  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:56.518  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:56.698  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:56.878  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:57.058  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:57.208  4376  4466 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
10-04 12:01:57.208  4376  4466 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,10-04 12:01:57.238  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:57.278  4376  4466 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 67ms lastUpdatedAfter : 145945ms
,10-04 12:01:57.418  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:57.538  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-04 12:01:57.538  9352  9416 I jxcore-log: 
,10-04 12:01:57.548  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-04 12:01:57.548  9352  9416 I jxcore-log: 
,10-04 12:01:57.548  9352  9416 D BluetoothAdapter: STATE_ON
,10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-04 12:01:57.558  9352  9416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-04 12:01:57.558  9352  9416 D BluetoothAdapter: STATE_ON
,10-04 12:01:57.568  9352  9416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-04 12:01:57.568  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-04 12:01:57.568  9352  9416 I jxcore-log: 
10-04 12:01:57.568  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-04 12:01:57.568  9352  9416 I jxcore-log: 
,10-04 12:01:57.598  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:57.768  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG UnitTest_app: 'Running unit tests'
10-04 12:01:57.768  9352  9416 I jxcore-log: 
,10-04 12:01:57.768  9352  9416 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
10-04 12:01:57.768  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-04 12:01:57.768  9352  9416 I jxcore-log: 
10-04 12:01:57.768  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-04 12:01:57.768  9352  9416 I jxcore-log: 
,10-04 12:01:57.768  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-04 12:01:57.768  9352  9416 I jxcore-log: 
,10-04 12:01:57.778  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG UnitTest_app: 'My device name is: samsung-SM-G930F'
10-04 12:01:57.778  9352  9416 I jxcore-log: 
,10-04 12:01:57.778  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - WARN testUtils: 'myNameCallback not set!'
10-04 12:01:57.778  9352  9416 I jxcore-log: 
10-04 12:01:57.778  9352  9416 I jxcore-log: 2016-10-04 10:01:57 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-04 12:01:57.778  9352  9416 I jxcore-log: 
,10-04 12:01:57.778  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:57.788  9352  9352 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-04 12:01:57.958  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:58.138  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:58.318  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:58.498  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:58.678  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:58.858  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:58.928  3438  3571 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,10-04 12:01:58.948  3438  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,10-04 12:01:58.968  9352  9416 I jxcore-log: 2016-10-04 10:01:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-04 12:01:58.968  9352  9416 I jxcore-log: 
,10-04 12:01:59.038  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:59.178  9352  9416 I jxcore-log: 2016-10-04 10:01:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-04 12:01:59.178  9352  9416 I jxcore-log: 
,10-04 12:01:59.188  9352  9416 I jxcore-log: 2016-10-04 10:01:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-04 12:01:59.188  9352  9416 I jxcore-log: 
,10-04 12:01:59.218  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:59.398  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:59.578  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:59.758  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:59.868  9352  9416 I jxcore-log: 2016-10-04 10:01:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-04 12:01:59.868  9352  9416 I jxcore-log: 
,10-04 12:01:59.938  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:01:59.968  9352  9416 I jxcore-log: 2016-10-04 10:01:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-04 12:01:59.968  9352  9416 I jxcore-log: 
,10-04 12:01:59.978  9352  9416 I jxcore-log: 2016-10-04 10:01:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-04 12:01:59.978  9352  9416 I jxcore-log: 
,10-04 12:01:59.978  9352  9416 I jxcore-log: 2016-10-04 10:01:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-04 12:01:59.978  9352  9416 I jxcore-log: 
,10-04 12:01:59.988  3438  3815 V AlarmManager: Expired Alarm result :8
,10-04 12:02:00.118  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:00.298  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:00.308  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-04 12:02:00.308  9352  9416 I jxcore-log: 
,10-04 12:02:00.348  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-04 12:02:00.348  9352  9416 I jxcore-log: 
,10-04 12:02:00.358  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-04 12:02:00.358  9352  9416 I jxcore-log: 
,10-04 12:02:00.358  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-04 12:02:00.358  9352  9416 I jxcore-log: 
,10-04 12:02:00.478  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:00.528  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-04 12:02:00.528  9352  9416 I jxcore-log: 
,10-04 12:02:00.608  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-04 12:02:00.608  9352  9416 I jxcore-log: 
,10-04 12:02:00.658  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:00.738  3438  3815 V AlarmManager: Expired Alarm result :4
10-04 12:02:00.738  3438  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{8af70d5: PendingIntentRecord{1a3f31c com.samsung.android.app.aodservice broadcastIntent}}
,10-04 12:02:00.738  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,10-04 12:02:00.738  3944  3944 D KeyguardUpdateMonitor: handleTimeUpdate
,10-04 12:02:00.758  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-04 12:02:00.758  9352  9416 I jxcore-log: 
,10-04 12:02:00.758  3944  3944 D Clock   : received broadcast android.intent.action.TIME_TICK
,10-04 12:02:00.838  3944  3944 D DateView: received broadcast android.intent.action.TIME_TICK
,10-04 12:02:00.838  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:00.848  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-04 12:02:00.848  9352  9416 I jxcore-log: 
,10-04 12:02:00.858  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-04 12:02:00.858  9352  9416 I jxcore-log: 
,10-04 12:02:00.858  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-04 12:02:00.858  9352  9416 I jxcore-log: 
,10-04 12:02:00.868  4651  4651 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,10-04 12:02:00.868  4651  4651 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,10-04 12:02:00.868  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-04 12:02:00.868  9352  9416 I jxcore-log: 
,10-04 12:02:00.868  4707  4707 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,10-04 12:02:00.868  4707  4707 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,10-04 12:02:00.878  3438  3978 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,10-04 12:02:00.878  3438  3978 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
10-04 12:02:00.878  3438  3978 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
10-04 12:02:00.878  3438  3978 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,10-04 12:02:00.878  3165  3165 D Sensorhubs: sendContextData: -72, 56, 1, 1
,10-04 12:02:00.878  3438  3978 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,10-04 12:02:00.878  3438  3978 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
10-04 12:02:00.878  3438  3978 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
10-04 12:02:00.878  4707  4707 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@a1db846, service=Device Physical Context Monitor
10-04 12:02:00.878  4707  4707 I AlpmModeManager: startAlpmMode : state  = BLANK
10-04 12:02:00.878  4707  4707 D DefaultClockView: Window showed. Time views updating
,10-04 12:02:00.878  3438  4305 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3438
10-04 12:02:00.878  3438  4305 I libsuspend: !@autosuspend_wakeup_count_disable
10-04 12:02:00.878  3438  4305 D PowerManagerService: mDisplayReady: false
,10-04 12:02:00.878  3438  4305 I libsuspend: !@autosuspend_wakeup_count_disable done
10-04 12:02:00.878  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
,10-04 12:02:00.878  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,10-04 12:02:00.878  3438  4305 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
10-04 12:02:00.888  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fac783c00
10-04 12:02:00.878  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:02:00.888  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
10-04 12:02:00.878  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:02:00.888  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-04 12:02:00.888  9352  9416 I jxcore-log: 
10-04 12:02:00.878  3438  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,10-04 12:02:00.888  3438  3544 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
10-04 12:02:00.888  3438  3544 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,10-04 12:02:00.888  4707  4707 D AODUpdatePositionController: updatePosition: direction[7] updatePosition: X[-3] Y[917] NewPositionTimer[56]
,10-04 12:02:00.888  4707  4707 D DefaultClockView: LocalTime Pattern : HH:mm
,10-04 12:02:00.888  4707  4707 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:02 time02: null ampm: null
,10-04 12:02:00.898  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
,10-04 12:02:00.898  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:02:00.898  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:02:00.898  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable
10-04 12:02:00.898  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:02:00.898  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
10-04 12:02:00.898  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
10-04 12:02:00.898  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
10-04 12:02:00.898  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:02:00.898  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:02:00.898  3438  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-04 12:02:00.898  3438  3552 D PowerManagerService: mDisplayReady: true
10-04 12:02:00.898  3438  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,10-04 12:02:00.908  4707  4707 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,10-04 12:02:00.908  4707  4707 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
10-04 12:02:00.908  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-04 12:02:00.908  9352  9416 I jxcore-log: 
,10-04 12:02:00.908  4707  4707 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:wt., 4 paź 12:02
10-04 12:02:00.908  4707  4707 I AODService.ClockTimer: startAlarm : TICK
,10-04 12:02:00.908  3438  4319 V AlarmManager: Add whitelist package alarm :PendingIntent{4f90bb1: PendingIntentRecord{1a3f31c com.samsung.android.app.aodservice broadcastIntent}}
,10-04 12:02:00.908  4707  4707 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,10-04 12:02:00.908  4707  4707 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
10-04 12:02:00.908  3438  4602 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
10-04 12:02:00.908  3438  4602 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,10-04 12:02:00.908  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-04 12:02:00.908  9352  9416 I jxcore-log: 
10-04 12:02:00.908  3438  4932 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3438
,10-04 12:02:00.918  4707  4707 D DefaultClockView: RootView invalidate()
,10-04 12:02:00.918  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-04 12:02:00.918  9352  9416 I jxcore-log: 
10-04 12:02:00.918  3438  3460 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3438
,10-04 12:02:00.928  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-04 12:02:00.928  9352  9416 I jxcore-log: 
,10-04 12:02:00.928  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-04 12:02:00.928  9352  9416 I jxcore-log: 
,10-04 12:02:00.928  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-04 12:02:00.928  9352  9416 I jxcore-log: 
,10-04 12:02:00.938  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-04 12:02:00.938  9352  9416 I jxcore-log: 
,10-04 12:02:00.938  3165  3207 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
10-04 12:02:00.938  3438  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
10-04 12:02:00.938  3438  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 2, 0,
10-04 12:02:00.938  3438  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 2, 0
10-04 12:02:00.938  3165  3208 D Sensorhubs: sendContextData: -63, 14, 10, 2, 0
10-04 12:02:00.938  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-04 12:02:00.938  9352  9416 I jxcore-log: 
,10-04 12:02:00.938  3438  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
10-04 12:02:00.938  3438  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
10-04 12:02:00.938  3438  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
10-04 12:02:00.948  3438  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,10-04 12:02:00.948  3438  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
10-04 12:02:00.948  3438  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
,10-04 12:02:00.948  4707  4707 I AODService: onSContextChanged: AODScreenShown state is already true
,10-04 12:02:00.958  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-04 12:02:00.958  9352  9416 I jxcore-log: 
,10-04 12:02:00.958  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-04 12:02:00.958  9352  9416 I jxcore-log: 
,10-04 12:02:00.968  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-04 12:02:00.968  9352  9416 I jxcore-log: 
,10-04 12:02:00.968  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-04 12:02:00.968  9352  9416 I jxcore-log: 
,10-04 12:02:00.978  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-04 12:02:00.978  9352  9416 I jxcore-log: 
,10-04 12:02:00.988  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-04 12:02:00.988  9352  9416 I jxcore-log: 
,10-04 12:02:00.988  9352  9416 I jxcore-log: 2016-10-04 10:02:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-04 12:02:00.988  9352  9416 I jxcore-log: 
,10-04 12:02:00.998  9352  9416 D BluetoothAdapter: STATE_ON
,10-04 12:02:01.008  9352  9416 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-04 12:02:01.008  9352  9416 I jxcore-log: 2016-10-04 10:02:01 - INFO testUtils: 'BLE multiple advertisement supported'
10-04 12:02:01.008  9352  9416 I jxcore-log: 
,10-04 12:02:01.018  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:01.068  3438  3438 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3438 (0x0)
,10-04 12:02:01.068  3438  3438 I libsuspend: !@autosuspend_wakeup_count_disable
10-04 12:02:01.068  3438  3438 D PowerManagerService: mDisplayReady: false
10-04 12:02:01.068  3438  3438 I libsuspend: !@autosuspend_wakeup_count_disable done
10-04 12:02:01.068  3438  3438 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,10-04 12:02:01.068  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:02:01.068  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:02:01.068  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fac783c00
10-04 12:02:01.068  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:02:01.068  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
10-04 12:02:01.068  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:02:01.068  3438  3563 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
10-04 12:02:01.068  3438  3544 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
10-04 12:02:01.068  3438  3544 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,10-04 12:02:01.088  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:02:01.088  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:02:01.088  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable
10-04 12:02:01.088  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:02:01.088  3438  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
10-04 12:02:01.088  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:02:01.088  3438  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
10-04 12:02:01.088  3438  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
10-04 12:02:01.088  3438  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
10-04 12:02:01.088  3438  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-04 12:02:01.088  3438  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-04 12:02:01.088  3438  3552 D PowerManagerService: mDisplayReady: true
10-04 12:02:01.088  3438  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,10-04 12:02:01.198  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:01.268  9352  9416 I jxcore-log: 2016-10-04 10:02:01 - DEBUG CoordinatedClient: 'connected to the test server'
10-04 12:02:01.268  9352  9416 I jxcore-log: 
,10-04 12:02:01.378  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:01.518  9352  9416 I jxcore-log: 2016-10-04 10:02:01 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-04 12:02:01.518  9352  9416 I jxcore-log: 
,10-04 12:02:01.518  9352  9416 I jxcore-log: 2016-10-04 10:02:01 - DEBUG CoordinatedClient: 'test client failed'
10-04 12:02:01.518  9352  9416 I jxcore-log: 
,10-04 12:02:01.528  9352  9416 I jxcore-log: 2016-10-04 10:02:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-04 12:02:01.528  9352  9416 I jxcore-log: 
,10-04 12:02:01.528  9352  9416 I jxcore-log: 2016-10-04 10:02:01 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-04 12:02:01.528  9352  9416 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-04 12:02:01.528  9352  9416 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-04 12:02:01.528  9352  9416 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-04 12:02:01.528  9352  9416 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-04 12:02:01.528  9352  9416 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-04 12:02:01.528  9352  9416 I jxcore-log: 
,10-04 12:02:01.528  9352  9416 I jxcore-log: 2016-10-04 10:02:01 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-04 12:02:01.528  9352  9416 I jxcore-log: 
,10-04 12:02:01.558  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:01.738  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:01.918  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:01.988  9427  9427 I FIPS_bssl: FIPS approved mode (1) | 9427 | app_process
,10-04 12:02:01.988  9427  9427 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-04 12:02:01.998  9427  9427 D AndroidRuntime: CheckJNI is OFF
10-04 12:02:01.998  9427  9427 D AndroidRuntime: readGMSProperty: start
10-04 12:02:01.998  9427  9427 D AndroidRuntime: readGMSProperty: already setted!!
10-04 12:02:01.998  9427  9427 D AndroidRuntime: propertySet: couldn't set property (it is from app)
10-04 12:02:01.998  9427  9427 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
10-04 12:02:01.998  9427  9427 D AndroidRuntime: readGMSProperty: end
10-04 12:02:01.998  9427  9427 D AndroidRuntime: addProductProperty: start
,10-04 12:02:02.018  9427  9427 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-04 12:02:02.038  9427  9427 I Radio-JNI: register_android_hardware_Radio DONE
,10-04 12:02:02.038  9427  9427 E AffinityControl: AffinityControl: registerfunction enter
,10-04 12:02:02.048  9427  9427 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-04 12:02:02.058  3438  3462 D PackageManager: START PACKAGE DELETE: observer{192944278}
10-04 12:02:02.058  3438  3462 D PackageManager: pkg{<packageName>}
10-04 12:02:02.058  3438  3462 D PackageManager: user{0}
10-04 12:02:02.058  3438  3462 D PackageManager: caller{2000}
10-04 12:02:02.058  3438  3462 D PackageManager: flags{2}
,10-04 12:02:02.058  3438  3462 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
10-04 12:02:02.058  3438  3462 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
10-04 12:02:02.058  3438  3462 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
10-04 12:02:02.058  3438  3462 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
10-04 12:02:02.058  3438  3462 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,10-04 12:02:02.058  3438  3571 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
10-04 12:02:02.058  3438  3571 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
10-04 12:02:02.058  3438  3571 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
10-04 12:02:02.058  3438  3571 D ApplicationPolicy: getApplicationUninstallationEnabled
,10-04 12:02:02.058  3438  3571 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
10-04 12:02:02.058  3438  3571 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
10-04 12:02:02.058  3438  3571 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,10-04 12:02:02.058  3438  3571 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
10-04 12:02:02.058  3438  3571 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
10-04 12:02:02.058  3438  3514 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
10-04 12:02:02.058  3438  3571 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
10-04 12:02:02.058  3438  3514 I ActivityManager: Killing 9352:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,10-04 12:02:02.068  3438  3514 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON,
,10-04 12:02:02.068  3438  3514 D ActivityManager: mDVFSHelper.acquire()
,10-04 12:02:02.088  9436  9436 E Zygote  : v2
10-04 12:02:02.088  9436  9436 I libpersona: KNOX_SDCARD checking this for 10171
10-04 12:02:02.088  3438  3571 D AASAinstall: there is not AASApackages.xml file
10-04 12:02:02.088  9436  9436 I libpersona: KNOX_SDCARD not a persona
10-04 12:02:02.088  9436  9436 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
10-04 12:02:02.088  9436  9436 E Zygote  : accessInfo : 0
10-04 12:02:02.088  9436  9436 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
10-04 12:02:02.088  3438  3514 I ActivityManager: Start proc 9436:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
,10-04 12:02:02.098  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:02.098  3438  3514 I ActivityManager:   Force finishing activity ActivityRecord{c4e4962 u0 com.test.thalitest/.MainActivity t4}
10-04 12:02:02.098  3438  3514 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,10-04 12:02:02.098  9436  9436 D TimaKeyStoreProvider: TimaSignature is unavailable
10-04 12:02:02.098  9436  9436 D ActivityThread: Added TimaKeyStore provider
,10-04 12:02:02.178  3438  4932 D GraphicsStats: Buffer count: 5
,10-04 12:02:02.178  3438  3958 I WindowState: WIN DEATH: Window{f9369e6 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-04 12:02:02.178  3438  4306 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@cfa0070)
,10-04 12:02:02.178  3438  3865 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-04 12:02:02.178  3438  3865 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-04 12:02:02.188  3438  3865 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-04 12:02:02.188  3006  3014 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
,10-04 12:02:02.188  3006  3014 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
10-04 12:02:02.188  3006  4360 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,10-04 12:02:02.278  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,10-04 12:02:02.308  3438  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,10-04 12:02:02.348  3438  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,10-04 12:02:02.348  3438  3544 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,10-04 12:02:02.348  3438  3544 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
10-04 12:02:02.348  3163  3163 W keystore: ENTER clear_uid from uid 1000 for 10171
10-04 12:02:02.348  3438  3544 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
10-04 12:02:02.348  3438  3544 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
10-04 12:02:02.348  3438  3544 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
10-04 12:02:02.348  3438  3544 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
10-04 12:02:02.348  3438  3544 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-04 12:02:02.348  3438  3544 W System.err: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:02:02.348  3438  3571 I art     : Starting a blocking GC Explicit
10-04 12:02:02.348  3438  3544 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-04 12:02:02.348  3438  3544 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-04 12:02:02.348  3438  3544 D SecWifiDisplayUtil: Metadata value : SecSettings2
10-04 12:02:02.348  3438  3544 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9347fe9 V.E...... R.....ID 0,0-0,0}
,10-04 12:02:02.358  3438  3514 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,10-04 12:02:02.358  3438  3544 W WindowManager: Failed looking up window
10-04 12:02:02.358  3438  3544 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2c8b70f does not exist
10-04 12:02:02.358  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-04 12:02:02.358  3438  3544 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-04 12:02:02.358  3438  3544 D ISSUE_DEBUG: InputChannelName : bd6b39c Starting com.test.thalitest
,10-04 12:02:02.368  3438  3438 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,10-04 12:02:02.378  3006  3006 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,10-04 12:02:02.388  3438  3514 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,10-04 12:02:02.398  3438  4931 I ActivityManager: Killing 8249:com.google.android.talk/u0a112 (adj 15): DHA:empty #33
,10-04 12:02:02.398  4307  4307 D Launcher: onRestart, Launcher: 209628761
,10-04 12:02:02.408  3438  3514 D InputDispatcher: Focused application released
10-04 12:02:02.408  9436  9436 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,10-04 12:02:02.418  3438  3544 E ViewSystem: ViewRootImpl #2 Surface is not valid.
10-04 12:02:02.418  3438  3544 W WindowManager: Failed looking up window
10-04 12:02:02.418  3438  3544 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2c8b70f does not exist
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:5208)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:208)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6690)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1994)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7403)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-04 12:02:02.418  3438  3544 D ViewRootImpl: #3 mView = null
10-04 12:02:02.418  3438  4370 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
10-04 12:02:02.418  9436  9436 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
10-04 12:02:02.418  3438  3544 W WindowManager: Failed looking up window
10-04 12:02:02.418  3438  3544 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2c8b70f does not exist
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4612)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3754)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6893)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4238)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:02:02.418  3438  3544 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-04 12:02:02.418  3438  3544 W Win,dowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-04 12:02:02.418  4307  4307 D Launcher: onStart, Launcher: 209628761
10-04 12:02:02.418  4307  4307 D Launcher.HomeView: onStart
10-04 12:02:02.418  3438  4305 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
10-04 12:02:02.418  3438  4305 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:02:02.418  3438  3438 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:02:02.418  4307  4307 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
10-04 12:02:02.428  4307  4307 V ActivityThread: updateVisibility : ActivityRecord{ef96f76 token=android.os.BinderProxy@613c8cc {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
10-04 12:02:02.428  3438  3438 I KnoxTimeoutHandler: Shared devices show user statefalse
10-04 12:02:02.428  3438  3438 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
10-04 12:02:02.428  4307  4307 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
10-04 12:02:02.428  4307  4307 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
10-04 12:02:02.428  4307  4307 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
10-04 12:02:02.428  4307  4307 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
10-04 12:02:02.428  4307  4307 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
10-04 12:02:02.428  4307  4307 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
10-04 12:02:02.428  4307  4307 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
10-04 12:02:02.428  4307  4307 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
10-04 12:02:02.428  4307  4307 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
10-04 12:02:02.438  3438  5947 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
10-04 12:02:02.438  3006  3006 I SurfaceFlinger: id=21 createSurf (1440x2560),1 flag=4, MauncherAct
10-04 12:02:02.438  9436  9436 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
10-04 12:02:02.438  9436  9436 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
10-04 12:02:02.438  9436  9436 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
10-04 12:02:02.438  9436  9436 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
10-04 12:02:02.448  3438  3571 I art     : Explicit concurrent mark sweep GC freed 176878(10MB) AllocSpace objects, 6(2MB) LOS objects, 32% free, 33MB/49MB, paused 1.110ms total 98.858ms
10-04 12:02:02.448  9436  9436 I InjectionManager: Inside getClassLibPath caller 
10-04 12:02:02.448  4307  4596 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
10-04 12:02:02.448  9436  9436 W System  : ClassLoader referenced unknown path: /data/app/com.test.thalitest-1/base.apk
,10-04 12:02:02.458  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:02:02.458  3438  3959 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,10-04 12:02:02.458  3438  3571 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
10-04 12:02:02.458  3438  3571 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
10-04 12:02:02.458  3438  3571 D AASAinstall: there is not AASApackages.xml file
10-04 12:02:02.458  3438  3571 D PackageManager: result of delete: 1{192944278}
,10-04 12:02:02.468  9436  9436 D AndroidRuntime: Shutting down VM
,10-04 12:02:02.468  9436  9436 E AndroidRuntime: FATAL EXCEPTION: main
10-04 12:02:02.468  9436  9436 E AndroidRuntime: Process: com.test.thalitest, PID: 9436
10-04 12:02:02.468  9436  9436 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6294)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:222)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1861)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7229)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
10-04 12:02:02.468  9436  9436 E AndroidRuntime: 	... 9 more
,10-04 12:02:02.468  3438  3571 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
10-04 12:02:02.468  3438  3571 D PackageManager: userId{-1}
10-04 12:02:02.468  3438  3571 D PackageManager: andCode{true}
10-04 12:02:02.468  9427  9427 I art     : System.exit called, status: 0
10-04 12:02:02.468  9427  9427 I AndroidRuntime: VM exiting with result code 0.
,10-04 12:02:02.488  3438  4370 V WindowStateAnimator: Finishing drawing window Window{a36947e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,10-04 12:02:02.488  3006  3006 I SurfaceFlinger: id=22 createSurf (1592x384),1 flag=4, VSBConnecti
10-04 12:02:02.488  3438  3571 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
10-04 12:02:02.488  3438  3571 I ActivityManager: Killing 9436:com.test.thalitest/u0a171 (adj 9): stop com.test.thalitest cause pkg removed
,10-04 12:02:02.498  3438  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,10-04 12:02:02.498  3438  5947 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,10-04 12:02:02.498  3438  3571 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,10-04 12:02:02.508  3438  4305 V WindowStateAnimator: Finishing drawing window Window{caa0351 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
10-04 12:02:02.508  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd6fa4ac8
10-04 12:02:02.508  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd6fa4ac8
10-04 12:02:02.508  6038  6038 V ActivityThread: updateVisibility : ActivityRecord{c8576f0 token=android.os.BinderProxy@b88d95d {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,10-04 12:02:02.528  8811  9452 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,10-04 12:02:02.538  8811  9452 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,10-04 12:02:02.538  8811  9452 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,10-04 12:02:02.538  3438  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:02:02.548  3438  3544 D ActivityManager: mDVFSHelper.release()
10-04 12:02:02.548  3438  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3cea9e8 u0 com.samsung.android.MtpApplication/.USBConnection t3} time:259890
10-04 12:02:02.548  3438  3438 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,10-04 12:02:02.558  3438  3438 I KnoxTimeoutHandler: SD activityfalse
,10-04 12:02:02.568  3438  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,10-04 12:02:02.568  3438  5947 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
10-04 12:02:02.568  3438  5947 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
10-04 12:02:02.568  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,10-04 12:02:02.578  3438  4595 V WindowStateAnimator: Finishing drawing window Window{d4eca2c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,10-04 12:02:02.578  6038  6038 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b88d95d time:259921,
10-04 12:02:02.578  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.578  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fd6fa4ac8
,10-04 12:02:02.578  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,10-04 12:02:02.578  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,10-04 12:02:02.578  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.578  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,10-04 12:02:02.588  3944  3944 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
,10-04 12:02:02.588  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
10-04 12:02:02.588  3944  3944 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
10-04 12:02:02.588  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,10-04 12:02:02.588  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,10-04 12:02:02.588  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,10-04 12:02:02.588  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.588  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
10-04 12:02:02.588  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,10-04 12:02:02.598  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.598  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
10-04 12:02:02.598  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,10-04 12:02:02.598  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.598  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,10-04 12:02:02.598  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,10-04 12:02:02.598  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.598  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
10-04 12:02:02.598  3438  3509 D AccessibilityManagerService: onUserStateChangedLocked()
10-04 12:02:02.598  3438  3509 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
,10-04 12:02:02.598  4255  4785 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-04 12:02:02.608  5011  5230 D PresenceModule: onReceive: package removed
,10-04 12:02:02.608  5011  5230 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
10-04 12:02:02.608  5011  5230 D PresenceModule: Application package removed
10-04 12:02:02.608  5011  5230 D PresenceModule: onAppPkgRemoved: com.test.thalitest
10-04 12:02:02.608  5011  5230 D PresenceModule: onApplicationPackageRemoved: invalid package
,10-04 12:02:02.618  3438  3509 D EnterpriseDeviceManagerService: Package has changed for user 0
10-04 12:02:02.618  3438  3509 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,10-04 12:02:02.618  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
10-04 12:02:02.618  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,10-04 12:02:02.618  3438  3853 D NtpTrustedTime: currentTimeMillis() cache hit
10-04 12:02:02.618  3438  3853 V NetworkStats: removeUidsLocked() for UIDs [10171]
10-04 12:02:02.618  3438  3853 V NetworkStats: performPollLocked(flags=0x3)
10-04 12:02:02.618  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,10-04 12:02:02.628  3438  3854 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
10-04 12:02:02.628  3438  3854 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
10-04 12:02:02.628  3438  3853 D NetworkStatsRecorder: entry.iface is null
10-04 12:02:02.628  3438  3853 D NetworkStatsRecorder: entry.iface is null
10-04 12:02:02.628  3438  3853 D NetworkStatsRecorder: entry.iface is null
10-04 12:02:02.628  3438  3853 D NetworkStatsRecorder: entry.iface is null
,10-04 12:02:02.628  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.628  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
10-04 12:02:02.628  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,10-04 12:02:02.628  3438  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1475145051467- -> /data/system/netstats/uid.1475145051467-.backup
,10-04 12:02:02.628  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1475145051467-
10-04 12:02:02.628  3438  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1475145051467-.backup -> /data/system/netstats/uid.1475145051467-
,10-04 12:02:02.628  3438  3514 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{78665a0 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{af0f80d 6380:com.samsung.klmsagent/u0a26}
,10-04 12:02:02.628  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.638  3438  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
10-04 12:02:02.638  3438  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6194ce8 u0 com.sec.android.app.launcher/.activities.LauncherActivity t1} time:259981
,10-04 12:02:02.638  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
10-04 12:02:02.638  6380  6380 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Tue Oct 04 12:02:02 GMT+02:00 2016
10-04 12:02:02.638  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
10-04 12:02:02.638  3438  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
10-04 12:02:02.638  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.638  3438  3903 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/4_task.xml
10-04 12:02:02.638  3438  3959 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4808, uid=10124 that is not exported from uid 10122
,10-04 12:02:02.638  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
10-04 12:02:02.638  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,10-04 12:02:02.638  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.648  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,10-04 12:02:02.648  4016  4016 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
,10-04 12:02:02.648  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.648  3438  3853 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop96.tmp
10-04 12:02:02.648  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,10-04 12:02:02.648  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1475145051467-
10-04 12:02:02.648  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.648  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201655233-1473847639678
,10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.648  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-1475144767573
10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.648  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.648  3438  3853 E DropBoxManagerService: Can't write: netstats_dump
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1222)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-04 12:02:02.648  3438  3853 E DropBoxManagerService: 	... 16 more
10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.648  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
10-04 12:02:02.648  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
10-04 12:02:02.658  3438  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1475475191627- -> /data/system/netstats/uid_tag.1475475191627-.backup
10-04 12:02:02.658  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
,10-04 12:02:02.658  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1475475191627-
,10-04 12:02:02.658  3438  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1475475191627-.backup -> /data/system/netstats/uid_tag.1475475191627-
,10-04 12:02:02.658  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.658  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
10-04 12:02:02.668  3438  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,10-04 12:02:02.668  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: Can't write: netstats_dump
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1223)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-04 12:02:02.668  3438  3853 E DropBoxManagerService: 	... 16 more
10-04 12:02:02.668  3438  3853 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop96.tmp
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.668  4291  4291 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
10-04 12:02:02.668  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1475475191627-
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.668  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157707-1474873077928
10-04 12:,02:02.668  3438  3544 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
10-04 12:02:02.668  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1473847817708-1474285028441
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.668  3438  3853 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474883348145-1475474934622
10-04 12:02:02.668  3438  3853 V NetworkStats: performPollLocked() took 47ms
10-04 12:02:02.668  3438  3853 D NtpTrustedTime: currentTimeMillis() cache hit
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
10-04 12:02:02.668  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.668  3438  3544 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.668  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.668  4307  4307 D Launcher.HomeView: onStop
10-04 12:02:02.668  3438  3544 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
10-04 12:02:02.668  4307  4307 D capture : ----destroy
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
10-04 12:02:02.668  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
10-04 12:02:02.678  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
10-04 12:02:02.678  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
10-04 12:02:02.678  3438  3829 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-04 12:02:02.678  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.678  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
10-04 12:02:02.678  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
10-04 12:02:02.678  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
10-04 12:02:02.678  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
10-04 12:02:02.678  6380  6380 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive().END.
10-04 12:02:02.678  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.688  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
10-04 12:02:02.688  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
10-04 12:02:02.688  3438  3854 D NtpTrustedTime: currentTimeMillis() cache hit
10-04 12:02:02.688  3438  3854 D NtpTrustedTime: currentTimeMillis() cache hit
10-04 12:02:02.688  3438  3878 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
10-04 12:02:02.688  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.688  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
10-04 12:02:02.688  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
10-04 12:02:02.688  6380  6380 I KLMS-2.6.201: : KLMSIntentService(): onCreate()
10-04 12:02:02.688  6380  6380 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
10-04 12:02:02.698  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
10-04 12:02:02.698  3438  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.698  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  3438  3509 D ResourcesManager: For user 0 new overlays fetched Null
,10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  6380  6380 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  6380  9456 I KLMS-2.6.201: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  6380  9456 D KLMS-2.6.201: : KLMSIntentService(): PACKAGE_REMOVED
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  6380  9456 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().START
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  6380  9456 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  6380  9456 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  6380  9456 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
10-04 12:02:02.708  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
10-04 12:02:02.708  3438  3509 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
10-04 12:02:02.708  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.718  6380  9456 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
10-04 12:02:02.718  6380  9456 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
10-04 12:02:02.718  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.718  6380  9456 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.718  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.728  6380  9456 D KLMS-2.6.201: : Systemprocess(): arrayLicenseInfo is null
10-04 12:02:02.728  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.728  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.728  4279  9458 D RegisteredComponentCache: Collect Tech packages for Knox
10-04 12:02:02.728  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
10-04 12:02:02.728  4279  9458 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
10-04 12:02:02.728  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.728  4279  9458 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
10-04 12:02:02.728  4279  9458 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
10-04 12:02:02.728  4279  9458 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
10-04 12:02:02.728  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.728  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.728  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3978 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{78665a0 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{684a3bd 3438:system/1000}
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
10-04 12:02:02.738  3438  3438 D ResourcesManager: For user 0 new overlays fetched Null
10-04 12:02:02.738  6380  9456 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
10-04 12:02:02.738  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
10-04 12:02:02.748  3438  3438 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud

```
