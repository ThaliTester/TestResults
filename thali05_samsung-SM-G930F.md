#### Test 85046911f11c404_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-22 12:25:52.815  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:52.995  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:53.175  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:53.355  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:53.395  9481  9481 I FIPS_bssl: FIPS approved mode (1) | 9481 | app_process
09-22 12:25:53.405  9481  9481 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 12:25:53.405  9481  9481 D AndroidRuntime: CheckJNI is OFF
09-22 12:25:53.405  9481  9481 D AndroidRuntime: readGMSProperty: start
09-22 12:25:53.405  9481  9481 D AndroidRuntime: readGMSProperty: already setted!!
09-22 12:25:53.405  9481  9481 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-22 12:25:53.405  9481  9481 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-22 12:25:53.405  9481  9481 D AndroidRuntime: readGMSProperty: end
09-22 12:25:53.405  9481  9481 D AndroidRuntime: addProductProperty: start
09-22 12:25:53.425  9481  9481 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 12:25:53.445  9481  9481 I Radio-JNI: register_android_hardware_Radio DONE
09-22 12:25:53.455  9481  9481 E AffinityControl: AffinityControl: registerfunction enter
09-22 12:25:53.465  9481  9481 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-22 12:25:53.485  3405  4316 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-22 12:25:53.485  3405  4316 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-22 12:25:53.515  3405  4316 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:25:53.515  3405  4316 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:25:53.515  3405  4316 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-22 12:25:53.515  3405  4316 D ActivityManager: mDVFSHelper.acquire()
09-22 12:25:53.515  3405  4316 V WindowManager: addAppToken: AppWindowToken{d0a5b4376 token=Token{dac9611 ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-22 12:25:53.525  3405  3544 I InjectionManager: Inside getClassLibPath caller 
09-22 12:25:53.535  3405  3544 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 12:25:53.535  3405  3544 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9834b4e V.E...... R.....ID 0,0-0,0}
09-22 12:25:53.535  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:53.535  9490  9490 E Zygote  : v2
09-22 12:25:53.535  9490  9490 I libpersona: KNOX_SDCARD checking this for 10171
09-22 12:25:53.535  9490  9490 I libpersona: KNOX_SDCARD not a persona
09-22 12:25:53.535  3405  3544 W WindowManager: Failed looking up window
09-22 12:25:53.535  3405  3544 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@a2d046f does not exist
09-22 12:25:53.535  3405  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:25:53.535  3405  3544 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 12:25:53.535  3405  3544 D ISSUE_DEBUG: InputChannelName : 95ee57c Starting com.test.thalitest
09-22 12:25:53.535  9490  9490 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-22 12:25:53.535  9490  9490 E Zygote  : accessInfo : 0
09-22 12:25:53.535  9490  9490 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-22 12:25:53.545  3405  4316 I ActivityManager: Start proc 9490:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-22 12:25:53.545  3405  4316 D InputDispatcher: Focused application set to: xxxx
09-22 12:25:53.545  9481  9481 D AndroidRuntime: Shutting down VM
09-22 12:25:53.545  3405  3852 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-22 12:25:53.555  3003  3003 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-22 12:25:53.565  9490  9490 D TimaKeyStoreProvider: TimaSignature is unavailable
09-22 12:25:53.565  9490  9490 D ActivityThread: Added TimaKeyStore provider
09-22 12:25:53.585  6316  6316 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:25:53.595  3405  3849 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3405
09-22 12:25:53.595  3405  3849 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:25:53.595  3405  3849 D PowerManagerService: mDisplayReady: false
09-22 12:25:53.595  3405  3849 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:25:53.595  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:25:53.595  6316  6316 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:25:53.595  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:25:53.595  3003  3003 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f85743c00
09-22 12:25:53.595  3405  3849 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:25:53.595  3003  3003 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-22 12:25:53.595  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:53.595  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:53.595  3405  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-22 12:25:53.595  3405  4437 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3405
09-22 12:25:53.595  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:25:53.595  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:25:53.595  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:25:53.595  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:53.595  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:25:53.595  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:53.595  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:25:53.595  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:25:53.595  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:53.595  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:53.595  3405  3549 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:25:53.595  3405  3549 D PowerManagerService: mDisplayReady: true
09-22 12:25:53.595  3405  3549 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:25:53.605  3405  4230 D ActivityManager:  Launching com.test.thalitest, updated priority
09-22 12:25:53.605  3405  3446 V WindowStateAnimator: Finishing drawing window Window{bb61e3e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-22 12:25:53.615  4277  4277 V ActivityThread: updateVisibility : ActivityRecord{b452a9c token=android.os.BinderProxy@7df0897 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-22 12:25:53.625  3405  3405 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-22 12:25:53.625  3405  3510 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-22 12:25:53.635  3003  4487 D libEGL  : eglTerminate EGLDisplay = 0x7f7e400e78
09-22 12:25:53.635  3003  4487 D libEGL  : eglTerminate EGLDisplay = 0x7f7e400e78
09-22 12:25:53.645  3003  3012 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-22 12:25:53.645  3003  3834 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-22 12:25:53.655  3405  4854 V WindowStateAnimator: Finishing drawing window Window{35351c0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-22 12:25:53.655  6316  6316 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:25:53.655  4277  4277 D Launcher: onTrimMemory. Level: 20
09-22 12:25:53.655  6316  6316 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:25:53.655  6316  6316 V ActivityThread: updateVisibility : ActivityRecord{b52194b token=android.os.BinderProxy@1e939ec {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-22 12:25:53.655  3003  3834 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-22 12:25:53.655  3003  4487 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-22 12:25:53.665  3003  4487 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-22 12:25:53.665  3003  3014 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-22 12:25:53.675  3003  3003 D libEGL  : eglTerminate EGLDisplay = 0x7ff97b0ee8
09-22 12:25:53.675  3003  3003 D libEGL  : eglTerminate EGLDisplay = 0x7ff97b0ee8
09-22 12:25:53.675  3003  3003 D libEGL  : eglTerminate EGLDisplay = 0x7ff97b0eb8
09-22 12:25:53.675  3003  3003 D libEGL  : eglTerminate EGLDisplay = 0x7ff97b0ee8
09-22 12:25:53.715  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:53.745  3405  3405 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3405 (0x0)
09-22 12:25:53.745  3405  3405 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3405 (0x0)
09-22 12:25:53.745  3405  3405 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:25:53.745  3405  3405 D PowerManagerService: mDisplayReady: false
09-22 12:25:53.745  3405  3405 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:25:53.745  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:25:53.745  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:25:53.745  3405  3405 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:25:53.745  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:53.745  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:53.745  3405  3563 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-22 12:25:53.745  3003  3003 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f85743c00
09-22 12:25:53.745  3003  3003 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-22 12:25:53.745  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:25:53.745  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:25:53.745  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:53.755  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:25:53.745  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:53.755  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:25:53.745  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:25:53.745  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:25:53.745  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:53.755  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:53.755  3405  3549 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:25:53.755  3405  3549 D PowerManagerService: mDisplayReady: true
09-22 12:25:53.755  3405  3549 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:25:53.895  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:53.955  3405  4230 I WindowManager: Screenshot max retries 4 of Token{dac9611 ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{95ee57c u0 d0 Starting com.test.thalitest} drawState=1
09-22 12:25:53.955  3405  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:25:53.955  3405  3405 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:25:53.955  3405  3544 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-22 12:25:53.965  3405  3405 I KnoxTimeoutHandler: SD activityfalse
09-22 12:25:53.965  3405  6249 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:25:53.965  3405  6249 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:25:53.975  3405  3852 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-22 12:25:54.005  9490  9490 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 12:25:54.005  3405  4396 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-22 12:25:54.005  9490  9490 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-22 12:25:54.005  3405  6249 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-22 12:25:54.005  3405  3544 V WindowStateAnimator: Finishing drawing window Window{95ee57c u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-22 12:25:54.005  3405  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:25:54.005  3405  3405 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:25:54.015  3405  3544 D ActivityManager: mDVFSHelper.release()
09-22 12:25:54.015  3405  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c491c9a u0 com.samsung.android.MtpApplication/.USBConnection t3} time:209160
09-22 12:25:54.015  3405  6249 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:25:54.015  3405  3405 I KnoxTimeoutHandler: SD activityfalse
09-22 12:25:54.025  3405  6249 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-22 12:25:54.025  3405  6249 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:25:54.025  3405  6249 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:25:54.025  9490  9490 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:25:54.035  3003  3003 D libEGL  : eglInitialize EGLDisplay = 0x7ff97b0dc8
09-22 12:25:54.035  9490  9490 I InjectionManager: Inside getClassLibPath caller 
09-22 12:25:54.055  9490  9490 D InjectionManager: InjectionManager
09-22 12:25:54.055  9490  9490 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-22 12:25:54.055  9490  9490 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-22 12:25:54.055  9490  9490 I InjectionManager: featureStore :{}
09-22 12:25:54.055  9490  9490 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 12:25:54.065  9490  9490 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-22 12:25:54.065  9490  9490 D RelationGraph: garbageCollect()
09-22 12:25:54.065  9490  9490 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 12:25:54.075  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:54.095  9490  9490 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-22 12:25:54.135  9490  9490 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-22 12:25:54.135  9490  9490 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:25:54.135  9490  9490 I InjectionManager: Inside getClassLibPath caller 
09-22 12:25:54.145  9490  9490 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-22 12:25:54.205  9490  9490 I cr_LibraryLoader: Time to load native libraries: 36 ms (timestamps 9312-9348)
09-22 12:25:54.205  9490  9490 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-22 12:25:54.225  3405  3876 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-22 12:25:54.255  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:54.275  9490  9505 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-22 12:25:54.295  9490  9490 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {db09050}
09-22 12:25:54.295  9490  9490 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-22 12:25:54.325  3405  3876 I MdnieScenarioControlService: mGameModeLauncher : false
09-22 12:25:54.325  3405  3876 I MdnieScenarioControlService: setUIMode
09-22 12:25:54.325  9490  9490 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-22 12:25:54.375  9490  9490 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-22 12:25:54.435  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:54.455  3405  3510 W ActivityManager: Activity pause timeout for ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4}
09-22 12:25:54.565  9490  9490 D libEGL  : eglInitialize EGLDisplay = 0xff8aeb2c
09-22 12:25:54.615  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:54.655  3405  4854 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-22 12:25:54.655  3405  4854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-22 12:25:54.745  9490  9490 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-22 12:25:54.765  9490  9490 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-22 12:25:54.765  9490  9490 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-22 12:25:54.795  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:54.805  9490  9490 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-22 12:25:54.845  9490  9490 D Activity: performCreate Call Injection manager
09-22 12:25:54.845  9490  9490 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-22 12:25:54.855  9490  9490 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 12:25:54.855  9490  9490 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8aca4ae I.E...... R.....ID 0,0-0,0}
09-22 12:25:54.865  9490  9542 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-22 12:25:54.865  3405  4764 W WindowManager: Failed looking up window
09-22 12:25:54.865  3405  4764 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@a25664f does not exist
09-22 12:25:54.865  3405  4764 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 12:25:54.865  3405  4764 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 12:25:54.865  3405  4764 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 12:25:54.865  3405  4764 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-22 12:25:54.865  3405  4764 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-22 12:25:54.865  3405  4764 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-22 12:25:54.865  3405  3976 D ISSUE_DEBUG: InputChannelName : 732d1dc com.test.thalitest/com.test.thalitest.MainActivity
09-22 12:25:54.875  3405  3978 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-22 12:25:54.875  3405  3978 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:25:54.875  3405  3405 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:25:54.875  3405  3405 I KnoxTimeoutHandler: Shared devices show user statefalse
09-22 12:25:54.875  9490  9490 V ActivityThread: updateVisibility : ActivityRecord{fd84ddc token=android.os.BinderProxy@c17df76 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-22 12:25:54.885  9490  9505 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-22 12:25:54.915  9490  9490 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9490
09-22 12:25:54.925  3405  4396 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9490 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-22 12:25:54.935  3405  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-22 12:25:54.935  3405  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-22 12:25:54.945  3405  3863 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-22 12:25:54.945  3405  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-22 12:25:54.955  3405  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-22 12:25:54.955  9490  9490 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 12:25:54.965  3405  6250 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-22 12:25:54.965  3405  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-22 12:25:54.975  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:54.975  3405  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-22 12:25:54.975  3405  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-22 12:25:54.975  3405  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-22 12:25:54.985  3003  3003 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
09-22 12:25:55.015  9490  9542 D libEGL  : eglInitialize EGLDisplay = 0xdc6ff7c4
09-22 12:25:55.015  9490  9542 I OpenGLRenderer: Initialized EGL, version 1.4
09-22 12:25:55.025  9490  9542 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-22 12:25:55.025  3405  4764 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3405
09-22 12:25:55.025  3405  4764 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:25:55.025  3405  4764 D PowerManagerService: mDisplayReady: false
09-22 12:25:55.025  3405  4764 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:25:55.025  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:25:55.025  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:25:55.025  3405  4764 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:25:55.035  3003  3003 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f85743c00
09-22 12:25:55.025  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:55.035  3003  3003 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-22 12:25:55.025  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:55.035  3405  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-22 12:25:55.035  3405  3544 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-22 12:25:55.035  3405  3544 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-22 12:25:55.065  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:25:55.065  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:25:55.065  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:55.065  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:25:55.065  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:55.065  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:25:55.065  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:25:55.065  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:25:55.065  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:55.065  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:55.065  3405  3549 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:25:55.065  3405  3549 D PowerManagerService: mDisplayReady: true
09-22 12:25:55.065  3405  3549 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:25:55.085  9490  9490 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-22 12:25:55.105  3405  3972 V WindowStateAnimator: Finishing drawing window Window{732d1dc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-22 12:25:55.105  9490  9490 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-22 12:25:55.115  3405  4316 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3405
09-22 12:25:55.115  3405  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:25:55.115  3405  3405 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:25:55.125  3405  3544 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s164ms (total +1s601ms)
09-22 12:25:55.125  3405  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4} time:210271
09-22 12:25:55.125  3405  3405 I KnoxTimeoutHandler: SD activityfalse
09-22 12:25:55.125  3405  4437 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3405
09-22 12:25:55.125  3405  3544 D ViewRootImpl: #3 mView = null
09-22 12:25:55.125  3003  3012 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-22 12:25:55.125  3003  3012 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
09-22 12:25:55.135  9490  9546 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 12:25:55.135  9490  9546 D libEGL  : eglInitialize EGLDisplay = 0xdaf8c3f4
09-22 12:25:55.135  3405  3978 V WindowStateAnimator: Finishing drawing window Window{732d1dc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-22 12:25:55.135  9490  9490 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c17df76 time:210286
09-22 12:25:55.155  3003  3003 D libEGL  : eglTerminate EGLDisplay = 0x7ff97b0ee8
09-22 12:25:55.155  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:55.165  9490  9546 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-22 12:25:55.205  9490  9490 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9490
09-22 12:25:55.275  3405  3405 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3405 (0x0)
09-22 12:25:55.275  3405  3405 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:25:55.275  3405  3405 D PowerManagerService: mDisplayReady: false
09-22 12:25:55.275  3405  3405 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:25:55.275  3405  3405 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:25:55.275  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:25:55.275  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:25:55.275  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:55.275  3003  3003 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f85743c00
09-22 12:25:55.275  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:55.275  3003  3003 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-22 12:25:55.275  3405  3563 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-22 12:25:55.275  3405  3544 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-22 12:25:55.275  3405  3544 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-22 12:25:55.295  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:25:55.295  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:25:55.295  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:25:55.295  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:25:55.295  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:55.295  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:55.295  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:25:55.295  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:25:55.295  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:25:55.295  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:25:55.295  3405  3549 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:25:55.295  3405  3549 D PowerManagerService: mDisplayReady: true
09-22 12:25:55.295  3405  3549 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:25:55.335  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:25:55.415  3405  6284 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-22 12:25:55.435  9490  9490 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-22 12:25:55.455  4023  4023 D Recents : onTaskStackChanged
09-22 12:25:55.465  4023  4023 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-22 12:25:55.475  4023  4023 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:25:55.515  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:55.535  9490  9553 D jxcore_app_log: JniHelper::setJavaVM(0xf4df4000), pthread_self() = -638846672
,09-22 12:25:55.535  9490  9553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 12:25:55.535  9490  9553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 12:25:55.535  9490  9553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 12:25:55.535  9490  9553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 12:25:55.535  9490  9553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-22 12:25:55.535  9490  9553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@561955e added. We now have 1 listener(s)
,09-22 12:25:55.545  9490  9553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-22 12:25:55.545  9490  9553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-22 12:25:55.545  9490  9553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 12:25:55.545  9490  9553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-22 12:25:55.545  9490  9553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2da96a added. We now have 1 listener(s)
09-22 12:25:55.545  9490  9553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 12:25:55.555  9490  9553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 12:25:55.555  9490  9553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 12:25:55.555  9490  9553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 12:25:55.555  9490  9553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 12:25:55.555  9490  9553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-22 12:25:55.555  9490  9553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:25:55.555  9490  9553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-22 12:25:55.565  9490  9553 D BluetoothAdapter: STATE_ON
,09-22 12:25:55.565  9490  9553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:25:55.565  9490  9553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 12:25:55.565  9490  9553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 12:25:55.565  9490  9553 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 12:25:55.565  9490  9553 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-22 12:25:55.575  9490  9490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:25:55.575  9490  9490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:25:55.595  9490  9490 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 12:25:55.695  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:55.875  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:55.885  9490  9554 W jxcore-log: Initializing JXcore engine
09-22 12:25:55.885  9490  9554 W jxcore-log: JXcore engine is ready
,09-22 12:25:55.905  5057  5057 E audit   : type=1400 msg=audit(1474539955.905:264): avc:  denied  { ioctl } for  pid=9554 comm="Thread-164" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2222 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 12:25:55.905  5057  5057 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-22 12:25:55.905  5057  5057 E audit   : type=1300 msg=audit(1474539955.905:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d92bf3c8 items=0 ppid=3173 pid=9554 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-22 12:25:55.905  5057  5057 E audit   : type=1327 msg=audit(1474539955.905:264): proctitle="com.test.thalitest"
09-22 12:25:55.905  5057  5057 E audit   : type=1320 msg=audit(1474539955.905:264): 
09-22 12:25:55.905  5057  5057 E audit   : type=1400 msg=audit(1474539955.905:265): avc:  denied  { ioctl } for  pid=9554 comm="Thread-164" path="socket:[38956]" dev="sockfs" ino=38956 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 12:25:55.905  5057  5057 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-22 12:25:55.905  5057  5057 E audit   : type=1300 msg=audit(1474539955.905:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d92bf3c8 items=0 ppid=3173 pid=9554 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-22 12:25:55.905  5057  5057 E audit   : type=1327 msg=audit(1474539955.905:265): proctitle="com.test.thalitest"
09-22 12:25:55.905  5057  5057 E audit   : type=1320 msg=audit(1474539955.905:265): 
,09-22 12:25:55.905  9490  9554 W jxcore-log: Starting JXcore engine
,09-22 12:25:55.945  9490  9554 W jxcore-log: Platform android
09-22 12:25:55.945  9490  9554 W jxcore-log: 
09-22 12:25:55.945  9490  9554 W jxcore-log: Process ARCH arm
09-22 12:25:55.945  9490  9554 W jxcore-log: 
,09-22 12:25:56.015  9490  9554 I jxcore-log: JXcore Cordova bridge is ready!
09-22 12:25:56.015  9490  9554 I jxcore-log: 
09-22 12:25:56.015  9490  9554 W jxcore-log: JXcore engine is started
,09-22 12:25:56.015  9490  9553 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 12:25:56.025  9490  9490 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 12:25:56.055  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:56.235  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:56.415  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:56.525  3405  3901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-22 12:25:56.595  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:56.775  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:56.955  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:56.975  3405  6249 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-22 12:25:57.135  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:57.315  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:57.415  3405  6249 D SSRM:n  : SIOP:: AP = 290, PST = 270 (W:6), CP = 227, CUR = 9, LCD = 1
,09-22 12:25:57.495  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:57.675  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:57.855  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:58.035  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:58.205  3405  3849 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-22 12:25:58.215  3405  3849 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-22 12:25:58.215  3405  3849 D BatteryService: online:4, current avg:-46, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-242
09-22 12:25:58.215  3405  3849 D BatteryService: stay LED for fully charged
09-22 12:25:58.215  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:58.215  3405  3405 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-22 12:25:58.215  3405  3405 I MotionRecognitionService: Plugged
,09-22 12:25:58.215  3405  3405 D MotionRecognitionService:   cableConnection= 1
09-22 12:25:58.215  3405  3405 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-22 12:25:58.215  3405  3405 D MotionRecognitionService: skip setTransmitPower. 
,09-22 12:25:58.225  3405  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-22 12:25:58.225  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-22 12:25:58.225  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
09-22 12:25:58.225  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-22 12:25:58.235  5088  5088 D CommonServiceConfiguration: getStringValueSetting
,09-22 12:25:58.235  5047  5047 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-22 12:25:58.245  5047  5413 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-22 12:25:58.245  4715  4715 D BatteryController: saveBatteryData : level[100], status[5]
,09-22 12:25:58.245  5088  5088 D BatteryMonitor: new battery level: 100
,09-22 12:25:58.255  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-22 12:25:58.255  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-22 12:25:58.395  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:58.575  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:58.755  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:58.935  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:59.115  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:59.295  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:59.475  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:59.655  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:59.835  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:25:59.985  3405  3811 V AlarmManager: Expired Alarm result :8
,09-22 12:26:00.015  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:00.035  3405  6249 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-22 12:26:00.135  9490  9554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 12:26:00.135  9490  9554 I jxcore-log: 
,09-22 12:26:00.135  9490  9554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 12:26:00.135  9490  9554 I jxcore-log: 
,09-22 12:26:00.145  9490  9554 D BluetoothAdapter: STATE_ON
,09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:26:00.155  9490  9554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 12:26:00.155  9490  9554 D BluetoothAdapter: STATE_ON
,09-22 12:26:00.165  9490  9554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 12:26:00.165  9490  9554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 12:26:00.165  9490  9554 I jxcore-log: 
09-22 12:26:00.165  9490  9554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 12:26:00.165  9490  9554 I jxcore-log: 
,09-22 12:26:00.195  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:00.375  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:00.395  9490  9554 D executeNativeTests: Running unit tests
,09-22 12:26:00.395  9490  9554 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-22 12:26:00.395  9490  9554 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-22 12:26:00.395  9490  9554 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-22 12:26:00.395  9490  9554 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 12:26:00.405  9490  9554 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-22 12:26:00.405  9490  9554 I jxcore-log: *Native tests were executed*
09-22 12:26:00.405  9490  9554 I jxcore-log: 
09-22 12:26:00.405  9490  9554 I jxcore-log: Total number of executed tests:  1
09-22 12:26:00.405  9490  9554 I jxcore-log: 
,09-22 12:26:00.405  9490  9554 I jxcore-log: Number of passed tests:  1
09-22 12:26:00.405  9490  9554 I jxcore-log: 
09-22 12:26:00.405  9490  9554 I jxcore-log: Number of failed tests:  0
09-22 12:26:00.405  9490  9554 I jxcore-log: 
09-22 12:26:00.405  9490  9554 I jxcore-log: Number of ignored tests:  0
09-22 12:26:00.405  9490  9554 I jxcore-log: 
09-22 12:26:00.405  9490  9554 I jxcore-log: Total duration:  1
09-22 12:26:00.405  9490  9554 I jxcore-log: 
,09-22 12:26:00.405  9490  9554 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 12:26:00.405  9490  9554 I jxcore-log: 
09-22 12:26:00.405  9490  9554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 12:26:00.405  9490  9554 I jxcore-log: 
,09-22 12:26:00.425  9490  9490 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-22 12:26:00.555  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:00.735  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:00.895  9556  9556 I FIPS_bssl: FIPS approved mode (1) | 9556 | app_process
,09-22 12:26:00.895  9556  9556 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 12:26:00.905  9556  9556 D AndroidRuntime: CheckJNI is OFF
09-22 12:26:00.905  9556  9556 D AndroidRuntime: readGMSProperty: start
09-22 12:26:00.905  9556  9556 D AndroidRuntime: readGMSProperty: already setted!!
09-22 12:26:00.905  9556  9556 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-22 12:26:00.905  9556  9556 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-22 12:26:00.905  9556  9556 D AndroidRuntime: readGMSProperty: end
09-22 12:26:00.905  9556  9556 D AndroidRuntime: addProductProperty: start
,09-22 12:26:00.915  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:00.925  9556  9556 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-22 12:26:00.935  3405  3811 V AlarmManager: Expired Alarm result :4
,09-22 12:26:00.935  3405  3811 V AlarmManager: Send whitelist package alarm :PendingIntent{2d0c96d: PendingIntentRecord{ca5e2f com.samsung.android.app.aodservice broadcastIntent}}
,09-22 12:26:00.945  9556  9556 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 12:26:00.945  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-22 12:26:00.945  3944  3944 D KeyguardUpdateMonitor: handleTimeUpdate
,09-22 12:26:00.945  9556  9556 E AffinityControl: AffinityControl: registerfunction enter
,09-22 12:26:00.955  9556  9556 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 12:26:00.955  3405  4764 D PackageManager: START PACKAGE DELETE: observer{55738687}
09-22 12:26:00.955  3405  4764 D PackageManager: pkg{<packageName>}
09-22 12:26:00.955  3405  4764 D PackageManager: user{0}
09-22 12:26:00.955  3405  4764 D PackageManager: caller{2000}
09-22 12:26:00.955  3405  4764 D PackageManager: flags{2}
,09-22 12:26:00.965  3405  4764 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-22 12:26:00.965  3405  3510 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-22 12:26:00.965  3405  4764 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-22 12:26:00.965  3405  4764 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-22 12:26:00.965  3405  3510 I ActivityManager: Killing 9490:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
09-22 12:26:00.965  3405  4764 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-22 12:26:00.965  3405  4764 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-22 12:26:00.965  3405  3571 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-22 12:26:00.965  3405  3571 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-22 12:26:00.965  3405  3571 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-22 12:26:00.965  3405  3571 D ApplicationPolicy: getApplicationUninstallationEnabled
09-22 12:26:00.965  3405  3571 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-22 12:26:00.965  3405  3571 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-22 12:26:00.965  3405  3571 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-22 12:26:00.975  3405  3510 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-22 12:26:00.965  3944  3944 D Clock   : received broadcast android.intent.action.TIME_TICK
09-22 12:26:00.965  3405  3571 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
09-22 12:26:00.965  3405  3571 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-22 12:26:00.965  3405  3571 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-22 12:26:00.985  3405  3571 D AASAinstall: there is not AASApackages.xml file
,09-22 12:26:00.985  3405  3510 D ActivityManager: mDVFSHelper.acquire()
,09-22 12:26:01.065  3405  4593 D GraphicsStats: Buffer count: 5
,09-22 12:26:01.065  3405  4764 I WindowState: WIN DEATH: Window{732d1dc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 12:26:01.065  3405  3976 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@33c6a0c)
,09-22 12:26:01.075  3003  3012 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
09-22 12:26:01.075  3405  3863 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-22 12:26:01.075  3405  3863 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-22 12:26:01.075  3003  3014 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
09-22 12:26:01.075  3405  3863 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-22 12:26:01.075  3003  4487 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-22 12:26:01.085  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:01.275  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:01.275  3405  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-22 12:26:01.335  3405  3415 I art     : Background sticky concurrent mark sweep GC freed 194193(12MB) AllocSpace objects, 86(1860KB) LOS objects, 25% free, 42MB/56MB, paused 3.564ms total 124.828ms
,09-22 12:26:01.355  3405  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-22 12:26:01.365  3405  3510 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-22 12:26:01.365  3161  3161 W keystore: ENTER clear_uid from uid 1000 for 10171
09-22 12:26:01.365  3405  3510 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-22 12:26:01.365  3405  3571 I art     : Starting a blocking GC Explicit
09-22 12:26:01.365  3405  3510 E ActivityManager: Failure starting process com.test.thalitest
09-22 12:26:01.365  3405  3510 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5277)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5194)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5032)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2643)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4997)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4958)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7379)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9146)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8769)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8924)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:458)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:26:01.365  3405  3510 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 12:26:01.375  3405  3510 I ActivityManager:   Force finishing activity ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4}
09-22 12:26:01.375  3405  3510 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-22 12:26:01.395  3405  3405 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
09-22 12:26:01.395  3003  3003 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-22 12:26:01.405  3405  3510 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-22 12:26:01.415  3405  3510 D InputDispatcher: Focused application released
,09-22 12:26:01.415  4277  4277 D Launcher: onRestart, Launcher: 237373656
,09-22 12:26:01.415  3405  3544 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-22 12:26:01.415  3405  3544 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-22 12:26:01.415  3405  3544 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-22 12:26:01.415  3405  3544 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-22 12:26:01.415  3405  3544 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-22 12:26:01.415  3405  3544 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 12:26:01.415  3405  3544 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 12:26:01.415  3405  3544 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.415  3405  3544 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:26:01.415  3405  3544 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 12:26:01.415  3405  3544 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 12:26:01.415  3405  3544 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8a3eea4 V.E...... R.....ID 0,0-0,0}
,09-22 12:26:01.415  3405  3544 W WindowManager: Failed looking up window
09-22 12:26:01.415  3405  3544 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@75ac40d does not exist
09-22 12:26:01.415  3405  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:26:01.415  3405  3544 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 12:26:01.415  3405  3544 W WindowManager: Attempted to add application window with unknown token Token{dac9611 ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
09-22 12:26:01.425  3405  3544 D ViewRootImpl: #3 mView = null
,09-22 12:26:01.425  3405  3544 W WindowManager: Token{dac9611 ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{dac9611 ActivityRecord{f997638 u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-22 12:26:01.425  3405  3544 W WindowManager: view not successfully added to wm, removing view
,09-22 12:26:01.425  3405  3544 W WindowManager: Exception when adding starting window
09-22 12:26:01.425  3405  3544 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{8a3eea4 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-22 12:26:01.425  3405  3544 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:122)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4395)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:26:01.425  3405  3544 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 12:26:01.435  3405  4394 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,09-22 12:26:01.435  3405  4394 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:26:01.435  4277  4277 D Launcher: onStart, Launcher: 237373656
09-22 12:26:01.435  4277  4277 D Launcher.HomeView: onStart
09-22 12:26:01.435  3405  3405 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-22 12:26:01.435  3405  3405 I KnoxTimeoutHandler: Shared devices show user statefalse
09-22 12:26:01.435  3405  3405 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
09-22 12:26:01.435  4277  4277 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
09-22 12:26:01.435  4277  4277 V ActivityThread: updateVisibility : ActivityRecord{b452a9c token=android.os.BinderProxy@7df0897 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-22 12:26:01.445  4277  4277 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-22 12:26:01.445  4277  4277 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-22 12:26:01.445  4277  4277 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,09-22 12:26:01.445  4277  4277 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
,09-22 12:26:01.445  4277  4277 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
,09-22 12:26:01.445  4277  4277 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-22 12:26:01.445  4277  4277 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-22 12:26:01.445  4277  4277 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-22 12:26:01.445  4277  4277 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-22 12:26:01.455  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:26:01.455  3003  3003 I SurfaceFlinger: id=21 createSurf (1440x2560),1 flag=4, MauncherAct
,09-22 12:26:01.455  3405  6249 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-22 12:26:01.455  4277  4615 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-22 12:26:01.475  3944  3944 D DateView: received broadcast android.intent.action.TIME_TICK
,09-22 12:26:01.485  3405  6249 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-22 12:26:01.485  3405  4437 V WindowStateAnimator: Finishing drawing window Window{35351c0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-22 12:26:01.485  3405  6249 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-22 12:26:01.485  3003  3003 D libEGL  : eglInitialize EGLDisplay = 0x7ff97b0dc8
,09-22 12:26:01.505  7897  7897 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-22 12:26:01.505  7897  7897 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-22 12:26:01.505  3003  3003 I SurfaceFlinger: id=22 createSurf (1592x384),1 flag=4, VSBConnecti
09-22 12:26:01.505  4715  4715 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-22 12:26:01.515  4715  4715 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-22 12:26:01.515  3405  4312 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-22 12:26:01.515  3405  4312 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-22 12:26:01.515  3405  4312 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-22 12:26:01.515  3405  4312 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-22 12:26:01.515  3405  3571 I art     : Explicit concurrent mark sweep GC freed 112245(7MB) AllocSpace objects, 7(1932KB) LOS objects, 32% free, 33MB/49MB, paused 4.541ms total 155.858ms
09-22 12:26:01.515  3003  3003 D libEGL  : eglInitialize EGLDisplay = 0x7ff97b0dc8
,09-22 12:26:01.515  3163  3163 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-22 12:26:01.525  3405  4312 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-22 12:26:01.535  6316  6316 V ActivityThread: updateVisibility : ActivityRecord{b52194b token=android.os.BinderProxy@1e939ec {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
09-22 12:26:01.525  3405  4312 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-22 12:26:01.535  3405  6249 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-22 12:26:01.525  3405  4312 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-22 12:26:01.535  3405  6249 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-22 12:26:01.535  3405  4854 V WindowStateAnimator: Finishing drawing window Window{8d8aa1f u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
09-22 12:26:01.535  3405  6249 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-22 12:26:01.535  4715  4715 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@549c1c0, service=Device Physical Context Monitor
09-22 12:26:01.535  4715  4715 I AlpmModeManager: startAlpmMode : state  = BLANK
09-22 12:26:01.535  4277  4277 D Launcher.HomeView: onStop
,09-22 12:26:01.535  4277  4277 D capture : ----destroy
09-22 12:26:01.535  4715  4715 D DefaultClockView: Window showed. Time views updating
,09-22 12:26:01.535  3405  3446 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3405
09-22 12:26:01.535  3405  3446 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:26:01.535  3405  3446 D PowerManagerService: mDisplayReady: false
,09-22 12:26:01.535  3405  3446 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:26:01.535  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-22 12:26:01.535  4715  4715 D AODUpdatePositionController: updatePosition: direction[7] updatePosition: X[45] Y[324] NewPositionTimer[56]
09-22 12:26:01.535  3405  3446 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:26:01.535  4715  4715 D DefaultClockView: LocalTime Pattern : HH:mm
09-22 12:26:01.535  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:26:01.535  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-22 12:26:01.535  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:26:01.545  4715  4715 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:26 time02: null ampm: null
09-22 12:26:01.545  3003  3003 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f85743c00
09-22 12:26:01.545  3405  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-22 12:26:01.545  3003  3003 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-22 12:26:01.545  3405  3571 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-22 12:26:01.545  3405  3571 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-22 12:26:01.545  3405  3571 D AASAinstall: there is not AASApackages.xml file
09-22 12:26:01.545  3405  3571 D PackageManager: result of delete: 1{55738687}
,09-22 12:26:01.545  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-22 12:26:01.545  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-22 12:26:01.545  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:26:01.545  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:26:01.545  3405  3549 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:26:01.545  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:26:01.545  3405  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:26:01.545  3405  3549 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:26:01.545  3405  3405 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-22 12:26:01.545  3405  3549 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:26:01.545  3405  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c491c9a u0 com.samsung.android.MtpApplication/.USBConnection t3} time:216695
09-22 12:26:01.545  3405  3549 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:26:01.545  9556  9556 I art     : System.exit called, status: 0
09-22 12:26:01.545  3405  3549 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:26:01.545  9556  9556 I AndroidRuntime: VM exiting with result code 0.
09-22 12:26:01.545  3405  3549 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:26:01.545  3405  3571 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-22 12:26:01.545  3405  3571 D PackageManager: userId{-1}
09-22 12:26:01.545  3405  3571 D PackageManager: andCode{true}
09-22 12:26:01.545  3405  3549 D PowerManagerService: mDisplayReady: true
09-22 12:26:01.545  3405  3549 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:26:01.545  3405  3544 D ActivityManager: mDVFSHelper.release()
09-22 12:26:01.555  3405  3405 I KnoxTimeoutHandler: SD activityfalse
09-22 12:26:01.555  4715  4715 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
09-22 12:26:01.555  4715  4715 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
09-22 12:26:01.555  4715  4715 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:czw., 22 wrz 12:26
09-22 12:26:01.555  4715  4715 I AODService.ClockTimer: startAlarm : TICK
09-22 12:26:01.555  3405  4593 V AlarmManager: Add whitelist package alarm :PendingIntent{c835110: PendingIntentRecord{ca5e2f com.samsung.android.app.aodservice broadcastIntent}}
,09-22 12:26:01.565  3405  3571 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-22 12:26:01.565  3405  4764 V WindowStateAnimator: Finishing drawing window Window{bb61e3e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-22 12:26:01.565  3405  3544 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-22 12:26:01.565  6316  6316 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e939ec time:216715
09-22 12:26:01.565  3405  3544 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-22 12:26:01.565  3163  3204 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,09-22 12:26:01.575  3405  3814 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,09-22 12:26:01.575  3405  3813 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 26, 1,
,09-22 12:26:01.575  3405  3813 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 26, 1
09-22 12:26:01.575  3163  3206 D Sensorhubs: sendContextData: -63, 14, 10, 26, 1
,09-22 12:26:01.575  3405  3813 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
09-22 12:26:01.575  3405  3813 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-22 12:26:01.575  3405  3813 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-22 12:26:01.575  3405  3813 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
09-22 12:26:01.575  3405  3813 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,09-22 12:26:01.575  3405  3816 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-22 12:26:01.585  3003  3003 D libEGL  : eglInitialize EGLDisplay = 0x7ff97b0dc8
,09-22 12:26:01.595  9035  9567 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-22 12:26:01.595  9035  9567 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-22 12:26:01.595  3405  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:26:01.595  3405  3405 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:26:01.595  3405  3544 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ee3b808 u0 com.sec.android.app.launcher/.activities.LauncherActivity t1} time:216748
09-22 12:26:01.595  3405  3978 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-22 12:26:01.595  9035  9567 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-22 12:26:01.605  3405  3405 I KnoxTimeoutHandler: SD activityfalse
09-22 12:26:01.605  3405  3978 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-22 12:26:01.615  4715  4715 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
09-22 12:26:01.615  3405  4856 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-22 12:26:01.615  4715  4715 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
09-22 12:26:01.615  3405  4856 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-22 12:26:01.625  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.625  4715  4715 D DefaultClockView: RootView invalidate()
09-22 12:26:01.625  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.635  3405  3791 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-22 12:26:01.635  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-22 12:26:01.635  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-22 12:26:01.645  3405  4437 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3405
,09-22 12:26:01.645  4715  4715 I AODService: onSContextChanged: AODScreenShown state is already true
,09-22 12:26:01.645  3405  4312 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3405
,09-22 12:26:01.645  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-22 12:26:01.655  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.655  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-22 12:26:01.655  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.655  3944  3944 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-22 12:26:01.665  3944  3944 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,09-22 12:26:01.665  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.665  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.665  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-22 12:26:01.665  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-22 12:26:01.665  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-22 12:26:01.665  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-22 12:26:01.675  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.675  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.675  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-22 12:26:01.675  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-22 12:26:01.675  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-22 12:26:01.675  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-22 12:26:01.675  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-22 12:26:01.675  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.675  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-22 12:26:01.675  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-22 12:26:01.685  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-22 12:26:01.685  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-22 12:26:01.685  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-22 12:26:01.685  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-22 12:26:01.685  4300  4771 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-22 12:26:01.685  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,09-22 12:26:01.685  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.685  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.685  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-22 12:26:01.695  5088  5333 D PresenceModule: onReceive: package removed
,09-22 12:26:01.695  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-22 12:26:01.695  5088  5333 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
09-22 12:26:01.695  5088  5333 D PresenceModule: Application package removed
09-22 12:26:01.695  5088  5333 D PresenceModule: onAppPkgRemoved: com.test.thalitest
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  5088  5333 D PresenceModule: onApplicationPackageRemoved: invalid package
,09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-22 12:26:01.695  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.695  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-22 12:26:01.695  3405  3505 D AccessibilityManagerService: onUserStateChangedLocked()
09-22 12:26:01.695  3405  3505 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
,09-22 12:26:01.695  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-22 12:26:01.695  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,09-22 12:26:01.705  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3851 D NtpTrustedTime: currentTimeMillis() cache hit
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3851 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-22 12:26:01.705  3405  3851 V NetworkStats: performPollLocked(flags=0x3)
,09-22 12:26:01.705  3405  3852 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3852 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3851 D NetworkStatsRecorder: entry.iface is null
09-22 12:26:01.705  3405  3851 D NetworkStatsRecorder: entry.iface is null
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3851 D NetworkStatsRecorder: entry.iface is null
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3851 D NetworkStatsRecorder: entry.iface is null
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in nul,l rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-22 12:26:01.705  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-22 12:26:01.715  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-22 12:26:01.715  3405  3851 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708- -> /data/system/netstats/uid.1473847817708-.backup
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-22 12:26:01.715  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-22 12:26:01.715  3405  3851 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-22 12:26:01.715  3405  3851 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-.backup -> /data/system/netstats/uid.1473847817708-
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-22 12:26:01.715  3405  3505 D EnterpriseDeviceManagerService: Package has changed for user 0
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-22 12:26:01.715  3405  3505 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-22 12:26:01.715  3405  3510 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d96e185 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a115703 5785:com.samsung.klmsagent/u0a26}
09-22 12:26:01.715  5785  5785 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Thu Sep 22 12:26:01 GMT+02:00 2016
09-22 12:26:01.715  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-22 12:26:01.715  4265  4265 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-22 12:26:01.715  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-22 12:26:01.725  3405  3544 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:26:01.715  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-22 12:26:01.715  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-22 12:26:01.715  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-22 12:26:01.715  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-22 12:26:01.725  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.725  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-22 12:26:01.725  3405  3405 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-22 12:26:01.725  3405  4312 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4814, uid=10124 that is not exported from uid 10122
09-22 12:26:01.725  3405  3851 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-22 12:26:01.725  3405  3405 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.725  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.735  3405  3405 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-22 12:26:01.725  3405  3405 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-22 12:26:01.735  3405  3405 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-22 12:26:01.735  3405  3405 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-22 12:26:01.725  3405  3405 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
09-22 12:26:01.735  3405  3405 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-22 12:26:01.735  3405  3405 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-22 12:26:01.735  3405  3851 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.735  3405  3851 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201655233-1473847639678
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.735  3405  3405 I OTPFW   : ProvisionData::getAllEntries Enter
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: Can't write: netstats_dump
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1222)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 12:26:01.725  3405  3851 E DropBoxManagerService: 	... 16 more
09-22 12:26:01.735  3405  3405 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-22 12:26:01.725  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-22 12:26:01.735  3405  3405 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
09-22 12:26:01.735  3405  3901 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/4_task.xml
09-22 12:26:01.735  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.735  3405  3851 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157707- -> /data/system/netstats/uid_tag.1474285157707-.backup
09-22 12:26:01.735  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-22 12:26:01.735  3405  3851 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157707-
09-22 12:26:01.735  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-22 12:26:01.735  3405  3544 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-22 12:26:01.745  3405  3851 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157707-.backup -> /data/system/netstats/uid_tag.1474285157707-
09-22 12:26:01.735  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.745  4023  4023 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-22 12:26:01.735  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-22 12:26:01.745  3405  3405 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
09-22 12:26:01.735  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-22 12:26:01.745  3405  3405 D UcmService: Package update in userId-0 and uid-10171
09-22 12:26:01.735  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-22 12:26:01.745  3405  3405 W SQLiteLog: (28) failed to open "/data/system/gamemanager.db" with flag (131138) and mode_t (0) due to error (30)
09-22 12:26:01.735  3405  3876 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
09-22 12:26:01.745  5785  5785 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive().END.
09-22 12:26:01.735  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: Failed to open database '/data/system/gamemanager.db'.
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: #################################################################
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: #################################################################
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-22 12:26:01.745  3405  3405 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-22 12:26:01.735  3405  3544 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.745  3405  3825 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-22 12:26:01.735  3405  3544 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-22 12:26:01.745  3405  3405 D AndroidRuntime: Shutting down VM
09-22 12:26:01.745  3405  3405 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
09-22 12:26:01.745  3405  3405 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } in com.samsung.android.game.GameManagerService$UninstallReceiver@363ac65
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1003)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 12:26:01.745  3405  3405 E AndroidRuntime: #################################################################
09-22 12:26:01.745  3405  3405 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-22 12:26:01.745  3405  3405 E AndroidRuntime: #################################################################
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-22 12:26:01.745  3405  3405 E AndroidRuntime: 	... 8 more
09-22 12:26:01.745  3405  3405 D InjectionManagerService -AppFeature:  Info before com.test.thalitest removal target ={} 
09-22 12:26:01.745  3405  3405 D InjectionManagerService -AppFeature:  source ={}
09-22 12:26:01.745  3405  3851 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-22 12:26:01.745  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.745  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-22 12:26:01.745  3405  3851 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157707-
09-22 12:26:01.745  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: Can't write: netstats_dump
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1223)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 12:26:01.745  3405  3851 E DropBoxManagerService: 	... 16 more
09-22 12:26:01.745  3405  3851 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1473847817708-1474285028441
09-22 12:26:01.745  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.745  3405  3851 D NtpTrustedTime: currentTimeMillis() cache hit
09-22 12:26:01.745  3405  3851 V NetworkStats: performPollLocked() took 45ms
09-22 12:26:01.745  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-22 12:26:01.745  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
,09-22 12:26:01.755  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.755  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-22 12:26:01.755  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.755  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-22 12:26:01.755  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-22 12:26:01.755  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-22 12:26:01.765  5785  5785 I KLMS-2.6.201: : KLMSIntentService(): onCreate()
09-22 12:26:01.765  5785  5785 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-22 12:26:01.765  3405  3852 D NtpTrustedTime: currentTimeMillis() cache hit
09-22 12:26:01.765  3405  3852 D NtpTrustedTime: currentTimeMillis() cache hit
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-22 12:26:01.765  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-22 12:26:01.775  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-22 12:26:01.775  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-22 12:26:01.775  3405  3405 E android.os.Debug: THIS IS SYSTEM_SERVER.. store dumpState!!
09-22 12:26:01.775  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-22 12:26:01.775  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:26:01.775  5785  5785 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-22 12:26:01.775  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-22 12:26:01.775  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
09-22 12:26:01.775  5785  9572 I KLMS-2.6.201: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-22 12:26:01.775  5785  9572 D KLMS-2.6.201: : KLMSIntentService(): PACKAGE_REMOVED
09-22 12:26:01.775  5785  9572 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().START
09-22 12:26:01.775  5785  9572 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-22 12:26:01.775  5785  9572 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-22 12:26:01.785  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-22 12:26:01.775  5785  9572 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
09-22 12:26:01.785  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-22 12:26:01.785  3405  3505 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-22 12:26:01.785  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-22 12:26:01.785  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-22 12:26:01.785  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-22 12:26:01.785  5785  9572 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-22 12:26:01.785  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
09-22 12:26:01.785  3405  4437 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d96e185 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a38cab8 3405:system/1000}
09-22 12:26:01.785  5785  9572 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-22 12:26:01.795  3405  3505 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:26:01.795  3405  3505 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d

```
