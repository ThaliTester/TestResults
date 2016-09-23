#### Test 863677672134d31_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-23 14:20:19.369  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:19.549  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:19.729  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:19.909  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:20.089  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:20.119  9384  9384 I FIPS_bssl: FIPS approved mode (1) | 9384 | app_process
09-23 14:20:20.129  9384  9384 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 14:20:20.129  9384  9384 D AndroidRuntime: CheckJNI is OFF
09-23 14:20:20.129  9384  9384 D AndroidRuntime: readGMSProperty: start
09-23 14:20:20.129  9384  9384 D AndroidRuntime: readGMSProperty: already setted!!
09-23 14:20:20.129  9384  9384 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 14:20:20.129  9384  9384 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 14:20:20.129  9384  9384 D AndroidRuntime: readGMSProperty: end
09-23 14:20:20.129  9384  9384 D AndroidRuntime: addProductProperty: start
09-23 14:20:20.149  9384  9384 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 14:20:20.169  9384  9384 I Radio-JNI: register_android_hardware_Radio DONE
09-23 14:20:20.179  9384  9384 E AffinityControl: AffinityControl: registerfunction enter
09-23 14:20:20.179  9384  9384 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-23 14:20:20.209  3413  4399 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-23 14:20:20.209  3413  4399 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 14:20:20.229  3413  4399 D ResourcesManager: For user 0 new overlays fetched Null
09-23 14:20:20.239  3413  4399 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:20:20.239  3413  4399 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-23 14:20:20.239  3413  4399 D ActivityManager: mDVFSHelper.acquire()
09-23 14:20:20.239  3413  4399 V WindowManager: addAppToken: AppWindowToken{d0fa92bab token=Token{dded9fa ActivityRecord{9262425 u0 com.test.thalitest/.MainActivity t8}}} to stack=2 task=8 at 0
09-23 14:20:20.249  3413  3531 I InjectionManager: Inside getClassLibPath caller 
09-23 14:20:20.259  3413  3531 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 14:20:20.259  3413  3531 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6956523 V.E...... R.....ID 0,0-0,0}
09-23 14:20:20.259  9393  9393 E Zygote  : v2
09-23 14:20:20.259  9393  9393 I libpersona: KNOX_SDCARD checking this for 10171
09-23 14:20:20.259  9393  9393 I libpersona: KNOX_SDCARD not a persona
09-23 14:20:20.259  3413  3531 D ISSUE_DEBUG: InputChannelName : c1f9fd9 Starting com.test.thalitest
09-23 14:20:20.259  3413  3531 W WindowManager: Failed looking up window
09-23 14:20:20.259  3413  3531 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@e7eea20 does not exist
09-23 14:20:20.259  3413  3531 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 14:20:20.259  3413  3531 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 14:20:20.259  9393  9393 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 14:20:20.269  3413  4399 I ActivityManager: Start proc 9393:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-23 14:20:20.269  9393  9393 E Zygote  : accessInfo : 0
09-23 14:20:20.269  3413  4399 D InputDispatcher: Focused application set to: xxxx
09-23 14:20:20.269  9393  9393 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-23 14:20:20.269  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:20.269  9384  9384 D AndroidRuntime: Shutting down VM
09-23 14:20:20.269  3413  3855 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-23 14:20:20.269  3005  3005 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-23 14:20:20.299  9393  9393 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 14:20:20.299  9393  9393 D ActivityThread: Added TimaKeyStore provider
09-23 14:20:20.299  6077  6077 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:20:20.309  3413  4397 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3413
09-23 14:20:20.309  3413  4397 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:20:20.309  3413  4397 D PowerManagerService: mDisplayReady: false
09-23 14:20:20.309  3413  4397 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:20:20.309  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:20:20.309  6077  6077 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:20:20.309  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:20:20.309  3413  4397 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:20:20.309  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f98f43c00
09-23 14:20:20.309  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:20.309  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 14:20:20.309  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:20.309  3413  3549 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 14:20:20.309  3413  4412 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3413
09-23 14:20:20.319  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:20:20.319  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:20:20.319  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:20:20.319  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:20.319  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:20:20.319  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:20.319  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:20:20.319  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:20:20.319  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:20.319  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:20.319  3413  3537 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:20:20.319  3413  3537 D PowerManagerService: mDisplayReady: true
09-23 14:20:20.319  3413  3537 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 14:20:20.319  3413  4355 D ActivityManager:  Launching com.test.thalitest, updated priority
09-23 14:20:20.329  4278  4278 V ActivityThread: updateVisibility : ActivityRecord{cf6038 token=android.os.BinderProxy@6f340d2 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-23 14:20:20.329  3413  4217 V WindowStateAnimator: Finishing drawing window Window{34e5a1d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 14:20:20.339  3413  3413 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-23 14:20:20.339  3413  3497 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-23 14:20:20.349  3005  3014 D libEGL  : eglTerminate EGLDisplay = 0x7f98cc0e78
09-23 14:20:20.349  3005  3014 D libEGL  : eglTerminate EGLDisplay = 0x7f98cc0e78
09-23 14:20:20.349  3005  3071 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-23 14:20:20.349  3005  3014 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-23 14:20:20.359  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fd2e68978
09-23 14:20:20.369  3413  4619 V WindowStateAnimator: Finishing drawing window Window{44adcc7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 14:20:20.369  4278  4278 D Launcher: onTrimMemory. Level: 20
09-23 14:20:20.369  6077  6077 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:20:20.369  6077  6077 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:20:20.369  6077  6077 V ActivityThread: updateVisibility : ActivityRecord{4dfb631 token=android.os.BinderProxy@9b8fc2b {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-23 14:20:20.369  3005  4428 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-23 14:20:20.369  3005  4428 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-23 14:20:20.369  3005  4428 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-23 14:20:20.369  3005  4465 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-23 14:20:20.379  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fd2e68978
09-23 14:20:20.379  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fd2e68948
09-23 14:20:20.379  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fd2e68978
09-23 14:20:20.449  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:20.459  3413  3413 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3413 (0x0)
09-23 14:20:20.459  3413  3413 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3413 (0x0)
09-23 14:20:20.459  3413  3413 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:20:20.459  3413  3413 D PowerManagerService: mDisplayReady: false
09-23 14:20:20.459  3413  3413 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:20:20.459  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:20:20.459  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:20:20.459  3413  3413 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:20:20.469  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f98f43c00
09-23 14:20:20.459  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:20.469  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 14:20:20.459  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:20.459  3413  3549 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 14:20:20.469  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:20:20.469  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:20:20.469  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:20.469  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:20:20.469  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:20.469  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:20:20.469  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:20:20.469  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:20:20.469  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:20.469  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:20.469  3413  3537 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:20:20.469  3413  3537 D PowerManagerService: mDisplayReady: true
09-23 14:20:20.469  3413  3537 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 14:20:20.629  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:20.669  3413  4355 I WindowManager: Screenshot max retries 4 of Token{dded9fa ActivityRecord{9262425 u0 com.test.thalitest/.MainActivity t8}} appWin=Window{c1f9fd9 u0 d0 Starting com.test.thalitest} drawState=1
09-23 14:20:20.669  3413  3531 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:20:20.669  3413  3413 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:20:20.669  3413  3531 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 14:20:20.669  3413  5964 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:20:20.679  3413  5964 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:20:20.679  3413  3413 I KnoxTimeoutHandler: SD activityfalse
09-23 14:20:20.679  3413  3855 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-23 14:20:20.699  9393  9393 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 14:20:20.699  3413  5964 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 14:20:20.699  3413  4052 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-23 14:20:20.709  9393  9393 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-23 14:20:20.709  3413  5964 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:20:20.709  3413  3531 V WindowStateAnimator: Finishing drawing window Window{c1f9fd9 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-23 14:20:20.709  3413  3531 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:20:20.709  3413  3531 D ActivityManager: mDVFSHelper.release()
09-23 14:20:20.709  3413  3413 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:20:20.709  3413  3531 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{31ed5a9 u0 com.samsung.android.MtpApplication/.USBConnection t7} time:232519
09-23 14:20:20.719  3413  3413 I KnoxTimeoutHandler: SD activityfalse
09-23 14:20:20.719  3413  5964 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 14:20:20.719  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fd2e68858
09-23 14:20:20.719  3413  5964 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:20:20.719  3413  5964 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:20:20.719  9393  9393 D ResourcesManager: For user 0 new overlays fetched Null
09-23 14:20:20.729  9393  9393 I InjectionManager: Inside getClassLibPath caller 
09-23 14:20:20.749  9393  9393 D InjectionManager: InjectionManager
09-23 14:20:20.749  9393  9393 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-23 14:20:20.749  9393  9393 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-23 14:20:20.749  9393  9393 I InjectionManager: featureStore :{}
09-23 14:20:20.759  9393  9393 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 14:20:20.759  9393  9393 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-23 14:20:20.759  9393  9393 D RelationGraph: garbageCollect()
09-23 14:20:20.759  9393  9393 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 14:20:20.789  9393  9393 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-23 14:20:20.809  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:20.829  9393  9393 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-23 14:20:20.829  9393  9393 D ResourcesManager: For user 0 new overlays fetched Null
09-23 14:20:20.829  9393  9393 I InjectionManager: Inside getClassLibPath caller 
09-23 14:20:20.839  9393  9393 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-23 14:20:20.889  9393  9393 I cr_LibraryLoader: Time to load native libraries: 35 ms (timestamps 2661-2696)
09-23 14:20:20.889  9393  9393 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 14:20:20.929  3413  3879 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-23 14:20:20.959  9393  9408 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-23 14:20:20.989  9393  9393 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cc08b6b}
09-23 14:20:20.989  9393  9393 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 14:20:20.989  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:21.009  9393  9393 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 14:20:21.029  3413  3879 I MdnieScenarioControlService: mGameModeLauncher : false
09-23 14:20:21.029  3413  3879 I MdnieScenarioControlService: setUIMode
09-23 14:20:21.059  9393  9393 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-23 14:20:21.169  3413  3497 W ActivityManager: Activity pause timeout for ActivityRecord{9262425 u0 com.test.thalitest/.MainActivity t8}
09-23 14:20:21.169  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:21.259  9393  9393 D libEGL  : eglInitialize EGLDisplay = 0xffe008ec
09-23 14:20:21.349  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:21.349  3413  4217 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-23 14:20:21.349  3413  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-23 14:20:21.439  9393  9393 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-23 14:20:21.469  9393  9393 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-23 14:20:21.469  9393  9393 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-23 14:20:21.509  9393  9393 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-23 14:20:21.529  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:21.589  9393  9393 D Activity: performCreate Call Injection manager
09-23 14:20:21.589  9393  9393 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-23 14:20:21.599  9393  9393 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 14:20:21.609  9393  9393 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{15187e6 I.E...... R.....ID 0,0-0,0}
09-23 14:20:21.609  9393  9445 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-23 14:20:21.619  3413  4412 W WindowManager: Failed looking up window
09-23 14:20:21.619  3413  4412 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@e29f880 does not exist
09-23 14:20:21.619  3413  4412 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 14:20:21.619  3413  4412 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 14:20:21.619  3413  4412 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 14:20:21.619  3413  4412 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-23 14:20:21.619  3413  4412 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-23 14:20:21.619  3413  4412 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-23 14:20:21.619  3413  4052 D ISSUE_DEBUG: InputChannelName : 495feb9 com.test.thalitest/com.test.thalitest.MainActivity
09-23 14:20:21.629  3413  4399 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-23 14:20:21.629  3413  4399 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 14:20:21.629  3413  3413 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 14:20:21.629  3413  3413 I KnoxTimeoutHandler: Shared devices show user statefalse
09-23 14:20:21.639  9393  9393 V ActivityThread: updateVisibility : ActivityRecord{5992fd4 token=android.os.BinderProxy@ad81829 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-23 14:20:21.649  9393  9408 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-23 14:20:21.679  9393  9393 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9393
09-23 14:20:21.679  3413  5965 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 14:20:21.679  3413  4399 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9393 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 14:20:21.679  3413  3866 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-23 14:20:21.679  3413  3866 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-23 14:20:21.689  3413  3866 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-23 14:20:21.699  3413  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 14:20:21.699  3413  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 14:20:21.699  9393  9393 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 14:20:21.709  3413  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-23 14:20:21.709  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:21.709  3413  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 14:20:21.719  3413  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-23 14:20:21.719  3413  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 14:20:21.719  3005  3005 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
09-23 14:20:21.739  9393  9445 D libEGL  : eglInitialize EGLDisplay = 0xdc2bf7c4
09-23 14:20:21.739  9393  9445 I OpenGLRenderer: Initialized EGL, version 1.4
09-23 14:20:21.749  9393  9445 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-23 14:20:21.749  3413  4164 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3413
09-23 14:20:21.749  3413  4164 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:20:21.749  3413  4164 D PowerManagerService: mDisplayReady: false
09-23 14:20:21.749  3413  4164 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:20:21.749  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:20:21.749  3413  4164 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:20:21.749  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f98f43c00
09-23 14:20:21.749  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:20:21.749  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 14:20:21.749  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:21.749  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:21.749  3413  3549 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 14:20:21.749  3413  3531 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 14:20:21.749  3413  3531 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-23 14:20:21.769  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:20:21.769  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:20:21.769  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:20:21.769  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:20:21.769  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:21.769  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:21.769  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:20:21.769  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:20:21.769  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:21.769  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:21.769  3413  3537 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:20:21.769  3413  3537 D PowerManagerService: mDisplayReady: true
09-23 14:20:21.769  3413  3537 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 14:20:21.779  3413  5964 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:10), CP = 238, LCD = 1
09-23 14:20:21.789  9393  9393 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-23 14:20:21.799  3413  4840 V WindowStateAnimator: Finishing drawing window Window{495feb9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-23 14:20:21.799  9393  9393 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 14:20:21.809  9393  9449 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 14:20:21.809  9393  9449 D libEGL  : eglInitialize EGLDisplay = 0xdabbf3f4
09-23 14:20:21.809  3413  3437 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3413
09-23 14:20:21.809  3413  3531 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 14:20:21.809  3413  3413 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 14:20:21.809  3413  3531 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s149ms (total +1s568ms)
09-23 14:20:21.809  3413  3531 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9262425 u0 com.test.thalitest/.MainActivity t8} time:233618
09-23 14:20:21.809  3413  3531 D ViewRootImpl: #3 mView = null
09-23 14:20:21.809  3005  3071 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-23 14:20:21.809  3413  3413 I KnoxTimeoutHandler: SD activityfalse
09-23 14:20:21.819  3005  3014 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
09-23 14:20:21.819  3413  3968 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3413
09-23 14:20:21.819  9393  9449 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-23 14:20:21.829  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fd2e68978
09-23 14:20:21.829  3413  4620 V WindowStateAnimator: Finishing drawing window Window{495feb9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-23 14:20:21.839  9393  9393 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ad81829 time:233640
09-23 14:20:21.879  9393  9393 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9393
09-23 14:20:21.889  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:21.969  3413  3413 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3413 (0x0)
09-23 14:20:21.969  3413  3413 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:20:21.969  3413  3413 D PowerManagerService: mDisplayReady: false
09-23 14:20:21.969  3413  3413 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:20:21.969  3413  3413 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:20:21.969  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:20:21.969  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:20:21.969  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:21.969  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:21.969  3413  3549 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 14:20:21.969  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f98f43c00
09-23 14:20:21.969  3413  3531 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 14:20:21.969  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 14:20:21.969  3413  3531 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-23 14:20:21.989  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:20:21.989  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:20:21.989  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:21.989  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:20:21.989  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:21.989  3413  3537 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:20:21.989  3413  3537 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:20:21.989  3413  3537 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:20:21.989  3413  3537 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:20:21.989  3413  3537 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:20:21.989  3413  3537 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:20:21.989  3413  3537 D PowerManagerService: mDisplayReady: true
09-23 14:20:21.989  3413  3537 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 14:20:21.989  9393  9393 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-23 14:20:22.069  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:22.169  4020  4020 D Recents : onTaskStackChanged
09-23 14:20:22.169  4020  4020 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-23 14:20:22.179  4020  4020 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 14:20:22.219  9393  9456 D jxcore_app_log: JniHelper::setJavaVM(0xf4974000), pthread_self() = -632657616
,09-23 14:20:22.219  9393  9456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 14:20:22.219  9393  9456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 14:20:22.219  9393  9456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 14:20:22.219  9393  9456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 14:20:22.219  9393  9456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 14:20:22.219  9393  9456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b696 added. We now have 1 listener(s)
,09-23 14:20:22.229  9393  9456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-23 14:20:22.229  9393  9456 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 14:20:22.229  9393  9456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 14:20:22.229  9393  9456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 14:20:22.229  9393  9456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18e67ed added. We now have 1 listener(s)
09-23 14:20:22.229  9393  9456 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 14:20:22.229  9393  9456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 14:20:22.229  9393  9456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 14:20:22.229  9393  9456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 14:20:22.229  9393  9456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 14:20:22.229  9393  9456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 14:20:22.239  9393  9456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:20:22.239  9393  9456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-23 14:20:22.249  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:22.249  9393  9456 D BluetoothAdapter: STATE_ON
,09-23 14:20:22.249  9393  9456 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:20:22.249  9393  9456 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 14:20:22.249  9393  9456 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 14:20:22.249  9393  9456 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 14:20:22.249  9393  9456 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 14:20:22.259  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:20:22.259  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:20:22.279  9393  9393 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 14:20:22.429  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:22.609  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:22.619  9393  9457 W jxcore-log: Initializing JXcore engine
09-23 14:20:22.619  9393  9457 W jxcore-log: JXcore engine is ready
,09-23 14:20:22.639  4965  4965 E audit   : type=1400 msg=audit(1474633222.639:264): avc:  denied  { ioctl } for  pid=9457 comm="Thread-172" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2241 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 14:20:22.639  4965  4965 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 14:20:22.639  4965  4965 E audit   : type=1300 msg=audit(1474633222.639:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da33f3c8 items=0 ppid=3177 pid=9457 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-172" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 14:20:22.639  4965  4965 E audit   : type=1327 msg=audit(1474633222.639:264): proctitle="com.test.thalitest"
09-23 14:20:22.639  4965  4965 E audit   : type=1320 msg=audit(1474633222.639:264): 
09-23 14:20:22.639  4965  4965 E audit   : type=1400 msg=audit(1474633222.639:265): avc:  denied  { ioctl } for  pid=9457 comm="Thread-172" path="socket:[13291]" dev="sockfs" ino=13291 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 14:20:22.639  4965  4965 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 14:20:22.639  4965  4965 E audit   : type=1300 msg=audit(1474633222.639:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da33f3c8 items=0 ppid=3177 pid=9457 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-172" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 14:20:22.639  4965  4965 E audit   : type=1327 msg=audit(1474633222.639:265): proctitle="com.test.thalitest"
09-23 14:20:22.639  4965  4965 E audit   : type=1320 msg=audit(1474633222.639:265): 
,09-23 14:20:22.639  9393  9457 W jxcore-log: Starting JXcore engine
,09-23 14:20:22.679  9393  9457 W jxcore-log: Platform android
09-23 14:20:22.679  9393  9457 W jxcore-log: 
09-23 14:20:22.679  9393  9457 W jxcore-log: Process ARCH arm
09-23 14:20:22.679  9393  9457 W jxcore-log: 
,09-23 14:20:22.749  9393  9457 I jxcore-log: JXcore Cordova bridge is ready!
09-23 14:20:22.749  9393  9457 I jxcore-log: 
,09-23 14:20:22.749  9393  9457 W jxcore-log: JXcore engine is started
,09-23 14:20:22.759  9393  9456 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 14:20:22.769  9393  9393 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 14:20:22.789  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:22.969  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:23.149  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:23.189  3149  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 14:20:23.249  3413  3904 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/8_task.xml.bak
,09-23 14:20:23.329  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:23.509  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:23.679  3413  5964 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-23 14:20:23.689  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:23.869  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:24.049  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:24.229  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:24.409  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:24.589  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:24.769  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:24.949  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:25.129  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:25.309  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:25.489  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:25.669  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:25.849  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:26.029  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:26.209  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:26.389  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:26.569  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:26.729  3413  5964 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-23 14:20:26.749  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:26.929  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:27.109  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:27.289  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:27.469  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:27.649  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:27.829  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:28.009  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:28.189  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:28.369  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:28.549  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:28.729  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:28.869  9393  9457 I jxcore-log: 2016-09-23 12:20:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 14:20:28.869  9393  9457 I jxcore-log: 
,09-23 14:20:28.869  9393  9457 I jxcore-log: 2016-09-23 12:20:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 14:20:28.869  9393  9457 I jxcore-log: 
,09-23 14:20:28.879  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:20:28.879  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:20:28.889  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:28.889  9393  9457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 14:20:28.889  9393  9457 I jxcore-log: 2016-09-23 12:20:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 14:20:28.889  9393  9457 I jxcore-log: 
09-23 14:20:28.889  9393  9457 I jxcore-log: 2016-09-23 12:20:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 14:20:28.889  9393  9457 I jxcore-log: 
,09-23 14:20:28.909  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:29.039  9393  9457 I jxcore-log: Running unit tests
09-23 14:20:29.039  9393  9457 I jxcore-log: 
,09-23 14:20:29.039  9393  9457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 14:20:29.039  9393  9457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e006ac added. We now have 2 listener(s)
09-23 14:20:29.039  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 14:20:29.039  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 14:20:29.039  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 14:20:29.039  9393  9457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 14:20:29.039  9393  9457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b736f75 added. We now have 2 listener(s)
09-23 14:20:29.039  9393  9457 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 14:20:29.039  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 14:20:29.049  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:20:29.059  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:20:29.059  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:20:29.069  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:29.069  9393  9457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 14:20:29.069  9393  9457 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 14:20:29.069  9393  9457 D executeNativeTests: Running unit tests
,09-23 14:20:29.079  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:20:29.079  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:20:29.089  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:29.109  9393  9457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 14:20:29.109  9393  9457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802ed6b added. We now have 3 listener(s)
09-23 14:20:29.109  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 14:20:29.109  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 14:20:29.109  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 14:20:29.109  9393  9457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 14:20:29.109  9393  9457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 added. We now have 3 listener(s)
09-23 14:20:29.109  9393  9457 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 14:20:29.109  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 14:20:29.109  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:20:29.119  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:20:29.119  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:20:29.129  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:29.129  9393  9457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:29.129  9393  9457 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 14:20:29.129  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 14:20:29.129  9393  9457 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-23 14:20:29.129  9393  9457 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 14:20:29.129  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-23 14:20:29.129  9393  9457 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 14:20:29.129  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 14:20:29.129  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 14:20:29.129  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 14:20:29.129  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.129  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 14:20:29.129  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802ed6b removed from the list
09-23 14:20:29.129  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:29.129  9393  9457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 removed from the list
09-23 14:20:29.129  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 14:20:29.129  9393  9457 D io.jxcore.node.ConnectivityMonitor: stop
09-23 14:20:29.129  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.129  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.129  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:29.139  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 14:20:29.139  9393  9457 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 14:20:29.139  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 14:20:29.139  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 14:20:29.139  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.139  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.139  9393  9457 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802ed6b not in the list
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:29.139  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 14:20:29.139  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.139  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.139  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.139  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:29.139  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 14:20:29.139  9393  9457 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 14:20:29.139  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 14:20:29.139  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 14:20:29.139  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.139  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.139  9393  9457 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802ed6b not in the list
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:29.139  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:29.139  9393  9457 D io.jxcore.node.ConnectivityMonitor: stop
09-23 14:20:29.139  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.139  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.139  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:29.139  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 14:20:29.139  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:29.139  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:29.139  9393  9457 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 14:20:29.149  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:29.149  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:20:29.149  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 14:20:29.149  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.149  9393  9457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:29.149  9393  9457 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 14:20:29.149  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 14:20:29.149  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 14:20:29.149  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 14:20:29.149  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:29.149  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 14:20:29.159  9393  9457 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 14:20:29.159  9393  9457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 14:20:29.159  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 14:20:29.159  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.159  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.159  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.159  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 14:20:29.169  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 14:20:29.169  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.169  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.169  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 14:20:29.169  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 14:20:29.169  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.169  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.179  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-23 14:20:29.179  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.179  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.179  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 14:20:29.179  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 14:20:29.179  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 14:20:29.179  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 14:20:29.179  9393  9457 D BluetoothLeScanner: Start Scan
09-23 14:20:29.179  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.189  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.189  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.189  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:29.199  4956  5355 D BtGatt.GattService: registerClient() - UUID=f621e885-771c-4ab6-820c-0e1638f7130b
,09-23 14:20:29.239  4956  5058 D BtGatt.GattService: onClientRegistered() - UUID=f621e885-771c-4ab6-820c-0e1638f7130b, clientIf=7
,09-23 14:20:29.249  9393  9404 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-23 14:20:29.249  4956  5354 D BtGatt.GattService: start scan with filters
,09-23 14:20:29.249  4956  5354 D BtGatt.GattService: getScanSettings
,09-23 14:20:29.269  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:29.269  4956  5354 D BtGatt.GattService: Is it foreground application = true
,09-23 14:20:29.269  4956  5354 D BtGatt.GattService: not a background application
,09-23 14:20:29.279  4956  5354 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 14:20:29.289  4956  5354 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 14:20:29.289  4956  5354 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 14:20:29.299  4956  5129 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-23 14:20:29.299  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 14:20:29.299  4956  5129 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 14:20:29.299  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 14:20:29.299  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 14:20:29.299  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 14:20:29.299  4956  5118 D BtGatt.ScanManager: handling starting scan
,09-23 14:20:29.299  4956  5118 D BtGatt.ScanManager: isFilteringSupported
,09-23 14:20:29.299  4956  5118 D BluetoothAdapter: enableStandAloneBleMode=
,09-23 14:20:29.299  4956  5118 D BluetoothAdapter: STATE_ON
,09-23 14:20:29.299  4956  5118 D BluetoothAdapter: STATE_ON
09-23 14:20:29.309  4956  5118 D BluetoothAdapter: STATE_ON
09-23 14:20:29.309  4956  5118 D BluetoothAdapter: STATE_ON
09-23 14:20:29.309  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 14:20:29.309  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 14:20:29.309  9393  9393 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 14:20:29.309  4956  5118 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ebce0ba
,09-23 14:20:29.319  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 14:20:29.319  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 42
09-23 14:20:29.319  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-23 14:20:29.319  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{54a7e86: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.319  4956  5058 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-23 14:20:29.319  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:29.329  4956  5118 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-23 14:20:29.329  9393  9457 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 14:20:29.329  4956  5118 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-23 14:20:29.329  4956  5118 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 14:20:29.329  4956  5118 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 12
,09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577220
,09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-23 14:20:29.329  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{4e8e347: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-23 14:20:29.329  4956  5058 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 14:20:29.329  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:20:29.329  4956  5118 D BtGatt.ScanManager: Starting BLE batch scan
,09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 14:20:29.329  4956  5118 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:29.329  4956  5129 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577220
,09-23 14:20:29.339  4956  5058 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 14:20:29.339  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:29.339  4956  5058 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-23 14:20:29.339  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:29.339  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{c529774: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:29.339  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{108049d: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.349  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{8466ce3: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.349  3413  4412 V AlarmManager:  remove PendingIntent] PendingIntent{5bbb6e0: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.349  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{3e54d99: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.359  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{39cd85e: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.359  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{a68f43f: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.369  3413  4217 V AlarmManager:  remove PendingIntent] PendingIntent{d5610c: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.369  3413  4620 V AlarmManager:  remove PendingIntent] PendingIntent{9b42a55: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.379  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{95a1c6a: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.379  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{402955b: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.389  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{dfd81f8: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:29.449  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:29.629  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:29.809  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:29.819  9393  9393 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 14:20:29.819  9393  9393 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 14:20:29.819  9393  9393 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 14:20:29.989  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:30.169  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:30.299  3413  3556 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-23 14:20:30.319  3413  3556 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 14:20:30.339  3413  3814 V AlarmManager: Expired Alarm result :4
,09-23 14:20:30.349  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:30.349  4956  4956 D BtGatt.ScanManager: awakened up at time 242152
,09-23 14:20:30.349  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:20:30.349  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{ff59536: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:30.359  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
,09-23 14:20:30.359  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:30.359  4956  5058 D BtGatt.GattService: current time is 242162709019
09-23 14:20:30.359  3413  4412 V AlarmManager:  remove PendingIntent] PendingIntent{ccb2c37: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
,09-23 14:20:30.359  4956  5058 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 14:20:30.359  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-23 14:20:30.359  4956  5058 D ScanRecord: parseFromBytes
,09-23 14:20:30.359  4956  5058 D ScanRecord: first manudata for manu ID
,09-23 14:20:30.369  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-23 14:20:30.369  4956  5058 D ScanRecord: parseFromBytes
,09-23 14:20:30.369  4956  5058 D ScanRecord: first manudata for manu ID
,09-23 14:20:30.369  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-23 14:20:30.369  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:30.369  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:30.369  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:20:30.369  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:30.369  4956  5058 D ScanRecord: first manudata for manu ID
,09-23 14:20:30.369  9393  9403 D ScanRecord: parseFromBytes
,09-23 14:20:30.369  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:30.379  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:30.379  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:30.379  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:30.379  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:30.379  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:30.379  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:30.379  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{384c5a4: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:30.389  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{4984f0d: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:30.389  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{dfdcec2: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:30.399  3413  4217 V AlarmManager:  remove PendingIntent] PendingIntent{61c54d3: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:30.399  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{a1a9810: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:30.529  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:30.709  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:30.889  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:31.069  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:31.249  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:31.369  3413  3814 V AlarmManager: Expired Alarm result :4
,09-23 14:20:31.369  4956  4956 D BtGatt.ScanManager: awakened up at time 243170
,09-23 14:20:31.369  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:20:31.369  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{25e150e: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:31.379  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
09-23 14:20:31.379  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:31.379  4956  5058 D BtGatt.GattService: current time is 243186539595
09-23 14:20:31.379  4956  5058 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -87, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 14:20:31.379  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{34d6b2f: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:31.379  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-23 14:20:31.379  4956  5058 D ScanRecord: parseFromBytes
,09-23 14:20:31.379  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:31.379  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:20:31.379  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:31.379  4956  5058 D ScanRecord: first manudata for manu ID
,09-23 14:20:31.389  9393  9404 D ScanRecord: parseFromBytes
,09-23 14:20:31.389  9393  9404 D ScanRecord: first manudata for manu ID
09-23 14:20:31.389  9393  9404 D ScanRecord: parseFromBytes
09-23 14:20:31.389  9393  9404 D ScanRecord: first manudata for manu ID
,09-23 14:20:31.399  3413  3852 V AlarmManager:  remove PendingIntent] PendingIntent{3f9253c: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:31.409  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{2d552c5: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:31.419  3413  4620 V AlarmManager:  remove PendingIntent] PendingIntent{d6a741a: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:31.429  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:31.429  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{bcf8b4b: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:31.439  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{ad15928: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:31.579  3413  4290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-23 14:20:31.579  3413  4290 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-23 14:20:31.579  3413  4290 D BatteryService: online:4, current avg:-89, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-23 14:20:31.579  3413  4290 D BatteryService: stay LED for fully charged
09-23 14:20:31.579  3413  3413 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-23 14:20:31.589  3413  3413 I MotionRecognitionService: Plugged
,09-23 14:20:31.589  3413  3413 D MotionRecognitionService:   cableConnection= 1
09-23 14:20:31.589  3413  3413 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-23 14:20:31.589  3413  3413 D MotionRecognitionService: skip setTransmitPower. 
,09-23 14:20:31.589  3413  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-23 14:20:31.599  3947  3947 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-23 14:20:31.599  3947  3947 D KeyguardUpdateMonitor: handleBatteryUpdate
09-23 14:20:31.599  3947  3947 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-23 14:20:31.609  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:31.629  4999  4999 D CommonServiceConfiguration: getStringValueSetting
,09-23 14:20:31.639  4956  4956 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-23 14:20:31.639  4956  5357 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-23 14:20:31.639  3947  3947 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 14:20:31.639  3947  3947 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 14:20:31.649  4706  4706 D BatteryController: saveBatteryData : level[100], status[5]
,09-23 14:20:31.649  4999  4999 D BatteryMonitor: new battery level: 100
,09-23 14:20:31.789  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:31.799  3413  5964 D SSRM:n  : SIOP:: AP = 330, PST = 284 (W:6), CP = 248, CUR = -89, LCD = 1
,09-23 14:20:31.969  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:32.149  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:32.329  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:32.379  3413  3814 V AlarmManager: Expired Alarm result :4
,09-23 14:20:32.389  4956  4956 D BtGatt.ScanManager: awakened up at time 244195
,09-23 14:20:32.389  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:20:32.399  3413  4412 V AlarmManager:  remove PendingIntent] PendingIntent{eabb7e6: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.399  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
,09-23 14:20:32.399  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:32.399  4956  5058 D BtGatt.GattService: current time is 244207343171
09-23 14:20:32.399  4956  5058 D BtGatt.GattService: Batch record : [50, -35, 86, -77, -92, -11, 1, 0, -98, 18, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -92, 52, 14, 3, 1, -37, 18, -106, 104, 95, 67, 28, 6, 8, 116, 105, 110, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -77, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:20:32.399  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -92, 52, 14, 3, 1, -37, 18, -106, 104, 95, 67, 6, 8, 116, 105, 110, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,09-23 14:20:32.399  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:32.399  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:32.399  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 14:20:32.399  4956  5058 D ScanRecord: parseFromBytes
,09-23 14:20:32.399  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:32.409  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 14:20:32.409  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:32.409  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:32.409  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:20:32.409  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:32.409  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:32.409  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{3099127: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:32.409  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:32.409  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:32.409  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:32.409  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:32.409  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:32.409  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:32.409  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:32.409  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:32.419  3413  4397 V AlarmManager:  remove PendingIntent] PendingIntent{76dfd4: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.429  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{cc8157d: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.429  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{36b6c72: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.439  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{1f418c3: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.439  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{e4c2540: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.449  3413  4620 V AlarmManager:  remove PendingIntent] PendingIntent{9458c79: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.459  3413  4619 V AlarmManager:  remove PendingIntent] PendingIntent{1ffddbe: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.459  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{e757e1f: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:32.509  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:32.689  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:32.869  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:33.049  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:33.229  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:33.409  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:33.409  3413  3814 V AlarmManager: Expired Alarm result :4
,09-23 14:20:33.419  4956  4956 D BtGatt.ScanManager: awakened up at time 245221
,09-23 14:20:33.419  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:20:33.419  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{d897735: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:33.429  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
,09-23 14:20:33.429  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:33.429  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{dd817ca: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:33.429  4956  5058 D BtGatt.GattService: current time is 245237049940
09-23 14:20:33.429  4956  5058 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -90, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:20:33.429  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 14:20:33.429  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:33.429  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:33.439  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:20:33.439  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:33.439  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:33.439  9393  9404 D ScanRecord: parseFromBytes
,09-23 14:20:33.439  9393  9404 D ScanRecord: first manudata for manu ID
09-23 14:20:33.439  9393  9404 D ScanRecord: parseFromBytes
09-23 14:20:33.439  9393  9404 D ScanRecord: first manudata for manu ID
,09-23 14:20:33.439  3413  4397 V AlarmManager:  remove PendingIntent] PendingIntent{c7ddd3b: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:33.449  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{1a15c58: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:33.449  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{fe751b1: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:33.459  3413  4217 V AlarmManager:  remove PendingIntent] PendingIntent{47e696: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:33.469  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{4e31217: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:33.589  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:33.769  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:33.949  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:34.129  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:34.309  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:34.339  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.339  9393  9457 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 14:20:34.339  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 14:20:34.339  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 14:20:34.339  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:34.339  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 14:20:34.339  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-23 14:20:34.339  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 14:20:34.349  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 14:20:34.349  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 14:20:34.349  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-23 14:20:34.349  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-23 14:20:34.349  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.349  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.349  9393  9457 D BluetoothLeScanner: Stop Scan
,09-23 14:20:34.369  4956  4983 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 14:20:34.369  4956  4983 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:20:34.369  4956  4983 D BtGatt.GattService: stopScan() - queue size =1
09-23 14:20:34.369  4956  5129 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-23 14:20:34.369  4956  5129 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 14:20:34.369  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-23 14:20:34.369  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:20:34.369  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:34.369  4956  5118 D BtGatt.ScanManager: filter size is 1
09-23 14:20:34.369  4956  5129 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-23 14:20:34.369  4956  5129 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-23 14:20:34.369  4956  5118 D BtGatt.ScanManager: delete FilterIndex - 3
,09-23 14:20:34.369  4956  5355 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-23 14:20:34.369  4956  5058 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-23 14:20:34.369  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{8fbe604: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:34.369  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:34.369  4956  5118 D BtGatt.ScanManager: stopping BLe Batch
,09-23 14:20:34.379  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 14:20:34.379  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 14:20:34.379  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-23 14:20:34.379  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 14:20:34.379  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 14:20:34.379  4956  5058 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-23 14:20:34.379  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:34.379  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:20:34.379  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 14:20:34.389  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-23 14:20:34.389  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:34.389  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:34.389  3413  4397 V AlarmManager:  remove PendingIntent] PendingIntent{e6e57ed: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.389  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{213d622: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:34.389  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.389  9393  9457 D BluetoothLeAdvertiser: stop advertising
09-23 14:20:34.389  9393  9457 D BluetoothLeAdvertiser: wrapper is null
09-23 14:20:34.389  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 14:20:34.389  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 14:20:34.389  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 14:20:34.399  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 14:20:34.399  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{dfcb8b3: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.399  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 14:20:34.399  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:34.399  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 14:20:34.399  9393  9393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 14:20:34.399  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:34.399  9393  9457 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802ed6b not in the list
09-23 14:20:34.399  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 14:20:34.399  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:34.399  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:34.399  9393  9457 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 14:20:34.399  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 14:20:34.409  3413  4397 V AlarmManager:  remove PendingIntent] PendingIntent{2002d0f: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.419  9393  9393 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 14:20:34.419  9393  9393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 14:20:34.419  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{67f19c: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.419  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.419  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.429  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.429  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{28797a5: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.429  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 14:20:34.439  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:34.439  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{28e077a: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:34.439  9393  9393 D BluetoothAdapter: STATE_ON
09-23 14:20:34.439  9393  9393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 14:20:34.439  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 14:20:34.439  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 14:20:34.439  9393  9393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 14:20:34.439  3413  3852 V AlarmManager:  remove PendingIntent] PendingIntent{f1c8b2b: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.449  9393  9393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 14:20:34.449  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:34.449  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 14:20:34.449  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{d56af07: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.449  9393  9393 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 14:20:34.449  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 14:20:34.459  9393  9393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 14:20:34.459  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{da6d834: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:34.459  9393  9393 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 14:20:34.479  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:34.669  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:34.849  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:34.969  9393  9393 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 14:20:35.029  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:35.209  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:35.389  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:35.569  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:35.749  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:35.929  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:36.109  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:36.279  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:36.419  3413  6012 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-23 14:20:36.469  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:36.649  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:36.829  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:37.009  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:37.189  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:37.369  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:37.549  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:37.729  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:37.909  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:38.089  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:38.199  3149  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 14:20:38.259  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:38.439  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:38.619  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:38.799  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:38.979  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:39.159  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:39.339  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:39.409  9393  9457 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 14:20:39.409  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:20:39.429  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:20:39.439  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:20:39.439  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.449  9393  9457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:39.449  9393  9457 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 14:20:39.449  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 14:20:39.449  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 14:20:39.449  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-23 14:20:39.449  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:39.449  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 14:20:39.469  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:20:39.469  9393  9457 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 14:20:39.479  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.479  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:20:39.479  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.489  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.489  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.489  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 14:20:39.489  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 14:20:39.489  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 14:20:39.489  9393  9457 D BluetoothLeScanner: Start Scan
,09-23 14:20:39.489  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.499  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.499  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.499  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.509  4956  5355 D BtGatt.GattService: registerClient() - UUID=aa857220-2cd5-4171-9a11-70b30f2e809f
,09-23 14:20:39.519  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:39.549  4956  5058 D BtGatt.GattService: onClientRegistered() - UUID=aa857220-2cd5-4171-9a11-70b30f2e809f, clientIf=7
,09-23 14:20:39.549  9393  9404 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-23 14:20:39.559  4956  5354 D BtGatt.GattService: start scan with filters
,09-23 14:20:39.559  4956  5354 D BtGatt.GattService: getScanSettings
,09-23 14:20:39.559  4956  5354 D BtGatt.GattService: Is it foreground application = true
,09-23 14:20:39.559  4956  5354 D BtGatt.GattService: not a background application
,09-23 14:20:39.569  4956  5354 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 14:20:39.579  4956  5354 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 14:20:39.579  4956  5354 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:20:39.579  4956  5129 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 14:20:39.579  4956  5129 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,09-23 14:20:39.579  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 14:20:39.579  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 14:20:39.579  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 14:20:39.579  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 14:20:39.579  4956  5118 D BtGatt.ScanManager: handling starting scan
,09-23 14:20:39.589  4956  5118 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.589  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{9cc77ff: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.589  4956  5118 D BluetoothAdapter: STATE_ON
09-23 14:20:39.589  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 14:20:39.589  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 14:20:39.589  9393  9393 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 14:20:39.589  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 43
,09-23 14:20:39.589  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-23 14:20:39.599  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 14:20:39.599  4956  5058 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-23 14:20:39.599  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.599  4956  5118 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
,09-23 14:20:39.599  4956  5118 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 14:20:39.599  4956  5118 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,09-23 14:20:39.599  4956  5118 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-23 14:20:39.599  9393  9457 I io.jxcore.node.ConnectionHelper: start: OK
09-23 14:20:39.599  4956  5058 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,09-23 14:20:39.599  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.609  4956  5118 D BtGatt.ScanManager: Starting BLE batch scan
09-23 14:20:39.609  4956  5118 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-23 14:20:39.609  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:39.609  3413  3852 V AlarmManager:  remove PendingIntent] PendingIntent{6d8f9cc: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.609  4956  5058 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 14:20:39.609  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 13
,09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577220
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:39.609  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{646b415: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-23 14:20:39.609  4956  5058 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-23 14:20:39.609  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-23 14:20:39.609  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:39.619  9393  9457 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 14:20:39.619  9393  9457 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 14:20:39.619  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-23 14:20:39.619  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 14:20:39.619  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 14:20:39.619  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:39.619  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:39.619  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-23 14:20:39.619  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 14:20:39.619  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 14:20:39.619  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 14:20:39.619  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 14:20:39.619  4956  5129 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577220
09-23 14:20:39.619  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 14:20:39.619  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 14:20:39.619  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.619  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{437432a: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.619  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:39.619  9393  9457 D BluetoothLeScanner: Stop Scan
,09-23 14:20:39.629  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{e7a951b: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.629  4956  4971 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:20:39.629  4956  4971 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:20:39.629  4956  4971 D BtGatt.GattService: stopScan() - queue size =1
09-23 14:20:39.629  4956  5129 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-23 14:20:39.629  4956  5129 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 14:20:39.629  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:39.629  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-23 14:20:39.629  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:39.629  4956  5129 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-23 14:20:39.629  4956  5129 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-23 14:20:39.629  4956  5118 D BtGatt.ScanManager: filter size is 1
09-23 14:20:39.629  4956  5118 D BtGatt.ScanManager: delete FilterIndex - 4
09-23 14:20:39.629  4956  4983 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-23 14:20:39.629  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 14:20:39.629  4956  5058 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
,09-23 14:20:39.629  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.629  4956  5118 D BtGatt.ScanManager: stopping BLe Batch
09-23 14:20:39.629  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 14:20:39.639  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{181e6b8: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.629  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 14:20:39.629  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 14:20:39.629  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 14:20:39.639  4956  5058 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-23 14:20:39.639  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.639  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-23 14:20:39.639  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 14:20:39.639  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-23 14:20:39.639  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.639  3413  4217 V AlarmManager:  remove PendingIntent] PendingIntent{2eb7c91: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.639  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.639  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.639  9393  9457 D BluetoothLeAdvertiser: stop advertising
09-23 14:20:39.639  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{75e67f6: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.639  9393  9457 D BluetoothLeAdvertiser: wrapper is null
09-23 14:20:39.639  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 14:20:39.639  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 14:20:39.639  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 14:20:39.639  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 14:20:39.639  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{52367f7: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.639  9393  9393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 14:20:39.639  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:39.639  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 14:20:39.649  9393  9457 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 14:20:39.649  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:20:39.649  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 14:20:39.649  9393  9457 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802ed6b not in the list
09-23 14:20:39.649  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:39.649  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:39.649  9393  9457 D io.jxcore.node.ConnectivityMonitor: stop
09-23 14:20:39.649  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 14:20:39.649  3413  3852 V AlarmManager:  remove PendingIntent] PendingIntent{1c8c93: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.649  9393  9393 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 14:20:39.649  9393  9393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 14:20:39.649  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.659  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.659  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.659  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{baed4d0: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.659  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 14:20:39.659  9393  9393 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.659  3413  3852 V AlarmManager:  remove PendingIntent] PendingIntent{7282cc9: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.659  9393  9393 D BluetoothAdapter: STATE_ON
09-23 14:20:39.659  9393  9393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 14:20:39.659  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 14:20:39.659  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 14:20:39.659  9393  9393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 14:20:39.669  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{6367fce: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.669  9393  9457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 14:20:39.669  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:20:39.669  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 14:20:39.669  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{7795eef: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.669  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.669  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:39.669  9393  9457 D BluetoothLeAdvertiser: stop advertising
09-23 14:20:39.669  9393  9457 D BluetoothLeAdvertiser: wrapper is null
09-23 14:20:39.669  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 14:20:39.669  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 14:20:39.669  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.679  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:39.679  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{5746dfc: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.679  9393  9457 D BluetoothLeScanner: could not find callback wrapper
09-23 14:20:39.679  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 14:20:39.679  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:20:39.679  9393  9457 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@957e0c8 not in the list
09-23 14:20:39.679  9393  9393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 14:20:39.679  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:39.679  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 14:20:39.679  9393  9457 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 14:20:39.679  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:20:39.689  9393  9393 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 14:20:39.689  9393  9393 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 14:20:39.689  9393  9393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 14:20:39.689  3413  4397 V AlarmManager:  remove PendingIntent] PendingIntent{2c83ce7: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.689  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.689  3413  4217 V AlarmManager:  remove PendingIntent] PendingIntent{37a8094: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.689  9393  9393 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:20:39.699  9393  9457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:20:39.699  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.699  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{4ce073d: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.699  9393  9457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 14:20:39.699  9393  9457 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 14:20:39.699  9393  9457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 14:20:39.699  9393  9457 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 14:20:39.699  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 14:20:39.699  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:20:39.699  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 14:20:39.699  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:20:39.699  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{f18da39: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.709  9393  9457 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 14:20:39.709  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.709  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{128787e: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.709  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:20:39.709  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.719  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.719  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{265e1df: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.719  9393  9393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 14:20:39.719  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.719  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 14:20:39.719  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 14:20:39.719  9393  9457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 14:20:39.719  9393  9457 D BluetoothLeScanner: Start Scan
,09-23 14:20:39.719  9393  9457 D BluetoothAdapter: STATE_ON
09-23 14:20:39.719  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{1ad4e2c: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.719  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.719  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.729  9393  9457 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.729  4956  4983 D BtGatt.GattService: registerClient() - UUID=b38fbf2c-b073-4cd9-908a-e5403a469d86
,09-23 14:20:39.729  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{6a3e0f5: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.729  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{4cf9e8a: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.739  3413  4397 V AlarmManager:  remove PendingIntent] PendingIntent{770bcfb: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.739  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{9b72118: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.769  4956  5058 D BtGatt.GattService: onClientRegistered() - UUID=b38fbf2c-b073-4cd9-908a-e5403a469d86, clientIf=7
,09-23 14:20:39.769  9393  9404 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-23 14:20:39.769  4956  5355 D BtGatt.GattService: start scan with filters
,09-23 14:20:39.769  4956  5355 D BtGatt.GattService: getScanSettings
,09-23 14:20:39.769  4956  5355 D BtGatt.GattService: Is it foreground application = true
09-23 14:20:39.769  4956  5355 D BtGatt.GattService: not a background application
,09-23 14:20:39.779  4956  5355 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 14:20:39.779  4956  5355 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 14:20:39.779  4956  5355 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:20:39.779  4956  5129 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 14:20:39.779  4956  5129 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 14:20:39.779  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 14:20:39.779  9393  9457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 14:20:39.779  9393  9457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-23 14:20:39.779  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 14:20:39.779  4956  5118 D BtGatt.ScanManager: handling starting scan
,09-23 14:20:39.779  4956  5118 D BluetoothAdapter: STATE_ON
09-23 14:20:39.779  4956  5118 D BluetoothAdapter: STATE_ON
,09-23 14:20:39.789  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 14:20:39.789  9393  9457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 14:20:39.789  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{f9e9771: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.789  9393  9393 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 14:20:39.789  4956  5058 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-23 14:20:39.789  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:39.789  9393  9457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 14:20:39.789  4956  5118 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
09-23 14:20:39.789  4956  5118 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 14:20:39.789  4956  5118 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 14:20:39.789  4956  5118 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-23 14:20:39.789  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 44
09-23 14:20:39.789  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-23 14:20:39.789  4956  5058 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 14:20:39.789  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:39.789  4956  5118 D BtGatt.ScanManager: Starting BLE batch scan
09-23 14:20:39.789  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{b111956: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.789  4956  5118 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-23 14:20:39.789  9393  9457 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 14:20:39.799  4956  5058 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-23 14:20:39.799  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:39.799  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{a842dd7: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:39.799  4956  5058 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-23 14:20:39.799  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:20:39.799  3413  4217 V AlarmManager:  remove PendingIntent] PendingIntent{b8936c4: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 14
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577220
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
,09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:20:39.799  4956  5129 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577220
,09-23 14:20:39.809  3413  4620 V AlarmManager:  remove PendingIntent] PendingIntent{7b439ad: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.809  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{a1d74e2: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.809  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{f3d073: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.819  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{d44fb30: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.819  3413  4412 V AlarmManager:  remove PendingIntent] PendingIntent{207c3a9: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.819  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{8a1fd2e: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.829  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{7b100cf: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.829  3413  4619 V AlarmManager:  remove PendingIntent] PendingIntent{3b69a5c: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.829  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{6eff165: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.839  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{8d4be3a: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.839  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{f66daeb: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:39.879  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:40.059  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:40.239  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:40.289  9393  9393 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 14:20:40.289  9393  9393 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 14:20:40.289  9393  9393 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 14:20:40.429  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:40.609  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:40.789  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:40.799  3413  3814 V AlarmManager: Expired Alarm result :4
,09-23 14:20:40.809  4956  4956 D BtGatt.ScanManager: awakened up at time 252610
,09-23 14:20:40.809  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:20:40.809  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{3733ee1: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.819  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
,09-23 14:20:40.819  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: current time is 252621790588
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:20:40.819  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:40.819  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{8408406: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:40.819  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 14:20:40.819  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:40.819  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-23 14:20:40.819  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:40.819  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-23 14:20:40.819  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:40.819  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-23 14:20:40.819  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:40.819  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:20:40.819  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:40.819  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:40.819  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:40.819  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:40.819  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:40.819  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  9393  9403 D ScanRecord: parseFromBytes
,09-23 14:20:40.819  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:40.819  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:40.819  9393  9403 D ScanRecord: parseFromBytes
,09-23 14:20:40.819  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:40.839  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{e563ac7: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.839  3413  4412 V AlarmManager:  remove PendingIntent] PendingIntent{d89d8f4: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.849  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{483e81d: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.859  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{50da92: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.859  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{3f1bc63: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.869  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{ce59060: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.869  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{9fbe919: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.879  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{39e0dde: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:40.959  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:41.149  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:41.319  3413  4130 E Watchdog: !@Sync 8 [09-23 14:20:41.323]
,09-23 14:20:41.329  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:41.509  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:41.689  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:41.819  3413  3814 V AlarmManager: Expired Alarm result :4
,09-23 14:20:41.819  3413  5964 D SSRM:n  : SIOP:: AP = 300, PST = 290 (W:14), CP = 249, CUR = -89, LCD = 1
,09-23 14:20:41.829  4956  4956 D BtGatt.ScanManager: awakened up at time 253631
,09-23 14:20:41.829  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:20:41.829  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{683528c: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.839  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
09-23 14:20:41.839  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:41.839  4956  5058 D BtGatt.GattService: current time is 253643120664
09-23 14:20:41.839  4956  5058 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -77, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -78, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -95, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 14:20:41.839  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 14:20:41.839  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:41.839  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:20:41.839  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:41.839  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 14:20:41.839  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:41.839  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-23 14:20:41.839  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:41.839  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 14:20:41.839  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:41.839  4956  5058 D ScanRecord: first manudata for manu ID
,09-23 14:20:41.839  3413  4619 V AlarmManager:  remove PendingIntent] PendingIntent{d58fdd5: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:41.839  9393  9404 D ScanRecord: parseFromBytes
,09-23 14:20:41.839  9393  9404 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  9393  9404 D ScanRecord: parseFromBytes
09-23 14:20:41.839  9393  9404 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  9393  9404 D ScanRecord: parseFromBytes
09-23 14:20:41.839  9393  9404 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  9393  9404 D ScanRecord: parseFromBytes
09-23 14:20:41.839  9393  9404 D ScanRecord: first manudata for manu ID
09-23 14:20:41.839  9393  9404 D ScanRecord: parseFromBytes
09-23 14:20:41.839  9393  9404 D ScanRecord: first manudata for manu ID
,09-23 14:20:41.849  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{3f929ea: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.859  3413  4412 V AlarmManager:  remove PendingIntent] PendingIntent{d854db: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.859  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:41.869  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{2590b78: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.869  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{838a251: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.879  3413  4164 V AlarmManager:  remove PendingIntent] PendingIntent{d37fab6: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.879  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{dfd63b7: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.889  3413  4860 V AlarmManager:  remove PendingIntent] PendingIntent{fcf6724: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:41.889  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{694128d: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.049  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:42.219  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:42.399  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:42.579  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:42.759  4365  4454 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-23 14:20:42.759  4365  4454 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-23 14:20:42.769  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:42.849  3413  3814 V AlarmManager: Expired Alarm result :4
,09-23 14:20:42.849  4956  4956 D BtGatt.ScanManager: awakened up at time 254654
,09-23 14:20:42.849  4956  5118 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-23 14:20:42.849  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{fa8453: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.859  4956  5058 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=7
,09-23 14:20:42.859  4956  5058 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: current time is 254664047048
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: Batch record : [50, -35, 86, -77, -92, -11, 1, 0, -99, 19, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -81, 52, 14, 3, 1, -37, 18, -106, -69, -23, 92, 28, 6, 8, 116, 105, 110, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -77, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -89, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -95, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:20:42.859  3413  4840 V AlarmManager:  remove PendingIntent] PendingIntent{a2dd190: PendingIntentRecord{3ffd12 com.android.bluetooth broadcastIntent}}
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -81, 52, 14, 3, 1, -37, 18, -106, -69, -23, 92, 6, 8, 116, 105, 110, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-23 14:20:42.859  4956  5058 D ScanRecord: parseFromBytes
,09-23 14:20:42.859  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 14:20:42.859  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:42.859  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:20:42.859  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:42.859  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-23 14:20:42.859  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:42.859  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 14:20:42.859  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:42.859  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:42.859  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 14:20:42.869  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:42.869  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:42.869  4956  5058 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 14:20:42.869  4956  5058 D ScanRecord: parseFromBytes
09-23 14:20:42.869  4956  5058 D ScanRecord: first manudata for manu ID
09-23 14:20:42.869  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:42.869  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:42.869  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:42.869  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:42.869  3413  4412 V AlarmManager:  remove PendingIntent] PendingIntent{bc4a89: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:42.869  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:42.869  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:42.869  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:42.869  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:42.869  9393  9403 D ScanRecord: parseFromBytes
,09-23 14:20:42.869  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:42.869  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:42.869  9393  9403 D ScanRecord: first manudata for manu ID
09-23 14:20:42.869  9393  9403 D ScanRecord: parseFromBytes
09-23 14:20:42.869  9393  9403 D ScanRecord: first manudata for manu ID
,09-23 14:20:42.869  4365  4454 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 116ms lastUpdatedAfter : 155906ms
,09-23 14:20:42.879  3413  4290 V AlarmManager:  remove PendingIntent] PendingIntent{dd7aa8e: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.879  3413  4355 V AlarmManager:  remove PendingIntent] PendingIntent{29f12af: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.889  3413  3437 V AlarmManager:  remove PendingIntent] PendingIntent{7c676bc: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.889  3413  3438 V AlarmManager:  remove PendingIntent] PendingIntent{9160645: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.889  3413  4397 V AlarmManager:  remove PendingIntent] PendingIntent{2a7e19a: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.899  3413  4399 V AlarmManager:  remove PendingIntent] PendingIntent{f542acb: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.899  3413  4052 V AlarmManager:  remove PendingIntent] PendingIntent{fe242a8: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
09-23 14:20:42.909  3413  4619 V AlarmManager:  remove PendingIntent] PendingIntent{995c1c1: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.909  3413  3852 V AlarmManager:  remove PendingIntent] PendingIntent{2127d66: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.919  3413  3968 V AlarmManager:  remove PendingIntent] PendingIntent{6f8a8a7: PendingIntentRecord{eacc7e8 com.android.bluetooth broadcastIntent}}
,09-23 14:20:42.939  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:43.119  3413  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:20:43.189  3149  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found

```
