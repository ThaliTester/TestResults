#### Test 861725253aa3a32_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-23 16:24:47.484  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:47.664  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:47.844  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:48.024  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:48.204  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:48.284  9338  9338 I FIPS_bssl: FIPS approved mode (1) | 9338 | app_process
09-23 16:24:48.294  9338  9338 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 16:24:48.294  9338  9338 D AndroidRuntime: CheckJNI is OFF
09-23 16:24:48.294  9338  9338 D AndroidRuntime: readGMSProperty: start
09-23 16:24:48.294  9338  9338 D AndroidRuntime: readGMSProperty: already setted!!
09-23 16:24:48.294  9338  9338 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 16:24:48.294  9338  9338 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 16:24:48.294  9338  9338 D AndroidRuntime: readGMSProperty: end
09-23 16:24:48.294  9338  9338 D AndroidRuntime: addProductProperty: start
09-23 16:24:48.314  9338  9338 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 16:24:48.334  9338  9338 I Radio-JNI: register_android_hardware_Radio DONE
09-23 16:24:48.344  9338  9338 E AffinityControl: AffinityControl: registerfunction enter
09-23 16:24:48.344  9338  9338 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-23 16:24:48.374  3385  4938 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-23 16:24:48.384  3385  4938 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 16:24:48.384  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:48.404  3385  4938 D ResourcesManager: For user 0 new overlays fetched Null
09-23 16:24:48.404  3385  4938 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 16:24:48.404  3385  4938 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-23 16:24:48.404  3385  4938 D ActivityManager: mDVFSHelper.acquire()
09-23 16:24:48.414  3385  4938 V WindowManager: addAppToken: AppWindowToken{d0e681804 token=Token{c78cc17 ActivityRecord{a184896 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-23 16:24:48.414  3385  3549 I InjectionManager: Inside getClassLibPath caller 
09-23 16:24:48.424  3385  3549 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 16:24:48.424  3385  3549 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ce8639c V.E...... R.....ID 0,0-0,0}
09-23 16:24:48.434  3385  3549 W WindowManager: Failed looking up window
09-23 16:24:48.434  3385  3549 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@3f421a5 does not exist
09-23 16:24:48.434  3385  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 16:24:48.434  3385  3549 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 16:24:48.434  9347  9347 E Zygote  : v2
09-23 16:24:48.434  9347  9347 I libpersona: KNOX_SDCARD checking this for 10171
09-23 16:24:48.434  3385  3549 D ISSUE_DEBUG: InputChannelName : bd0c97a Starting com.test.thalitest
09-23 16:24:48.434  9347  9347 I libpersona: KNOX_SDCARD not a persona
09-23 16:24:48.434  9347  9347 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 16:24:48.434  3385  4938 I ActivityManager: Start proc 9347:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-23 16:24:48.434  9347  9347 E Zygote  : accessInfo : 0
09-23 16:24:48.434  9347  9347 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-23 16:24:48.434  3385  4938 D InputDispatcher: Focused application set to: xxxx
09-23 16:24:48.434  9338  9338 D AndroidRuntime: Shutting down VM
09-23 16:24:48.434  3385  3852 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-23 16:24:48.454  3005  3005 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-23 16:24:48.464  9347  9347 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 16:24:48.464  9347  9347 D ActivityThread: Added TimaKeyStore provider
09-23 16:24:48.494  6048  6048 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 16:24:48.494  3385  4216 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3385
09-23 16:24:48.494  3385  4216 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 16:24:48.494  3385  4216 D PowerManagerService: mDisplayReady: false
09-23 16:24:48.494  3385  4216 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 16:24:48.494  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:24:48.494  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:24:48.494  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:48.494  3385  4216 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 16:24:48.494  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:48.494  6048  6048 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 16:24:48.494  3385  3566 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 16:24:48.494  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb3083c00
09-23 16:24:48.494  3385  3973 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3385
09-23 16:24:48.494  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 16:24:48.504  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:24:48.504  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:24:48.504  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:48.504  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 16:24:48.504  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:48.504  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 16:24:48.504  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:24:48.504  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:24:48.504  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:48.504  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:48.504  3385  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 16:24:48.504  3385  3553 D PowerManagerService: mDisplayReady: true
09-23 16:24:48.504  3385  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 16:24:48.504  3385  4166 D ActivityManager:  Launching com.test.thalitest, updated priority
09-23 16:24:48.514  4277  4277 V ActivityThread: updateVisibility : ActivityRecord{9b342b1 token=android.os.BinderProxy@b0e05ec {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-23 16:24:48.524  3385  4391 V WindowStateAnimator: Finishing drawing window Window{8aeabac u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 16:24:48.524  3385  3385 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-23 16:24:48.524  3385  3512 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-23 16:24:48.534  3005  3013 D libEGL  : eglTerminate EGLDisplay = 0x7fb2e00e78
09-23 16:24:48.534  3005  3013 D libEGL  : eglTerminate EGLDisplay = 0x7fb2e00e78
09-23 16:24:48.554  3005  4481 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-23 16:24:48.554  3005  4475 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-23 16:24:48.554  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff9ae48e8
09-23 16:24:48.564  4277  4277 D Launcher: onTrimMemory. Level: 20
09-23 16:24:48.564  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:48.564  3385  3849 V WindowStateAnimator: Finishing drawing window Window{ebc39fe u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 16:24:48.564  6048  6048 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 16:24:48.564  6048  6048 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 16:24:48.564  6048  6048 V ActivityThread: updateVisibility : ActivityRecord{c46909 token=android.os.BinderProxy@a31c0f2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-23 16:24:48.564  3005  4475 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-23 16:24:48.564  3005  3015 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-23 16:24:48.574  3005  3015 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-23 16:24:48.574  3005  3013 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-23 16:24:48.584  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff9ae48e8
09-23 16:24:48.584  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff9ae48b8
09-23 16:24:48.594  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff9ae48e8
09-23 16:24:48.644  3385  3385 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3385 (0x0)
09-23 16:24:48.644  3385  3385 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3385 (0x0)
09-23 16:24:48.654  3385  3385 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 16:24:48.654  3385  3385 D PowerManagerService: mDisplayReady: false
09-23 16:24:48.654  3385  3385 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 16:24:48.654  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:24:48.654  3385  3385 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 16:24:48.654  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:24:48.654  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:48.654  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:48.654  3385  3566 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 16:24:48.654  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb3083c00
09-23 16:24:48.654  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 16:24:48.654  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:24:48.654  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:24:48.654  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:48.654  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 16:24:48.654  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:48.654  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 16:24:48.654  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:24:48.654  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:24:48.654  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:48.654  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:48.654  3385  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 16:24:48.654  3385  3553 D PowerManagerService: mDisplayReady: true
09-23 16:24:48.654  3385  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 16:24:48.744  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:48.864  3385  4166 I WindowManager: Screenshot max retries 4 of Token{c78cc17 ActivityRecord{a184896 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{bd0c97a u0 d0 Starting com.test.thalitest} drawState=1
09-23 16:24:48.864  3385  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 16:24:48.864  3385  3549 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 16:24:48.864  3385  3385 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 16:24:48.874  3385  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 16:24:48.874  3385  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 16:24:48.874  3385  3852 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-23 16:24:48.894  3385  3385 I KnoxTimeoutHandler: SD activityfalse
09-23 16:24:48.904  9347  9347 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 16:24:48.904  3385  4276 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-23 16:24:48.904  9347  9347 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-23 16:24:48.914  3385  5945 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 16:24:48.914  3385  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 16:24:48.914  3385  3549 V WindowStateAnimator: Finishing drawing window Window{bd0c97a u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-23 16:24:48.914  3385  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 16:24:48.914  3385  3549 D ActivityManager: mDVFSHelper.release()
09-23 16:24:48.914  3385  3385 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 16:24:48.914  3385  3549 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d51c368 u0 com.samsung.android.MtpApplication/.USBConnection t3} time:250508
09-23 16:24:48.924  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:48.934  3385  3385 I KnoxTimeoutHandler: SD activityfalse
09-23 16:24:48.934  9347  9347 D ResourcesManager: For user 0 new overlays fetched Null
09-23 16:24:48.934  3385  5945 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 16:24:48.944  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7ff9ae47c8
09-23 16:24:48.944  9347  9347 I InjectionManager: Inside getClassLibPath caller 
09-23 16:24:48.944  3385  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 16:24:48.944  3385  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 16:24:48.954  9347  9347 D InjectionManager: InjectionManager
09-23 16:24:48.954  9347  9347 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-23 16:24:48.954  9347  9347 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-23 16:24:48.954  9347  9347 I InjectionManager: featureStore :{}
09-23 16:24:48.964  9347  9347 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 16:24:48.964  9347  9347 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-23 16:24:48.964  9347  9347 D RelationGraph: garbageCollect()
09-23 16:24:48.974  9347  9347 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 16:24:49.004  9347  9347 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-23 16:24:49.044  9347  9347 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-23 16:24:49.054  9347  9347 D ResourcesManager: For user 0 new overlays fetched Null
09-23 16:24:49.054  9347  9347 I InjectionManager: Inside getClassLibPath caller 
09-23 16:24:49.054  9347  9347 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-23 16:24:49.104  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:49.114  9347  9347 I cr_LibraryLoader: Time to load native libraries: 34 ms (timestamps 666-700)
09-23 16:24:49.114  9347  9347 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 16:24:49.124  3385  3875 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-23 16:24:49.184  9347  9363 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-23 16:24:49.204  9347  9347 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1412d2f}
09-23 16:24:49.204  9347  9347 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 16:24:49.224  3385  3875 I MdnieScenarioControlService: mGameModeLauncher : false
09-23 16:24:49.224  3385  3875 I MdnieScenarioControlService: setUIMode
09-23 16:24:49.224  9347  9347 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 16:24:49.264  9347  9347 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-23 16:24:49.284  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:49.364  3385  3512 W ActivityManager: Activity pause timeout for ActivityRecord{a184896 u0 com.test.thalitest/.MainActivity t4}
09-23 16:24:49.464  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:49.464  9347  9347 D libEGL  : eglInitialize EGLDisplay = 0xff8ff10c
,09-23 16:24:49.584  3385  3448 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-23 16:24:49.584  3385  3448 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-23 16:24:49.644  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:49.674  9347  9347 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-23 16:24:49.694  9347  9347 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 16:24:49.694  9347  9347 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-23 16:24:49.734  9347  9347 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-23 16:24:49.794  9347  9347 D Activity: performCreate Call Injection manager
,09-23 16:24:49.794  9347  9347 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-23 16:24:49.804  9347  9347 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 16:24:49.814  9347  9347 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3bb317a I.E...... R.....ID 0,0-0,0}
,09-23 16:24:49.814  9347  9400 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 16:24:49.824  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:49.824  3385  4289 W WindowManager: Failed looking up window
09-23 16:24:49.824  3385  4289 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@7775685 does not exist
09-23 16:24:49.824  3385  4289 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 16:24:49.824  3385  4289 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 16:24:49.824  3385  4289 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 16:24:49.824  3385  4289 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-23 16:24:49.824  3385  4289 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-23 16:24:49.824  3385  4289 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 16:24:49.824  3385  4166 D ISSUE_DEBUG: InputChannelName : a0a8cda com.test.thalitest/com.test.thalitest.MainActivity
,09-23 16:24:49.834  3385  4421 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-23 16:24:49.834  3385  4421 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 16:24:49.834  3385  3385 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-23 16:24:49.834  3385  3385 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-23 16:24:49.834  9347  9347 V ActivityThread: updateVisibility : ActivityRecord{a9ac588 token=android.os.BinderProxy@a5ab8c2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-23 16:24:49.844  9347  9363 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-23 16:24:49.864  3385  5946 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-23 16:24:49.874  9347  9347 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9347
,09-23 16:24:49.884  3385  3447 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9347 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 16:24:49.884  3385  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-23 16:24:49.884  3385  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 16:24:49.894  3385  3863 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-23 16:24:49.894  3385  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 16:24:49.904  3385  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 16:24:49.904  9347  9347 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 16:24:49.904  3385  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-23 16:24:49.914  3385  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 16:24:49.914  3385  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-23 16:24:49.914  3385  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 16:24:49.924  3005  3005 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-23 16:24:49.954  9347  9400 D libEGL  : eglInitialize EGLDisplay = 0xdc2bf7c4
09-23 16:24:49.954  9347  9400 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 16:24:49.964  9347  9400 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-23 16:24:49.964  3385  4289 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 16:24:49.964  3385  4289 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3385
,09-23 16:24:49.964  3385  4289 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 16:24:49.964  3385  4289 D PowerManagerService: mDisplayReady: false
09-23 16:24:49.964  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:24:49.964  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb3083c00
,09-23 16:24:49.964  3385  4289 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 16:24:49.964  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 16:24:49.964  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:24:49.964  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:49.964  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:49.964  3385  3566 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,09-23 16:24:49.964  3385  3549 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 16:24:49.964  3385  3549 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-23 16:24:49.974  3005  3050 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=251564607703)
,09-23 16:24:49.984  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:24:49.984  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:24:49.984  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:49.984  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 16:24:49.984  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:49.984  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 16:24:49.984  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:24:49.984  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:24:49.984  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:49.984  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:49.984  3385  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 16:24:49.984  3385  3553 D PowerManagerService: mDisplayReady: true
09-23 16:24:49.984  3385  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 16:24:49.994  9347  9347 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-23 16:24:50.004  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:50.014  3385  3447 V WindowStateAnimator: Finishing drawing window Window{a0a8cda u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-23 16:24:50.014  9347  9347 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-23 16:24:50.014  9347  9404 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 16:24:50.014  9347  9404 D libEGL  : eglInitialize EGLDisplay = 0xdbbf63f4
,09-23 16:24:50.024  3385  4421 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3385
09-23 16:24:50.024  3385  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 16:24:50.024  3385  3385 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 16:24:50.024  3385  3549 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s162ms (total +1s611ms)
09-23 16:24:50.024  3385  4166 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3385
09-23 16:24:50.024  3385  3549 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a184896 u0 com.test.thalitest/.MainActivity t4} time:251615
09-23 16:24:50.024  3385  3549 D ViewRootImpl: #3 mView = null
09-23 16:24:50.024  3005  4481 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-23 16:24:50.024  3385  3385 I KnoxTimeoutHandler: SD activityfalse
,09-23 16:24:50.024  3005  4475 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-23 16:24:50.034  9347  9404 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-23 16:24:50.034  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff9ae48e8
,09-23 16:24:50.044  3385  3973 V WindowStateAnimator: Finishing drawing window Window{a0a8cda u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-23 16:24:50.044  9347  9347 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a5ab8c2 time:251634
,09-23 16:24:50.094  9347  9347 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9347
,09-23 16:24:50.174  3385  3385 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3385 (0x0)
09-23 16:24:50.174  3385  3385 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 16:24:50.174  3385  3385 D PowerManagerService: mDisplayReady: false
09-23 16:24:50.174  3385  3385 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 16:24:50.174  3385  3385 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 16:24:50.174  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:24:50.174  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:24:50.174  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:50.174  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:50.174  3385  3566 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-23 16:24:50.174  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb3083c00
09-23 16:24:50.174  3385  3549 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 16:24:50.174  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 16:24:50.174  3385  3549 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-23 16:24:50.184  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:50.204  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:24:50.204  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:24:50.204  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:50.204  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 16:24:50.204  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:50.204  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 16:24:50.204  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:24:50.204  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:24:50.204  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:24:50.204  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:24:50.204  3385  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 16:24:50.204  3385  3553 D PowerManagerService: mDisplayReady: true
09-23 16:24:50.204  3385  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 16:24:50.314  9347  9347 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 16:24:50.364  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:50.364  4015  4015 D Recents : onTaskStackChanged
,09-23 16:24:50.374  4015  4015 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-23 16:24:50.374  4015  4015 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 16:24:50.414  9347  9411 D jxcore_app_log: JniHelper::setJavaVM(0xf4a34000), pthread_self() = -634390224
,09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802ed2a added. We now have 1 listener(s)
,09-23 16:24:50.424  9347  9411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-23 16:24:50.424  9347  9411 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 16:24:50.424  9347  9411 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 16:24:50.424  9347  9411 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-23 16:24:50.424  9347  9411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c2ae91 added. We now have 1 listener(s)
09-23 16:24:50.424  9347  9411 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 16:24:50.424  9347  9411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 16:24:50.424  9347  9411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 16:24:50.424  9347  9411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 16:24:50.424  9347  9411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-23 16:24:50.434  9347  9411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 16:24:50.434  9347  9411 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:24:50.434  9347  9411 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-23 16:24:50.444  9347  9411 D BluetoothAdapter: STATE_ON
,09-23 16:24:50.444  9347  9411 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 16:24:50.444  9347  9411 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 16:24:50.444  9347  9411 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 16:24:50.444  9347  9411 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 16:24:50.444  9347  9411 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 16:24:50.444  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:24:50.454  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:24:50.474  9347  9347 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 16:24:50.544  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:50.724  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:50.764  3385  5945 D SSRM:n  : SIOP:: AP = 280, PST = 277 (W:10), CP = 233, LCD = 1
,09-23 16:24:50.864  9347  9412 W jxcore-log: Initializing JXcore engine
09-23 16:24:50.864  9347  9412 W jxcore-log: JXcore engine is ready
,09-23 16:24:50.874  4978  4978 E audit   : type=1400 msg=audit(1474640690.874:264): avc:  denied  { ioctl } for  pid=9412 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2091 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 16:24:50.874  4978  4978 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 16:24:50.874  4978  4978 E audit   : type=1300 msg=audit(1474640690.874:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d993f3c8 items=0 ppid=3181 pid=9412 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 16:24:50.874  4978  4978 E audit   : type=1327 msg=audit(1474640690.874:264): proctitle="com.test.thalitest"
09-23 16:24:50.874  4978  4978 E audit   : type=1320 msg=audit(1474640690.874:264): 
09-23 16:24:50.874  4978  4978 E audit   : type=1400 msg=audit(1474640690.874:265): avc:  denied  { ioctl } for  pid=9412 comm="Thread-160" path="socket:[37051]" dev="sockfs" ino=37051 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 16:24:50.874  4978  4978 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 16:24:50.874  4978  4978 E audit   : type=1300 msg=audit(1474640690.874:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d993f3c8 items=0 ppid=3181 pid=9412 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 16:24:50.874  4978  4978 E audit   : type=1327 msg=audit(1474640690.874:265): proctitle="com.test.thalitest"
09-23 16:24:50.874  4978  4978 E audit   : type=1320 msg=audit(1474640690.874:265): 
,09-23 16:24:50.884  9347  9412 W jxcore-log: Starting JXcore engine
,09-23 16:24:50.894  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:50.924  9347  9412 W jxcore-log: Platform android
09-23 16:24:50.924  9347  9412 W jxcore-log: 
09-23 16:24:50.924  9347  9412 W jxcore-log: Process ARCH arm
09-23 16:24:50.924  9347  9412 W jxcore-log: 
,09-23 16:24:50.994  9347  9412 I jxcore-log: JXcore Cordova bridge is ready!
09-23 16:24:50.994  9347  9412 I jxcore-log: 
09-23 16:24:50.994  9347  9412 W jxcore-log: JXcore engine is started
,09-23 16:24:51.004  9347  9411 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 16:24:51.004  9347  9347 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 16:24:51.084  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:51.264  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:51.424  3385  3900 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-23 16:24:51.444  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:51.504  3385  4108 E Watchdog: !@Sync 8 [09-23 16:24:51.515]
,09-23 16:24:51.624  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:51.804  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:51.874  3385  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-23 16:24:51.984  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:52.164  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:52.344  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:52.524  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:52.704  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:52.884  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:52.914  4353  4426 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-23 16:24:52.914  4353  4426 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-23 16:24:53.004  4353  4426 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 0Kb duration : 89ms lastUpdatedAfter : 144873ms
,09-23 16:24:53.064  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:53.244  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:53.424  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:53.594  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:53.784  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:53.964  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:54.144  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:54.324  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:54.504  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:54.684  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:54.864  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:54.954  3385  5945 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-23 16:24:55.044  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:55.224  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:55.404  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:55.584  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:55.764  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:55.944  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:56.124  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:56.304  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:56.484  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:56.654  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:56.834  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:56.864  8179  8202 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-23 16:24:57.014  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:57.054  9347  9412 I jxcore-log: 2016-09-23 14:24:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 16:24:57.054  9347  9412 I jxcore-log: 
,09-23 16:24:57.054  9347  9412 I jxcore-log: 2016-09-23 14:24:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 16:24:57.054  9347  9412 I jxcore-log: 
,09-23 16:24:57.054  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 16:24:57.064  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 16:24:57.064  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.074  9347  9412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 16:24:57.074  9347  9412 I jxcore-log: 2016-09-23 14:24:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 16:24:57.074  9347  9412 I jxcore-log: 
09-23 16:24:57.074  9347  9412 I jxcore-log: 2016-09-23 14:24:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 16:24:57.074  9347  9412 I jxcore-log: 
,09-23 16:24:57.194  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:57.234  9347  9412 I jxcore-log: Running unit tests
09-23 16:24:57.234  9347  9412 I jxcore-log: 
09-23 16:24:57.234  9347  9412 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 16:24:57.234  9347  9412 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e61ce55 added. We now have 2 listener(s)
09-23 16:24:57.234  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 16:24:57.234  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 16:24:57.234  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 16:24:57.234  9347  9412 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 16:24:57.234  9347  9412 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@740f06a added. We now have 2 listener(s)
09-23 16:24:57.234  9347  9412 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 16:24:57.234  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 16:24:57.244  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:24:57.254  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 16:24:57.254  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 16:24:57.264  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.264  9347  9412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 16:24:57.264  9347  9412 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 16:24:57.264  9347  9412 D executeNativeTests: Running unit tests
,09-23 16:24:57.274  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:24:57.274  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:24:57.304  9347  9412 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 16:24:57.304  9347  9412 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe23a41 added. We now have 3 listener(s)
09-23 16:24:57.304  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 16:24:57.304  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 16:24:57.304  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 16:24:57.304  9347  9412 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 16:24:57.304  9347  9412 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 added. We now have 3 listener(s)
09-23 16:24:57.304  9347  9412 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 16:24:57.304  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 16:24:57.304  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:24:57.314  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 16:24:57.324  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 16:24:57.324  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.324  9347  9412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 16:24:57.324  9347  9412 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 16:24:57.324  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 16:24:57.324  9347  9412 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 16:24:57.324  9347  9412 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 16:24:57.324  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 16:24:57.324  9347  9412 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 16:24:57.324  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 16:24:57.324  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 16:24:57.324  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 16:24:57.324  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:24:57.324  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 16:24:57.324  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe23a41 removed from the list
09-23 16:24:57.324  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:24:57.324  9347  9412 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 removed from the list
09-23 16:24:57.334  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectivityMonitor: stop
09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:24:57.334  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:24:57.334  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 16:24:57.334  9347  9412 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 16:24:57.334  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 16:24:57.334  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 16:24:57.334  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:24:57.334  9347  9412 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe23a41 not in the list
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:24:57.334  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 16:24:57.334  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:24:57.334  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:24:57.334  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 16:24:57.334  9347  9412 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 16:24:57.334  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 16:24:57.334  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 16:24:57.334  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:24:57.334  9347  9412 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe23a41 not in the list
09-23 16:24:57.334  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:24:57.334  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
09-23 16:24:57.334  9347  9412 D io.jxcore.node.ConnectivityMonitor: stop
09-23 16:24:57.334  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 16:24:57.334  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:24:57.334  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:24:57.344  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 16:24:57.344  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 16:24:57.344  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:24:57.344  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
09-23 16:24:57.344  9347  9412 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 16:24:57.344  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 16:24:57.344  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 16:24:57.354  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 16:24:57.354  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.354  9347  9412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 16:24:57.354  9347  9412 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 16:24:57.354  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 16:24:57.354  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 16:24:57.354  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 16:24:57.354  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 16:24:57.354  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 16:24:57.364  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 16:24:57.364  9347  9412 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 16:24:57.364  9347  9412 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 16:24:57.364  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 16:24:57.364  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.374  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.374  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.374  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 16:24:57.374  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:57.374  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.384  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.384  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 16:24:57.384  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 16:24:57.384  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.384  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.384  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 16:24:57.384  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.394  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:24:57.394  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 16:24:57.394  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 16:24:57.394  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-23 16:24:57.394  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 16:24:57.394  9347  9412 D BluetoothLeScanner: Start Scan
09-23 16:24:57.394  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.394  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.404  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.404  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.414  4971  4984 D BtGatt.GattService: registerClient() - UUID=a5150bec-1b59-4f6e-9be1-342b9280f96a
,09-23 16:24:57.454  4971  5108 D BtGatt.GattService: onClientRegistered() - UUID=a5150bec-1b59-4f6e-9be1-342b9280f96a, clientIf=7
,09-23 16:24:57.464  9347  9357 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-23 16:24:57.464  4971  5470 D BtGatt.GattService: start scan with filters
,09-23 16:24:57.464  4971  5470 D BtGatt.GattService: getScanSettings
,09-23 16:24:57.484  4971  5470 D BtGatt.GattService: Is it foreground application = true
,09-23 16:24:57.484  4971  5470 D BtGatt.GattService: not a background application
,09-23 16:24:57.504  4971  5470 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 16:24:57.504  4971  5470 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 16:24:57.514  4971  5470 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 16:24:57.514  4971  5165 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 16:24:57.514  4971  5165 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 16:24:57.514  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 16:24:57.514  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 16:24:57.514  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 16:24:57.514  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 16:24:57.514  4971  5156 D BtGatt.ScanManager: handling starting scan
,09-23 16:24:57.514  4971  5156 D BtGatt.ScanManager: isFilteringSupported
09-23 16:24:57.514  4971  5156 D BluetoothAdapter: enableStandAloneBleMode=
,09-23 16:24:57.524  4971  5156 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.524  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 62
,09-23 16:24:57.524  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-23 16:24:57.524  4971  5156 D BluetoothAdapter: STATE_ON
,09-23 16:24:57.534  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 16:24:57.534  4971  5156 D BluetoothAdapter: STATE_ON
09-23 16:24:57.534  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 16:24:57.534  9347  9347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 16:24:57.534  4971  5156 D BluetoothAdapter: STATE_ON
09-23 16:24:57.534  4971  5156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1412d2f
09-23 16:24:57.534  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1
09-23 16:24:57.534  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 16:24:57.534  4971  5165 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577344
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:24:57.544  3385  4391 V AlarmManager:  remove PendingIntent] PendingIntent{9152a73: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
,09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:24:57.544  4971  5108 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
,09-23 16:24:57.544  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-23 16:24:57.544  4971  5165 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577344
09-23 16:24:57.554  9347  9412 I io.jxcore.node.ConnectionHelper: start: OK
09-23 16:24:57.554  4971  5156 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-23 16:24:57.554  4971  5156 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 16:24:57.554  4971  5156 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 16:24:57.554  4971  5156 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-23 16:24:57.554  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8e44d30: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.554  4971  5108 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,09-23 16:24:57.554  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:24:57.554  4971  5156 D BtGatt.ScanManager: Starting BLE batch scan
,09-23 16:24:57.554  4971  5156 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-23 16:24:57.564  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:24:57.564  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{bd9ada9: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.564  4971  5108 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 16:24:57.564  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:24:57.564  4971  5108 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-23 16:24:57.564  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:24:57.564  3385  4937 V AlarmManager:  remove PendingIntent] PendingIntent{84e9f2e: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.574  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{ef90c5c: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.574  3385  4391 V AlarmManager:  remove PendingIntent] PendingIntent{cf67b65: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.584  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{3a9803a: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.584  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{b1974eb: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.594  3385  4289 V AlarmManager:  remove PendingIntent] PendingIntent{4389248: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.594  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{45868e1: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.604  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{89f6606: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.614  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{b9874c7: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.614  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{c688af4: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.624  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{f91b21d: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:57.744  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:57.924  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:58.044  9347  9347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 16:24:58.044  9347  9347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 16:24:58.044  9347  9347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 16:24:58.104  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:58.284  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:58.424  3385  3574 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-23 16:24:58.444  3385  3574 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 16:24:58.464  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:58.574  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:24:58.574  4971  4971 D BtGatt.ScanManager: awakened up at time 260168
,09-23 16:24:58.584  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 16:24:58.584  3385  4275 V AlarmManager:  remove PendingIntent] PendingIntent{c1d9663: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:58.584  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
,09-23 16:24:58.584  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:24:58.584  4971  5108 D BtGatt.GattService: current time is 260177518697
,09-23 16:24:58.584  4971  5108 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 16:24:58.584  3385  4391 V AlarmManager:  remove PendingIntent] PendingIntent{ffd6260: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:24:58.594  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 16:24:58.594  4971  5108 D ScanRecord: parseFromBytes
09-23 16:24:58.594  4971  5108 D ScanRecord: first manudata for manu ID
,09-23 16:24:58.594  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 16:24:58.594  4971  5108 D ScanRecord: parseFromBytes
09-23 16:24:58.594  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:24:58.594  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-23 16:24:58.594  4971  5108 D ScanRecord: parseFromBytes
09-23 16:24:58.594  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:24:58.594  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 16:24:58.594  4971  5108 D ScanRecord: parseFromBytes
09-23 16:24:58.594  4971  5108 D ScanRecord: first manudata for manu ID
,09-23 16:24:58.604  9347  9358 D ScanRecord: parseFromBytes
,09-23 16:24:58.604  9347  9358 D ScanRecord: first manudata for manu ID
09-23 16:24:58.604  9347  9358 D ScanRecord: parseFromBytes
09-23 16:24:58.604  9347  9358 D ScanRecord: first manudata for manu ID
,09-23 16:24:58.604  9347  9358 D ScanRecord: parseFromBytes
,09-23 16:24:58.604  9347  9358 D ScanRecord: first manudata for manu ID
09-23 16:24:58.604  9347  9358 D ScanRecord: parseFromBytes
09-23 16:24:58.604  9347  9358 D ScanRecord: first manudata for manu ID
,09-23 16:24:58.614  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{91c5319: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:58.614  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{b72fde: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:58.624  3385  4289 V AlarmManager:  remove PendingIntent] PendingIntent{24935bf: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:58.624  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{846448c: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:58.634  3385  4166 V AlarmManager:  remove PendingIntent] PendingIntent{f1607d5: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:58.634  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:58.824  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:59.004  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:59.184  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:59.364  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:59.544  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:59.594  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:24:59.594  4971  4971 D BtGatt.ScanManager: awakened up at time 261186
,09-23 16:24:59.594  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 16:24:59.604  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{3656edb: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:59.604  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-23 16:24:59.604  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:24:59.614  3385  4276 V AlarmManager:  remove PendingIntent] PendingIntent{2591d78: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
,09-23 16:24:59.624  3385  4937 V AlarmManager:  remove PendingIntent] PendingIntent{9bc4c51: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:59.634  3385  4275 V AlarmManager:  remove PendingIntent] PendingIntent{c135cb6: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:24:59.724  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:59.904  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:24:59.984  3385  3812 V AlarmManager: Expired Alarm result :8
,09-23 16:25:00.084  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:00.264  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:00.444  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:00.624  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:25:00.624  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:00.624  4971  4971 D BtGatt.ScanManager: awakened up at time 262212
,09-23 16:25:00.624  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 16:25:00.624  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-23 16:25:00.624  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{da85c8d: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:00.624  3942  3942 D KeyguardUpdateMonitor: handleTimeUpdate
,09-23 16:25:00.634  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-23 16:25:00.634  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:25:00.634  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{ef08e42: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
,09-23 16:25:00.654  3942  3942 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-23 16:25:00.664  3385  4275 V AlarmManager:  remove PendingIntent] PendingIntent{d0de53: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:00.674  3385  4276 V AlarmManager:  remove PendingIntent] PendingIntent{3de2390: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:00.724  3942  3942 D DateView: received broadcast android.intent.action.TIME_TICK
,09-23 16:25:00.744  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:25:00.744  3385  3812 V AlarmManager: Send whitelist package alarm :PendingIntent{b13fbb1: PendingIntentRecord{503f60d com.samsung.android.app.aodservice broadcastIntent}}
,09-23 16:25:00.754  4663  4663 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-23 16:25:00.754  4663  4663 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-23 16:25:00.764  4704  4704 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-23 16:25:00.764  4704  4704 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-23 16:25:00.774  3385  3448 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-23 16:25:00.774  3385  3448 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-23 16:25:00.774  3385  3448 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-23 16:25:00.774  3385  3448 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-23 16:25:00.774  3164  3164 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-23 16:25:00.774  3385  3448 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-23 16:25:00.774  3385  3448 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-23 16:25:00.774  3385  3448 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-23 16:25:00.774  4704  4704 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@835c4c1, service=Device Physical Context Monitor
09-23 16:25:00.774  4704  4704 I AlpmModeManager: startAlpmMode : state  = BLANK
09-23 16:25:00.774  4704  4704 D DefaultClockView: Window showed. Time views updating
,09-23 16:25:00.774  3385  4421 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3385
09-23 16:25:00.774  3385  4421 I libsuspend: !@autosuspend_wakeup_count_disable
,09-23 16:25:00.774  3385  4421 D PowerManagerService: mDisplayReady: false
,09-23 16:25:00.774  3385  4421 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 16:25:00.774  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:25:00.774  4704  4704 D AODUpdatePositionController: updatePosition: direction[5] updatePosition: X[-16] Y[751] NewPositionTimer[56]
09-23 16:25:00.774  3385  4421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 16:25:00.774  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-23 16:25:00.784  4704  4704 D DefaultClockView: LocalTime Pattern : HH:mm
09-23 16:25:00.774  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:25:00.784  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb3083c00
09-23 16:25:00.774  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:25:00.784  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 16:25:00.784  4704  4704 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 16:25 time02: null ampm: null
09-23 16:25:00.784  3385  3566 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 16:25:00.784  3385  3549 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 16:25:00.784  3385  3549 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-23 16:25:00.784  3385  5945 D SSRM:n  : SIOP:: AP = 320, PST = 276 (W:6), CP = 242, LCD = 1
,09-23 16:25:00.794  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:00.794  3164  3207 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
09-23 16:25:00.794  3385  3815 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
09-23 16:25:00.794  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:25:00.794  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:25:00.794  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 16:25:00.794  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-23 16:25:00.794  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 16:25:00.794  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:25:00.794  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 16:25:00.794  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 16:25:00.794  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:25:00.804  3385  3814 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 25, 0,
09-23 16:25:00.794  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:25:00.804  3385  3814 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 25, 0
09-23 16:25:00.794  3385  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-23 16:25:00.794  3385  3553 D PowerManagerService: mDisplayReady: true
09-23 16:25:00.794  3385  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 16:25:00.804  3164  3208 D Sensorhubs: sendContextData: -63, 14, 14, 25, 0
,09-23 16:25:00.804  3385  3814 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-23 16:25:00.804  3385  3814 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-23 16:25:00.804  3385  3814 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-23 16:25:00.804  3385  3814 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,09-23 16:25:00.804  3385  3814 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
09-23 16:25:00.804  3385  3817 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-23 16:25:00.814  4704  4704 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-23 16:25:00.814  4704  4704 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-23 16:25:00.814  4704  4704 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pt., 23 wrz 16:25
09-23 16:25:00.814  4704  4704 I AODService.ClockTimer: startAlarm : TICK
09-23 16:25:00.814  3385  4275 V AlarmManager: Add whitelist package alarm :PendingIntent{c7d4c8e: PendingIntentRecord{503f60d com.samsung.android.app.aodservice broadcastIntent}}
,09-23 16:25:00.814  4704  4704 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
09-23 16:25:00.814  4704  4704 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
09-23 16:25:00.814  3385  3448 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
,09-23 16:25:00.814  3385  3448 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
09-23 16:25:00.814  3385  3447 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3385
,09-23 16:25:00.824  4704  4704 I AODService: onSContextChanged: AODScreenShown state is already true
,09-23 16:25:00.824  4704  4704 D DefaultClockView: RootView invalidate()
,09-23 16:25:00.824  3385  3971 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3385
,09-23 16:25:00.974  3385  3385 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3385 (0x0)
,09-23 16:25:00.974  3385  3385 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 16:25:00.974  3385  3385 D PowerManagerService: mDisplayReady: false
09-23 16:25:00.974  3385  3385 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 16:25:00.974  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:25:00.974  3385  3385 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 16:25:00.974  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,09-23 16:25:00.974  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:00.974  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:25:00.974  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb3083c00
09-23 16:25:00.974  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:25:00.974  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 16:25:00.974  3385  3566 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 16:25:00.974  3385  3549 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 16:25:00.984  3385  3549 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-23 16:25:00.994  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:25:00.994  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:25:00.994  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 16:25:00.994  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:25:00.994  3385  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 16:25:00.994  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:25:00.994  3385  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 16:25:00.994  3385  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 16:25:00.994  3385  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 16:25:00.994  3385  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 16:25:00.994  3385  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 16:25:00.994  3385  3553 D PowerManagerService: mDisplayReady: true
09-23 16:25:00.994  3385  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 16:25:01.164  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:01.334  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:01.524  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:01.634  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:25:01.644  4971  4971 D BtGatt.ScanManager: awakened up at time 263234
,09-23 16:25:01.644  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 16:25:01.644  3385  3447 V AlarmManager:  remove PendingIntent] PendingIntent{129e8bc: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:01.654  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-23 16:25:01.654  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:01.654  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{1299045: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
,09-23 16:25:01.674  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{305a39a: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:01.684  3385  4276 V AlarmManager:  remove PendingIntent] PendingIntent{45bc4cb: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:01.694  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:01.884  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:02.064  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:02.244  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:02.414  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:02.564  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.564  9347  9412 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 16:25:02.564  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 16:25:02.564  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 16:25:02.564  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:25:02.564  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 16:25:02.564  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 16:25:02.564  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 16:25:02.574  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 16:25:02.574  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 16:25:02.574  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 16:25:02.574  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-23 16:25:02.574  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.584  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.584  9347  9412 D BluetoothLeScanner: Stop Scan
,09-23 16:25:02.594  4971  4984 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 16:25:02.594  4971  4984 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 16:25:02.594  4971  4984 D BtGatt.GattService: stopScan() - queue size =1
09-23 16:25:02.594  4971  5165 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-23 16:25:02.594  4971  5165 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,09-23 16:25:02.594  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 1
,09-23 16:25:02.594  4971  5470 D BtGatt.GattService: unregisterClient() - clientIf=7
09-23 16:25:02.594  4971  5156 D BtGatt.ScanManager: filter size is 1
09-23 16:25:02.594  4971  5156 D BtGatt.ScanManager: delete FilterIndex - 3
09-23 16:25:02.594  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 16:25:02.594  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 16:25:02.594  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-23 16:25:02.594  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-23 16:25:02.604  3385  4276 V AlarmManager:  remove PendingIntent] PendingIntent{10ad4a8: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.594  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 16:25:02.604  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:02.604  4971  5108 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
,09-23 16:25:02.604  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:25:02.604  4971  5156 D BtGatt.ScanManager: stopping BLe Batch
09-23 16:25:02.604  4971  5108 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-23 16:25:02.604  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:02.604  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-23 16:25:02.604  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 16:25:02.614  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 3
09-23 16:25:02.614  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.614  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
09-23 16:25:02.614  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{57ebc1: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.614  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:02.614  3385  3973 V AlarmManager:  remove PendingIntent] PendingIntent{78a5f66: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
,09-23 16:25:02.614  4971  5108 D BtGatt.GattService: current time is 264205564810
09-23 16:25:02.614  4971  5108 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 16:25:02.614  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:02.624  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{ddfe2a7: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:25:02.614  9347  9412 D BluetoothLeAdvertiser: stop advertising
09-23 16:25:02.614  9347  9412 D BluetoothLeAdvertiser: wrapper is null
09-23 16:25:02.614  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 16:25:02.614  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 16:25:02.614  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 16:25:02.614  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-23 16:25:02.614  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:02.614  4971  5108 D ScanRecord: first manudata for manu ID
,09-23 16:25:02.614  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 16:25:02.614  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 16:25:02.614  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:02.624  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:02.624  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 16:25:02.624  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:02.624  4971  5108 D ScanRecord: first manudata for manu ID
,09-23 16:25:02.624  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 16:25:02.624  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:25:02.624  9347  9347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 16:25:02.624  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 16:25:02.624  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 16:25:02.624  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 16:25:02.624  9347  9412 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe23a41 not in the list
,09-23 16:25:02.624  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:25:02.624  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
09-23 16:25:02.624  9347  9412 D io.jxcore.node.ConnectivityMonitor: stop
09-23 16:25:02.624  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 16:25:02.624  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 3
,09-23 16:25:02.624  4971  5165 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-23 16:25:02.624  4971  5165 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-23 16:25:02.634  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{59e0243: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.634  9347  9347 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 16:25:02.634  9347  9347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 16:25:02.634  9347  9347 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.634  9347  9347 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.634  9347  9347 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.634  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{bc990c0: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:02.634  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 16:25:02.644  9347  9347 D BluetoothAdapter: STATE_ON
,09-23 16:25:02.644  9347  9347 D BluetoothAdapter: STATE_ON
09-23 16:25:02.644  9347  9347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 16:25:02.644  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{36d51f9: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:02.644  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 16:25:02.644  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 16:25:02.644  9347  9347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 16:25:02.644  9347  9347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 16:25:02.644  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{41bf53e: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.644  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 16:25:02.644  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 16:25:02.654  9347  9347 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 16:25:02.654  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 16:25:02.654  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{e5e274a: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.654  9347  9347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:25:02.654  9347  9347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 16:25:02.654  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{b4b76bb: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.664  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{cf0b7d8: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.664  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{3924731: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.664  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{7df6e16: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.674  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{8b0c397: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:02.784  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:02.954  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:03.134  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:03.164  9347  9347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-23 16:25:03.314  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:03.494  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:03.684  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:03.864  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:04.044  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:04.224  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:04.394  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:04.584  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:04.754  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:04.934  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:05.124  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:05.304  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:05.474  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:05.664  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:05.844  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:06.024  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:06.194  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:06.374  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:06.554  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:06.734  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:06.924  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:07.104  3385  5981 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-23 16:25:07.104  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:07.284  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:07.454  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:07.634  9347  9412 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 16:25:07.634  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:25:07.644  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:07.654  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 16:25:07.654  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 16:25:07.664  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.674  9347  9412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 16:25:07.674  9347  9412 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 16:25:07.674  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 16:25:07.674  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 16:25:07.674  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 16:25:07.674  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:25:07.674  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 16:25:07.684  9347  9412 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 16:25:07.684  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:25:07.694  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.694  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.694  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:25:07.704  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.704  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.704  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 16:25:07.704  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 16:25:07.704  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 16:25:07.704  9347  9412 D BluetoothLeScanner: Start Scan
,09-23 16:25:07.714  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.714  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.714  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.724  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.724  4971  4985 D BtGatt.GattService: registerClient() - UUID=96cb21cd-fa54-4cf9-901a-ae7032ddf3de
,09-23 16:25:07.774  4971  5108 D BtGatt.GattService: onClientRegistered() - UUID=96cb21cd-fa54-4cf9-901a-ae7032ddf3de, clientIf=7
,09-23 16:25:07.774  9347  9358 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-23 16:25:07.774  4971  4984 D BtGatt.GattService: start scan with filters
,09-23 16:25:07.774  4971  4984 D BtGatt.GattService: getScanSettings
,09-23 16:25:07.774  4971  4984 D BtGatt.GattService: Is it foreground application = true
,09-23 16:25:07.774  4971  4984 D BtGatt.GattService: not a background application
,09-23 16:25:07.784  4971  4984 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 16:25:07.794  4971  4984 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 16:25:07.794  4971  4984 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 16:25:07.794  4971  5165 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 16:25:07.794  4971  5165 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 16:25:07.794  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 16:25:07.794  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 16:25:07.794  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-23 16:25:07.794  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 16:25:07.794  4971  5156 D BtGatt.ScanManager: handling starting scan
,09-23 16:25:07.804  4971  5156 D BluetoothAdapter: STATE_ON
09-23 16:25:07.804  4971  5156 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.804  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 16:25:07.804  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 16:25:07.804  9347  9347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 16:25:07.814  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{4ce29ee: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:07.814  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 63
,09-23 16:25:07.814  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-23 16:25:07.814  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 16:25:07.814  4971  5108 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-23 16:25:07.814  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:07.814  4971  5156 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
09-23 16:25:07.814  4971  5156 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 16:25:07.814  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:07.814  4971  5156 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 16:25:07.824  4971  5156 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-23 16:25:07.824  4971  5108 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 16:25:07.824  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8a28e8f: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:07.824  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:07.824  4971  5156 D BtGatt.ScanManager: Starting BLE batch scan
09-23 16:25:07.824  4971  5156 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 2
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577345
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 16:25:07.824  9347  9412 I io.jxcore.node.ConnectionHelper: start: OK
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:25:07.824  4971  5108 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-23 16:25:07.824  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
,09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:25:07.834  3385  4391 V AlarmManager:  remove PendingIntent] PendingIntent{640751c: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-23 16:25:07.834  3385  3447 V AlarmManager:  remove PendingIntent] PendingIntent{cc89525: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:25:07.824  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-23 16:25:07.834  4971  5165 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577345
,09-23 16:25:07.834  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.834  4971  5108 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-23 16:25:07.834  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:25:07.834  9347  9412 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 16:25:07.834  9347  9412 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 16:25:07.834  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 16:25:07.834  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 16:25:07.834  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:25:07.834  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 16:25:07.834  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 16:25:07.834  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 16:25:07.834  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 16:25:07.834  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 16:25:07.834  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 16:25:07.834  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 16:25:07.844  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.844  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{e76f6fa: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:07.844  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.844  9347  9412 D BluetoothLeScanner: Stop Scan
,09-23 16:25:07.844  4971  5470 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 16:25:07.844  4971  5470 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 16:25:07.844  4971  5470 D BtGatt.GattService: stopScan() - queue size =1
09-23 16:25:07.844  4971  5165 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-23 16:25:07.844  4971  5165 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 16:25:07.844  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:25:07.844  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-23 16:25:07.844  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-23 16:25:07.844  4971  5165 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,09-23 16:25:07.844  4971  5165 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-23 16:25:07.844  4971  5156 D BtGatt.ScanManager: filter size is 1
09-23 16:25:07.844  4971  5156 D BtGatt.ScanManager: delete FilterIndex - 4
09-23 16:25:07.854  3385  4391 V AlarmManager:  remove PendingIntent] PendingIntent{74384ab: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.854  4971  5463 D BtGatt.GattService: unregisterClient() - clientIf=7
09-23 16:25:07.854  4971  5108 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-23 16:25:07.854  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:07.854  4971  5156 D BtGatt.ScanManager: stopping BLe Batch
,09-23 16:25:07.854  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 16:25:07.854  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 16:25:07.854  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 16:25:07.854  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 16:25:07.854  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-23 16:25:07.854  4971  5108 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-23 16:25:07.854  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:25:07.854  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-23 16:25:07.854  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 16:25:07.854  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{16dc708: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:07.854  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.854  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,09-23 16:25:07.864  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{6925ea1: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:25:07.854  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:07.854  4971  5108 D BtGatt.GattService: current time is 269449448652
09-23 16:25:07.854  4971  5108 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 16:25:07.854  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.864  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 16:25:07.864  3385  4166 V AlarmManager:  remove PendingIntent] PendingIntent{6ad88c6: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:25:07.864  9347  9412 D BluetoothLeAdvertiser: stop advertising
,09-23 16:25:07.864  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:07.864  9347  9412 D BluetoothLeAdvertiser: wrapper is null
09-23 16:25:07.864  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:07.864  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 16:25:07.864  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 16:25:07.864  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 16:25:07.864  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 16:25:07.864  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{6b3c087: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.864  9347  9347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 16:25:07.864  9347  9412 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 16:25:07.864  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:25:07.864  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 16:25:07.864  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 16:25:07.864  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 16:25:07.864  9347  9412 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe23a41 not in the list
09-23 16:25:07.864  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:25:07.864  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
,09-23 16:25:07.864  9347  9412 D io.jxcore.node.ConnectivityMonitor: stop
09-23 16:25:07.864  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 16:25:07.874  3385  4275 V AlarmManager:  remove PendingIntent] PendingIntent{a01de23: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.874  9347  9347 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 16:25:07.874  9347  9347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 16:25:07.874  9347  9347 D BluetoothAdapter: STATE_ON
09-23 16:25:07.874  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{68c6f20: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.874  9347  9347 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.874  9347  9347 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.884  3385  3447 V AlarmManager:  remove PendingIntent] PendingIntent{66740d9: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.884  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 16:25:07.884  9347  9347 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.884  9347  9347 D BluetoothAdapter: STATE_ON
09-23 16:25:07.884  9347  9347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 16:25:07.884  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 16:25:07.884  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 16:25:07.884  9347  9347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:25:07.884  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{8eea9e: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.894  9347  9412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 16:25:07.894  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 16:25:07.894  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{c8a397f: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.894  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 16:25:07.894  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.894  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.894  9347  9412 D BluetoothLeAdvertiser: stop advertising
09-23 16:25:07.894  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{b995d4c: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:07.894  9347  9412 D BluetoothLeAdvertiser: wrapper is null
09-23 16:25:07.894  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 16:25:07.894  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 16:25:07.894  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.894  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.894  9347  9412 D BluetoothLeScanner: could not find callback wrapper
09-23 16:25:07.894  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 16:25:07.894  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 16:25:07.894  9347  9347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 16:25:07.894  9347  9412 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbe6 not in the list
09-23 16:25:07.904  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8a50238: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:07.894  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 16:25:07.894  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 16:25:07.894  9347  9412 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 16:25:07.904  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:25:07.904  9347  9347 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 16:25:07.904  9347  9347 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 16:25:07.904  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{2c409e4: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.914  9347  9347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 16:25:07.914  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.914  3385  4216 V AlarmManager:  remove PendingIntent] PendingIntent{2d3de4d: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 16:25:07.914  9347  9412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 16:25:07.914  9347  9347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 16:25:07.914  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.924  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{e7f4d02: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.924  9347  9412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 16:25:07.924  9347  9412 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 16:25:07.924  9347  9412 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 16:25:07.924  9347  9412 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 16:25:07.924  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 16:25:07.924  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 16:25:07.924  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 16:25:07.924  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{e19374e: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.924  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:25:07.934  9347  9412 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 16:25:07.934  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{3ea806f: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.934  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.934  3385  4166 V AlarmManager:  remove PendingIntent] PendingIntent{2d4b17c: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.934  9347  9347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 16:25:07.934  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.944  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{48b8a05: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.944  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.944  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.944  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 16:25:07.944  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-23 16:25:07.944  9347  9412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 16:25:07.944  9347  9412 D BluetoothLeScanner: Start Scan
,09-23 16:25:07.944  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.944  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{8557a5a: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.944  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.944  9347  9412 D BluetoothAdapter: STATE_ON
,09-23 16:25:07.954  9347  9412 D BluetoothAdapter: STATE_ON
09-23 16:25:07.954  3385  4275 V AlarmManager:  remove PendingIntent] PendingIntent{348b48b: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.954  4971  4984 D BtGatt.GattService: registerClient() - UUID=f848152d-e93b-4cb5-988c-6f18487db466
,09-23 16:25:07.954  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{b796968: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.964  3385  4216 V AlarmManager:  remove PendingIntent] PendingIntent{f3fc181: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.964  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{5e0e226: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:07.994  4971  5108 D BtGatt.GattService: onClientRegistered() - UUID=f848152d-e93b-4cb5-988c-6f18487db466, clientIf=7
,09-23 16:25:07.994  9347  9358 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-23 16:25:07.994  4971  5470 D BtGatt.GattService: start scan with filters
,09-23 16:25:07.994  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:07.994  4971  5470 D BtGatt.GattService: getScanSettings
,09-23 16:25:07.994  4971  5470 D BtGatt.GattService: Is it foreground application = true
,09-23 16:25:07.994  4971  5470 D BtGatt.GattService: not a background application
,09-23 16:25:08.004  4971  5470 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 16:25:08.004  4971  5470 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 16:25:08.004  4971  5470 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 16:25:08.004  4971  5165 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 16:25:08.004  4971  5165 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,09-23 16:25:08.004  4971  5156 D BtGatt.ScanManager: handling starting scan
09-23 16:25:08.004  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 16:25:08.004  9347  9412 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 16:25:08.004  4971  5156 D BluetoothAdapter: STATE_ON
09-23 16:25:08.004  9347  9412 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 16:25:08.004  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 16:25:08.004  4971  5156 D BluetoothAdapter: STATE_ON
,09-23 16:25:08.014  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 16:25:08.014  9347  9412 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 16:25:08.014  9347  9347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 16:25:08.014  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 64
,09-23 16:25:08.014  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-23 16:25:08.014  3385  3973 V AlarmManager:  remove PendingIntent] PendingIntent{50c0e67: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:08.014  4971  5108 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-23 16:25:08.014  9347  9412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 16:25:08.014  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:08.014  4971  5156 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
09-23 16:25:08.014  4971  5156 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 16:25:08.014  4971  5156 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 16:25:08.014  4971  5156 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-23 16:25:08.014  4971  5108 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 16:25:08.014  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:25:08.014  4971  5156 D BtGatt.ScanManager: Starting BLE batch scan
09-23 16:25:08.014  4971  5156 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-23 16:25:08.024  4971  5108 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 16:25:08.024  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:25:08.024  9347  9412 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 16:25:08.024  4971  5108 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-23 16:25:08.024  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{d2fb414: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:25:08.024  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:08.024  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{1a5f4bd: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 3
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577345
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
,09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
,09-23 16:25:08.034  3385  4216 V AlarmManager:  remove PendingIntent] PendingIntent{b68fab2: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-23 16:25:08.024  4971  5165 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577345
,09-23 16:25:08.034  3385  4391 V AlarmManager:  remove PendingIntent] PendingIntent{fc12a03: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.034  3385  3973 V AlarmManager:  remove PendingIntent] PendingIntent{15dfd80: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.044  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{9421fb9: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.044  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{8e80ffe: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.054  3385  4276 V AlarmManager:  remove PendingIntent] PendingIntent{c22635f: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.054  3385  3447 V AlarmManager:  remove PendingIntent] PendingIntent{f6571ac: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.054  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{ddbfe75: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.064  3385  4166 V AlarmManager:  remove PendingIntent] PendingIntent{1b12e0a: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.064  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{a33d67b: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.074  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{18dfc98: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.074  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{1fb0cf1: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:08.184  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:08.364  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:08.524  9347  9347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 16:25:08.524  9347  9347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 16:25:08.524  9347  9347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 16:25:08.544  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:08.724  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:08.904  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:09.024  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:25:09.034  4971  4971 D BtGatt.ScanManager: awakened up at time 270622
,09-23 16:25:09.034  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 16:25:09.034  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{c1f5f57: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:09.044  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
09-23 16:25:09.044  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:09.044  4971  5108 D BtGatt.GattService: current time is 270635468497
09-23 16:25:09.044  4971  5108 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -77, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -87, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 16:25:09.044  3385  4397 V AlarmManager:  remove PendingIntent] PendingIntent{cb24a44: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:25:09.044  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 16:25:09.044  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:09.044  4971  5108 D ScanRecord: first manudata for manu ID
,09-23 16:25:09.044  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 16:25:09.044  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:09.044  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:09.044  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 16:25:09.044  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:09.044  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:09.044  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 16:25:09.044  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:09.044  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-23 16:25:09.054  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:09.054  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 16:25:09.054  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:09.054  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  9347  9357 D ScanRecord: parseFromBytes
09-23 16:25:09.054  9347  9357 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  9347  9357 D ScanRecord: parseFromBytes
09-23 16:25:09.054  9347  9357 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  9347  9357 D ScanRecord: parseFromBytes
09-23 16:25:09.054  9347  9357 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  9347  9357 D ScanRecord: parseFromBytes
09-23 16:25:09.054  9347  9357 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  9347  9357 D ScanRecord: parseFromBytes
09-23 16:25:09.054  9347  9357 D ScanRecord: first manudata for manu ID
09-23 16:25:09.054  9347  9357 D ScanRecord: parseFromBytes
09-23 16:25:09.054  9347  9357 D ScanRecord: first manudata for manu ID
09-23 16:25:09.064  3385  3849 V AlarmManager:  remove PendingIntent] PendingIntent{f22872d: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:09.074  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 16:25:09.084  3385  4276 V AlarmManager:  remove PendingIntent] PendingIntent{b17462: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:09.094  3385  3447 V AlarmManager:  remove PendingIntent] PendingIntent{2d099f3: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:09.094  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{6abc6b0: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:09.104  3385  4937 V AlarmManager:  remove PendingIntent] PendingIntent{9cd6929: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:09.104  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{13674ae: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:09.104  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{850e24f: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
09-23 16:25:09.114  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{77e9ddc: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:09.184  3385  3396 I art     : Background sticky concurrent mark sweep GC freed 146818(10MB) AllocSpace objects, 108(2MB) LOS objects, 23% free, 43MB/56MB, paused 2.850ms total 116.280ms
,09-23 16:25:09.254  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:09.434  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:09.624  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:09.804  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:09.974  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:10.044  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:25:10.054  4971  4971 D BtGatt.ScanManager: awakened up at time 271644
,09-23 16:25:10.054  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 16:25:10.054  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{ef92dba: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:10.064  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
,09-23 16:25:10.064  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 16:25:10.064  4971  5108 D BtGatt.GattService: current time is 271659136381
09-23 16:25:10.074  3385  4937 V AlarmManager:  remove PendingIntent] PendingIntent{3e3546b: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
09-23 16:25:10.064  4971  5108 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,09-23 16:25:10.074  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 16:25:10.074  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:10.074  4971  5108 D ScanRecord: first manudata for manu ID
,09-23 16:25:10.074  4971  5108 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-23 16:25:10.074  4971  5108 D ScanRecord: parseFromBytes
09-23 16:25:10.074  4971  5108 D ScanRecord: first manudata for manu ID
09-23 16:25:10.074  9347  9357 D ScanRecord: parseFromBytes
,09-23 16:25:10.074  9347  9357 D ScanRecord: first manudata for manu ID
09-23 16:25:10.074  9347  9357 D ScanRecord: parseFromBytes
09-23 16:25:10.074  9347  9357 D ScanRecord: first manudata for manu ID
,09-23 16:25:10.084  3385  3448 V AlarmManager:  remove PendingIntent] PendingIntent{145bbc8: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:10.094  3385  4938 V AlarmManager:  remove PendingIntent] PendingIntent{e981461: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:10.104  3385  4780 V AlarmManager:  remove PendingIntent] PendingIntent{fc6b86: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:10.114  3385  4421 V AlarmManager:  remove PendingIntent] PendingIntent{3e0cc47: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:10.124  3385  3973 V AlarmManager:  remove PendingIntent] PendingIntent{adecc74: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:10.164  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:10.334  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:10.514  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:10.694  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:10.804  3385  5945 D SSRM:n  : SIOP:: AP = 290, PST = 283 (W:14), CP = 242, LCD = 1
,09-23 16:25:10.874  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:11.054  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:11.074  3385  3812 V AlarmManager: Expired Alarm result :4
,09-23 16:25:11.074  4971  4971 D BtGatt.ScanManager: awakened up at time 272667
,09-23 16:25:11.074  4971  5156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 16:25:11.084  3385  4289 V AlarmManager:  remove PendingIntent] PendingIntent{9a3ba12: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:11.084  4971  5108 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-23 16:25:11.084  4971  5108 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 16:25:11.094  3385  4276 V AlarmManager:  remove PendingIntent] PendingIntent{953e5e3: PendingIntentRecord{98dfacf com.android.bluetooth broadcastIntent}}
,09-23 16:25:11.104  3385  3447 V AlarmManager:  remove PendingIntent] PendingIntent{9563be0: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:11.114  3385  3971 V AlarmManager:  remove PendingIntent] PendingIntent{f35ee99: PendingIntentRecord{cca6287 com.android.bluetooth broadcastIntent}}
,09-23 16:25:11.244  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:11.414  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 16:25:11.604  3385  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
