#### Test 86171191c184704_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-21 17:20:32.793  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:32.973  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:33.153  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:33.333  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:33.393  9331  9331 I FIPS_bssl: FIPS approved mode (1) | 9331 | app_process
09-21 17:20:33.403  9331  9331 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 17:20:33.403  9331  9331 D AndroidRuntime: CheckJNI is OFF
09-21 17:20:33.403  9331  9331 D AndroidRuntime: readGMSProperty: start
09-21 17:20:33.403  9331  9331 D AndroidRuntime: readGMSProperty: already setted!!
09-21 17:20:33.403  9331  9331 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-21 17:20:33.403  9331  9331 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-21 17:20:33.403  9331  9331 D AndroidRuntime: readGMSProperty: end
09-21 17:20:33.403  9331  9331 D AndroidRuntime: addProductProperty: start
09-21 17:20:33.423  9331  9331 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 17:20:33.443  9331  9331 I Radio-JNI: register_android_hardware_Radio DONE
09-21 17:20:33.443  9331  9331 E AffinityControl: AffinityControl: registerfunction enter
09-21 17:20:33.453  9331  9331 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-21 17:20:33.483  3424  4403 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-21 17:20:33.483  3424  4403 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-21 17:20:33.513  3424  4403 D ResourcesManager: For user 0 new overlays fetched Null
09-21 17:20:33.513  3424  4403 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:20:33.513  3424  4403 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-21 17:20:33.513  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:33.513  3424  4403 D ActivityManager: mDVFSHelper.acquire()
09-21 17:20:33.523  3424  4403 V WindowManager: addAppToken: AppWindowToken{d01ba150 token=Token{742bb13 ActivityRecord{640e602 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-21 17:20:33.523  3424  3546 I InjectionManager: Inside getClassLibPath caller 
09-21 17:20:33.533  3424  3546 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-21 17:20:33.533  3424  3546 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4424a68 V.E...... R.....ID 0,0-0,0}
09-21 17:20:33.533  3424  3546 W WindowManager: Failed looking up window
09-21 17:20:33.533  3424  3546 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@7558e81 does not exist
09-21 17:20:33.533  3424  3546 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 17:20:33.533  3424  3546 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 17:20:33.543  3424  3546 D ISSUE_DEBUG: InputChannelName : 99f2b26 Starting com.test.thalitest
09-21 17:20:33.543  9340  9340 E Zygote  : v2
09-21 17:20:33.543  9340  9340 I libpersona: KNOX_SDCARD checking this for 10171
09-21 17:20:33.543  9340  9340 I libpersona: KNOX_SDCARD not a persona
09-21 17:20:33.543  9340  9340 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-21 17:20:33.543  9340  9340 E Zygote  : accessInfo : 0
09-21 17:20:33.543  3424  4403 I ActivityManager: Start proc 9340:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-21 17:20:33.543  3002  3002 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-21 17:20:33.543  9340  9340 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-21 17:20:33.573  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:20:33.583  9340  9340 D TimaKeyStoreProvider: TimaSignature is unavailable
09-21 17:20:33.583  9340  9340 D ActivityThread: Added TimaKeyStore provider
09-21 17:20:33.583  3424  4266 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3424
09-21 17:20:33.583  3424  4266 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:20:33.583  3424  4266 D PowerManagerService: mDisplayReady: false
09-21 17:20:33.583  3424  4266 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:20:33.583  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:20:33.583  3424  4403 D InputDispatcher: Focused application set to: xxxx
09-21 17:20:33.583  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:20:33.583  3002  3002 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb58c3c00
09-21 17:20:33.583  3424  4266 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 17:20:33.583  3002  3002 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-21 17:20:33.583  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:33.583  9331  9331 D AndroidRuntime: Shutting down VM
09-21 17:20:33.583  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:33.583  3424  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-21 17:20:33.583  3424  3856 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-21 17:20:33.593  3002  3048 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=251201408088)
09-21 17:20:33.593  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:20:33.593  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:20:33.593  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:20:33.593  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:33.593  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 17:20:33.593  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:33.593  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:20:33.593  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:20:33.593  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:33.593  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:33.593  3424  3551 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:20:33.593  3424  3551 D PowerManagerService: mDisplayReady: true
09-21 17:20:33.593  3424  3551 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 17:20:33.603  3424  4289 D ActivityManager:  Launching com.test.thalitest, updated priority
09-21 17:20:33.613  3424  3980 V WindowStateAnimator: Finishing drawing window Window{d924a8e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-21 17:20:33.613  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:20:33.613  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:20:33.613  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:20:33.613  6039  6039 V ActivityThread: updateVisibility : ActivityRecord{7c2f27c token=android.os.BinderProxy@6126139 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-21 17:20:33.613  3002  4328 D libEGL  : eglTerminate EGLDisplay = 0x7faee9de78
09-21 17:20:33.613  3002  4328 D libEGL  : eglTerminate EGLDisplay = 0x7faee9de78
09-21 17:20:33.613  3424  3424 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-21 17:20:33.623  3424  3510 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-21 17:20:33.623  3002  3011 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-21 17:20:33.623  3002  3013 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-21 17:20:33.633  3002  3002 D libEGL  : eglTerminate EGLDisplay = 0x7fc6fdf968
09-21 17:20:33.643  3002  3013 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-21 17:20:33.643  3002  3013 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-21 17:20:33.643  4282  4282 V ActivityThread: updateVisibility : ActivityRecord{2bb4df0 token=android.os.BinderProxy@65bc418 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-21 17:20:33.643  4282  4282 D Launcher: onTrimMemory. Level: 20
09-21 17:20:33.653  3002  4420 D libEGL  : eglTerminate EGLDisplay = 0x7fae5fee78
09-21 17:20:33.653  3002  3013 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-21 17:20:33.653  3002  3011 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-21 17:20:33.653  3002  3002 D libEGL  : eglTerminate EGLDisplay = 0x7fc6fdf968
09-21 17:20:33.653  3002  3002 D libEGL  : eglTerminate EGLDisplay = 0x7fc6fdf968
09-21 17:20:33.693  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:33.733  3424  3424 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3424 (0x0)
09-21 17:20:33.733  3424  3424 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:20:33.733  3424  3424 D PowerManagerService: mDisplayReady: false
09-21 17:20:33.733  3424  3424 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:20:33.733  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:20:33.733  3424  3424 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 17:20:33.733  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:20:33.733  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:33.733  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:33.733  3424  3563 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-21 17:20:33.733  3002  3002 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb58c3c00
09-21 17:20:33.733  3002  3002 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-21 17:20:33.743  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:20:33.743  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:20:33.743  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:33.743  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:20:33.743  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:33.743  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 17:20:33.743  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:20:33.743  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:20:33.743  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:33.743  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:33.743  3424  3551 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:20:33.743  3424  3551 D PowerManagerService: mDisplayReady: true
09-21 17:20:33.743  3424  3551 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 17:20:33.783  3424  5934 D SSRM:n  : SIOP:: AP = 280, PST = 279 (W:10), CP = 238, LCD = 1
09-21 17:20:33.873  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:33.953  3424  4289 I WindowManager: Screenshot max retries 4 of Token{742bb13 ActivityRecord{640e602 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{99f2b26 u0 d0 Starting com.test.thalitest} drawState=1
09-21 17:20:33.953  3424  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:20:33.953  3424  5934 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:20:33.953  3424  3424 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:20:33.963  3424  5934 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:20:33.953  3424  3546 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-21 17:20:33.963  3424  3856 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-21 17:20:33.963  3424  3424 I KnoxTimeoutHandler: SD activityfalse
09-21 17:20:33.983  3424  5934 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 17:20:33.983  9340  9340 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 17:20:33.993  3424  5934 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:20:33.993  3424  4324 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-21 17:20:33.993  9340  9340 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-21 17:20:33.993  3424  3546 V WindowStateAnimator: Finishing drawing window Window{99f2b26 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-21 17:20:33.993  3424  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:20:33.993  3424  3424 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:20:33.993  3424  3546 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{455c9ea u0 com.samsung.android.MtpApplication/.USBConnection t3} time:251608
09-21 17:20:33.993  3424  3546 D ActivityManager: mDVFSHelper.release()
09-21 17:20:33.993  3424  3424 I KnoxTimeoutHandler: SD activityfalse
09-21 17:20:34.003  3002  3002 D libEGL  : eglInitialize EGLDisplay = 0x7fc6fdf848
09-21 17:20:34.003  3424  5934 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 17:20:34.003  3424  5934 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:20:34.003  3424  5934 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:20:34.013  9340  9340 D ResourcesManager: For user 0 new overlays fetched Null
09-21 17:20:34.013  9340  9340 I InjectionManager: Inside getClassLibPath caller 
09-21 17:20:34.033  9340  9340 D InjectionManager: InjectionManager
09-21 17:20:34.033  9340  9340 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-21 17:20:34.033  9340  9340 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-21 17:20:34.033  9340  9340 I InjectionManager: featureStore :{}
09-21 17:20:34.043  9340  9340 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 17:20:34.043  9340  9340 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-21 17:20:34.043  9340  9340 D RelationGraph: garbageCollect()
09-21 17:20:34.053  9340  9340 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 17:20:34.053  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:34.083  9340  9340 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-21 17:20:34.113  9340  9340 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-21 17:20:34.123  9340  9340 D ResourcesManager: For user 0 new overlays fetched Null
09-21 17:20:34.123  9340  9340 I InjectionManager: Inside getClassLibPath caller 
09-21 17:20:34.123  9340  9340 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-21 17:20:34.183  9340  9340 I cr_LibraryLoader: Time to load native libraries: 32 ms (timestamps 1756-1788)
09-21 17:20:34.183  9340  9340 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 17:20:34.213  3424  3882 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-21 17:20:34.233  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:34.253  9340  9355 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-21 17:20:34.273  9340  9340 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2df907}
09-21 17:20:34.273  9340  9340 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 17:20:34.293  9340  9340 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-21 17:20:34.313  3424  3882 I MdnieScenarioControlService: mGameModeLauncher : false
09-21 17:20:34.313  3424  3882 I MdnieScenarioControlService: setUIMode
09-21 17:20:34.343  9340  9340 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-21 17:20:34.413  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:34.453  3424  3510 W ActivityManager: Activity pause timeout for ActivityRecord{640e602 u0 com.test.thalitest/.MainActivity t4}
09-21 17:20:34.523  9340  9340 D libEGL  : eglInitialize EGLDisplay = 0xffd6b46c
09-21 17:20:34.593  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:34.643  3424  3990 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-21 17:20:34.643  3424  3990 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-21 17:20:34.743  9340  9340 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-21 17:20:34.763  9340  9340 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 17:20:34.763  9340  9340 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-21 17:20:34.773  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:34.793  9340  9340 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-21 17:20:34.853  9340  9340 D Activity: performCreate Call Injection manager
,09-21 17:20:34.863  9340  9340 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-21 17:20:34.863  9340  9340 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 17:20:34.873  9340  9340 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cbc2d32 I.E...... R.....ID 0,0-0,0}
,09-21 17:20:34.883  9340  9392 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 17:20:34.883  3424  4807 W WindowManager: Failed looking up window
09-21 17:20:34.883  3424  4807 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@b986161 does not exist
09-21 17:20:34.883  3424  4807 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 17:20:34.883  3424  4807 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 17:20:34.883  3424  4807 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 17:20:34.883  3424  4807 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-21 17:20:34.883  3424  4807 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-21 17:20:34.883  3424  4807 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-21 17:20:34.893  3424  3797 D ISSUE_DEBUG: InputChannelName : f933486 com.test.thalitest/com.test.thalitest.MainActivity
,09-21 17:20:34.893  3424  3990 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-21 17:20:34.893  3424  3990 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 17:20:34.893  3424  3424 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 17:20:34.893  3424  3424 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-21 17:20:34.903  9340  9340 V ActivityThread: updateVisibility : ActivityRecord{ddeb400 token=android.os.BinderProxy@dafb1a5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-21 17:20:34.913  9340  9355 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-21 17:20:34.933  9340  9340 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9340
,09-21 17:20:34.943  3424  3990 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9340 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 17:20:34.943  3424  3867 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-21 17:20:34.943  3424  3867 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-21 17:20:34.943  3424  3867 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-21 17:20:34.953  3424  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 17:20:34.953  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:34.953  3424  5935 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-21 17:20:34.953  3424  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-21 17:20:34.963  9340  9340 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 17:20:34.963  3424  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 17:20:34.973  3424  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-21 17:20:34.973  3424  3867 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 17:20:34.983  3002  3002 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-21 17:20:34.993  9340  9392 D libEGL  : eglInitialize EGLDisplay = 0xdc37f7c4
09-21 17:20:34.993  9340  9392 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 17:20:35.003  9340  9392 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-21 17:20:35.003  3424  3797 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3424
,09-21 17:20:35.003  3424  3797 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:20:35.003  3424  3797 D PowerManagerService: mDisplayReady: false
09-21 17:20:35.003  3424  3797 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:20:35.003  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:20:35.003  3424  3797 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-21 17:20:35.003  3002  3002 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb58c3c00
09-21 17:20:35.003  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:20:35.003  3002  3002 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-21 17:20:35.003  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-21 17:20:35.003  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-21 17:20:35.003  3424  3563 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-21 17:20:35.003  3424  3546 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-21 17:20:35.013  3424  3546 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-21 17:20:35.023  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-21 17:20:35.023  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:20:35.023  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:35.023  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:20:35.023  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:35.023  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 17:20:35.023  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:20:35.023  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-21 17:20:35.023  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:35.023  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:35.023  3424  3551 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:20:35.023  3424  3551 D PowerManagerService: mDisplayReady: true
09-21 17:20:35.023  3424  3551 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-21 17:20:35.033  9340  9340 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-21 17:20:35.043  9340  9396 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 17:20:35.043  9340  9396 D libEGL  : eglInitialize EGLDisplay = 0xdb6bf3f4
,09-21 17:20:35.053  3424  4295 V WindowStateAnimator: Finishing drawing window Window{f933486 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-21 17:20:35.053  9340  9340 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-21 17:20:35.063  3424  3443 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3424
,09-21 17:20:35.063  3424  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 17:20:35.063  3424  3424 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 17:20:35.063  3424  3546 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s114ms (total +1s543ms)
09-21 17:20:35.063  3424  3546 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{640e602 u0 com.test.thalitest/.MainActivity t4} time:252676
09-21 17:20:35.063  3424  3546 D ViewRootImpl: #3 mView = null
,09-21 17:20:35.063  3002  4420 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-21 17:20:35.063  3424  3424 I KnoxTimeoutHandler: SD activityfalse
09-21 17:20:35.063  3002  3071 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-21 17:20:35.073  9340  9396 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-21 17:20:35.073  3424  4289 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3424
,09-21 17:20:35.073  3002  3002 D libEGL  : eglTerminate EGLDisplay = 0x7fc6fdf968
09-21 17:20:35.073  3424  4281 V WindowStateAnimator: Finishing drawing window Window{f933486 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-21 17:20:35.073  9340  9340 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@dafb1a5 time:252688
,09-21 17:20:35.133  9340  9340 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9340
,09-21 17:20:35.133  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:35.223  3424  3424 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3424 (0x0)
09-21 17:20:35.223  3424  3424 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:20:35.223  3424  3424 D PowerManagerService: mDisplayReady: false
09-21 17:20:35.223  3424  3424 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:20:35.223  3424  3424 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 17:20:35.223  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:20:35.223  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:20:35.223  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:35.223  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-21 17:20:35.223  3424  3563 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-21 17:20:35.223  3002  3002 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb58c3c00
09-21 17:20:35.223  3424  3546 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-21 17:20:35.223  3002  3002 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-21 17:20:35.223  3424  3546 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-21 17:20:35.233  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-21 17:20:35.233  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:20:35.233  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:20:35.233  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-21 17:20:35.233  3424  3551 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 17:20:35.233  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:35.233  3424  3551 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:20:35.233  3424  3551 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,09-21 17:20:35.233  3424  3551 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:20:35.233  3424  3551 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:20:35.233  3424  3551 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:20:35.233  3424  3551 D PowerManagerService: mDisplayReady: true
09-21 17:20:35.233  3424  3551 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-21 17:20:35.313  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:35.333  3150  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-21 17:20:35.363  9340  9340 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 17:20:35.453  4023  4023 D Recents : onTaskStackChanged
,09-21 17:20:35.463  4023  4023 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-21 17:20:35.473  4023  4023 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 17:20:35.473  9340  9404 D jxcore_app_log: JniHelper::setJavaVM(0xf4af4000), pthread_self() = -635963088
,09-21 17:20:35.473  9340  9404 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 17:20:35.473  9340  9404 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 17:20:35.473  9340  9404 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 17:20:35.473  9340  9404 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 17:20:35.473  9340  9404 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87646e2 added. We now have 1 listener(s)
,09-21 17:20:35.483  9340  9404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-21 17:20:35.483  9340  9404 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 17:20:35.483  9340  9404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 17:20:35.483  9340  9404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-21 17:20:35.483  9340  9404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0c3da9 added. We now have 1 listener(s)
09-21 17:20:35.483  9340  9404 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 17:20:35.483  9340  9404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 17:20:35.483  9340  9404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 17:20:35.483  9340  9404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 17:20:35.483  9340  9404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 17:20:35.483  9340  9404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-21 17:20:35.493  9340  9404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:20:35.493  9340  9404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-21 17:20:35.493  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:35.503  9340  9404 D BluetoothAdapter: STATE_ON
,09-21 17:20:35.503  9340  9404 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:20:35.503  9340  9404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 17:20:35.503  9340  9404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 17:20:35.503  9340  9404 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 17:20:35.503  9340  9404 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 17:20:35.513  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:35.513  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:35.543  9340  9340 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 17:20:35.623  3424  4148 E Watchdog: !@Sync 8 [09-21 17:20:35.631]
,09-21 17:20:35.673  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:35.853  9340  9405 W jxcore-log: Initializing JXcore engine
09-21 17:20:35.853  9340  9405 W jxcore-log: JXcore engine is ready
,09-21 17:20:35.853  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:35.873  4954  4954 E audit   : type=1400 msg=audit(1474471235.873:262): avc:  denied  { ioctl } for  pid=9405 comm="Thread-172" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1057 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 17:20:35.873  4954  4954 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 17:20:35.873  4954  4954 E audit   : type=1300 msg=audit(1474471235.873:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da07a3c8 items=0 ppid=3175 pid=9405 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-172" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 17:20:35.873  4954  4954 E audit   : type=1327 msg=audit(1474471235.873:262): proctitle="com.test.thalitest"
09-21 17:20:35.873  4954  4954 E audit   : type=1320 msg=audit(1474471235.873:262): 
09-21 17:20:35.873  4954  4954 E audit   : type=1400 msg=audit(1474471235.873:263): avc:  denied  { ioctl } for  pid=9405 comm="Thread-172" path="socket:[10215]" dev="sockfs" ino=10215 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 17:20:35.873  4954  4954 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 17:20:35.873  4954  4954 E audit   : type=1300 msg=audit(1474471235.873:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da07a3c8 items=0 ppid=3175 pid=9405 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-172" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 17:20:35.873  4954  4954 E audit   : type=1327 msg=audit(1474471235.873:263): proctitle="com.test.thalitest"
09-21 17:20:35.873  4954  4954 E audit   : type=1320 msg=audit(1474471235.873:263): 
,09-21 17:20:35.873  9340  9405 W jxcore-log: Starting JXcore engine
,09-21 17:20:35.913  9340  9405 W jxcore-log: Platform android
09-21 17:20:35.913  9340  9405 W jxcore-log: 
09-21 17:20:35.913  9340  9405 W jxcore-log: Process ARCH arm
09-21 17:20:35.913  9340  9405 W jxcore-log: 
,09-21 17:20:35.983  9340  9405 I jxcore-log: JXcore Cordova bridge is ready!
09-21 17:20:35.983  9340  9405 I jxcore-log: 
09-21 17:20:35.983  9340  9405 W jxcore-log: JXcore engine is started
,09-21 17:20:35.993  9340  9404 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 17:20:35.993  9340  9340 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 17:20:36.033  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:36.213  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:36.393  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:36.533  3424  3907 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-21 17:20:36.573  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:36.753  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:36.933  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:36.973  3424  5934 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-21 17:20:36.973  4389  4445 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-21 17:20:36.973  4389  4445 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-21 17:20:37.033  4389  4445 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 61ms lastUpdatedAfter : 156202ms
,09-21 17:20:37.113  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:37.293  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:37.473  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:37.653  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:37.833  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:38.013  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:38.193  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:38.373  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:38.553  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:38.733  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:38.913  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:39.093  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:39.273  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:39.453  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:39.633  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:39.813  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:39.993  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:40.013  3424  5934 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-21 17:20:40.173  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:40.353  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:40.533  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:40.713  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:40.893  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:41.073  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:41.253  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:41.433  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:41.613  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:41.793  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:41.923  9340  9405 I jxcore-log: 2016-09-21 15:20:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-21 17:20:41.923  9340  9405 I jxcore-log: 
,09-21 17:20:41.923  9340  9405 I jxcore-log: 2016-09-21 15:20:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-21 17:20:41.923  9340  9405 I jxcore-log: 
,09-21 17:20:41.933  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:20:41.943  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:20:41.943  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:41.943  9340  9405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 17:20:41.943  9340  9405 I jxcore-log: 2016-09-21 15:20:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-21 17:20:41.943  9340  9405 I jxcore-log: 
,09-21 17:20:41.943  9340  9405 I jxcore-log: 2016-09-21 15:20:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-21 17:20:41.943  9340  9405 I jxcore-log: 
,09-21 17:20:41.973  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:42.093  9340  9405 I jxcore-log: Running unit tests
09-21 17:20:42.093  9340  9405 I jxcore-log: 
,09-21 17:20:42.093  9340  9405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 17:20:42.093  9340  9405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa7fa70 added. We now have 2 listener(s)
09-21 17:20:42.093  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 17:20:42.093  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 17:20:42.093  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 17:20:42.093  9340  9405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 17:20:42.093  9340  9405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a73f1e9 added. We now have 2 listener(s)
,09-21 17:20:42.093  9340  9405 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 17:20:42.093  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 17:20:42.103  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:20:42.113  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:20:42.113  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:20:42.113  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.123  9340  9405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:42.123  9340  9405 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:20:42.123  9340  9405 D executeNativeTests: Running unit tests
,09-21 17:20:42.123  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:42.133  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:42.153  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:42.183  9340  9405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 17:20:42.183  9340  9405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f59c3ff added. We now have 3 listener(s)
,09-21 17:20:42.183  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 17:20:42.183  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 17:20:42.183  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 17:20:42.183  9340  9405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 17:20:42.183  9340  9405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc added. We now have 3 listener(s)
09-21 17:20:42.183  9340  9405 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 17:20:42.183  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 17:20:42.193  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:20:42.203  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:20:42.203  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:20:42.203  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.213  9340  9405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:42.213  9340  9405 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 17:20:42.213  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 17:20:42.213  9340  9405 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-21 17:20:42.213  9340  9405 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 17:20:42.213  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 17:20:42.213  9340  9405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 17:20:42.213  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 17:20:42.213  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 17:20:42.213  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:20:42.213  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.213  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 17:20:42.213  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f59c3ff removed from the list
09-21 17:20:42.213  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:42.213  9340  9405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc removed from the list
09-21 17:20:42.213  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:20:42.213  9340  9405 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 17:20:42.213  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.213  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.213  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:42.223  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
09-21 17:20:42.223  9340  9405 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-21 17:20:42.223  9340  9405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 17:20:42.223  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 17:20:42.223  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:20:42.223  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.223  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.223  9340  9405 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f59c3ff not in the list
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:42.223  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
09-21 17:20:42.223  9340  9405 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:20:42.223  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.223  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.223  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.223  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 17:20:42.223  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:42.223  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 17:20:42.233  9340  9405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 17:20:42.233  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 17:20:42.233  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 17:20:42.233  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:20:42.233  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.233  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.233  9340  9405 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f59c3ff not in the list
09-21 17:20:42.233  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:42.233  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
09-21 17:20:42.233  9340  9405 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:20:42.233  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.233  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.233  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:42.233  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:20:42.233  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 17:20:42.233  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 17:20:42.233  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:42.233  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
09-21 17:20:42.233  9340  9405 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 17:20:42.233  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:42.243  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:20:42.243  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 17:20:42.243  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.243  9340  9405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:42.243  9340  9405 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:20:42.243  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:20:42.243  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 17:20:42.243  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 17:20:42.243  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:42.243  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 17:20:42.253  9340  9405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 17:20:42.253  9340  9405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 17:20:42.253  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:20:42.253  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.263  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.263  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.263  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:20:42.263  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 17:20:42.273  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.273  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.273  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 17:20:42.273  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 17:20:42.273  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.273  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.283  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-21 17:20:42.283  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.283  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.283  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-21 17:20:42.283  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 17:20:42.283  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 17:20:42.283  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 17:20:42.283  9340  9405 D BluetoothLeScanner: Start Scan
09-21 17:20:42.293  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.293  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.293  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:42.293  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.303  4948  5119 D BtGatt.GattService: registerClient() - UUID=5bd53453-afec-4bbd-aac5-75e8a9a631e4
,09-21 17:20:42.333  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:42.353  4948  5060 D BtGatt.GattService: onClientRegistered() - UUID=5bd53453-afec-4bbd-aac5-75e8a9a631e4, clientIf=7
,09-21 17:20:42.353  9340  9351 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-21 17:20:42.353  4948  4966 D BtGatt.GattService: start scan with filters
09-21 17:20:42.353  4948  4966 D BtGatt.GattService: getScanSettings
,09-21 17:20:42.363  4948  4966 D BtGatt.GattService: Is it foreground application = true
,09-21 17:20:42.363  4948  4966 D BtGatt.GattService: not a background application
,09-21 17:20:42.373  4948  4966 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-21 17:20:42.383  4948  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:20:42.383  4948  4966 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:20:42.383  4948  5111 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-21 17:20:42.383  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 17:20:42.383  4948  5111 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
09-21 17:20:42.383  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-21 17:20:42.383  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 17:20:42.383  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 17:20:42.383  4948  5103 D BtGatt.ScanManager: handling starting scan
09-21 17:20:42.383  4948  5103 D BtGatt.ScanManager: isFilteringSupported
,09-21 17:20:42.383  4948  5103 D BluetoothAdapter: enableStandAloneBleMode=
,09-21 17:20:42.383  4948  5103 D BluetoothAdapter: STATE_ON
09-21 17:20:42.383  4948  5103 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.393  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 17:20:42.393  4948  5103 D BluetoothAdapter: STATE_ON
09-21 17:20:42.393  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 17:20:42.393  9340  9340 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:20:42.393  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 66
09-21 17:20:42.393  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-21 17:20:42.393  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 17:20:42.393  4948  5103 D BluetoothAdapter: STATE_ON
,09-21 17:20:42.393  4948  5103 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a435346
,09-21 17:20:42.403  9340  9405 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 22
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574520
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:42.403  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{bf4292f: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:42.403  4948  5111 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574520
,09-21 17:20:42.403  4948  5060 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-21 17:20:42.403  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:42.403  4948  5103 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-21 17:20:42.403  4948  5103 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-21 17:20:42.403  4948  5103 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-21 17:20:42.403  4948  5103 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-21 17:20:42.413  4948  5060 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,09-21 17:20:42.413  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:42.413  4948  5103 D BtGatt.ScanManager: Starting BLE batch scan
09-21 17:20:42.413  4948  5103 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-21 17:20:42.413  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{4dc0b3c: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.413  4948  5060 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-21 17:20:42.413  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:20:42.423  4948  5060 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-21 17:20:42.423  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:20:42.423  3424  3980 V AlarmManager:  remove PendingIntent] PendingIntent{98540c5: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.423  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{4d6ca1a: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.423  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{dfc9f28: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.433  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{dfe2441: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.433  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{f876de6: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.443  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{60a0f27: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.443  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{21085d4: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.453  3424  3443 V AlarmManager:  remove PendingIntent] PendingIntent{fc7c37d: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.453  3424  4713 V AlarmManager:  remove PendingIntent] PendingIntent{54c8272: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.463  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{77e76c3: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.473  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{6da2b40: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.473  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{7921a79: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:42.513  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:42.693  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:42.873  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:42.893  9340  9340 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-21 17:20:42.893  9340  9340 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:20:42.893  9340  9340 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-21 17:20:43.053  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:43.233  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:43.413  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:43.423  3424  3817 V AlarmManager: Expired Alarm result :4
,09-21 17:20:43.423  4948  4948 D BtGatt.ScanManager: awakened up at time 261039
,09-21 17:20:43.443  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:20:43.443  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{547bc1f: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.453  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
09-21 17:20:43.453  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:43.453  4948  5060 D BtGatt.GattService: current time is 261061529620
,09-21 17:20:43.453  4948  5060 D BtGatt.GattService: Batch record : [-93, 108, -84, 117, 25, 82, 1, -128, -96, 3, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -56, 58, -112, 69, -31, 21, -27, 69, 74, 40, -83, -51, -30, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -90, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-21 17:20:43.453  3424  4713 V AlarmManager:  remove PendingIntent] PendingIntent{9d6bb6c: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.453  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -56, 58, -112, 69, -31, 21, -27, 69, 74, 40, -83, -51, -30]
,09-21 17:20:43.453  4948  5060 D ScanRecord: parseFromBytes
,09-21 17:20:43.463  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:43.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 17:20:43.463  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{f10e535: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:43.463  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:43.463  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:43.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-21 17:20:43.463  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:43.463  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:43.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-21 17:20:43.463  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:43.463  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:43.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-21 17:20:43.463  4948  5060 D ScanRecord: parseFromBytes
,09-21 17:20:43.463  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:43.473  9340  9350 D ScanRecord: parseFromBytes
,09-21 17:20:43.473  9340  9350 D ScanRecord: first manudata for manu ID
,09-21 17:20:43.473  9340  9350 D ScanRecord: parseFromBytes
,09-21 17:20:43.473  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:43.473  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{c05edca: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:43.473  9340  9350 D ScanRecord: parseFromBytes
,09-21 17:20:43.473  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:43.473  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:43.473  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:43.473  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:43.473  9340  9350 D ScanRecord: first manudata for manu ID
,09-21 17:20:43.483  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{135fb3b: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.483  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{12a2258: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.493  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{d779fb1: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.503  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{27d1c96: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.503  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{fff1017: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.513  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{f4b0c04: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:43.573  3424  3573 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-21 17:20:43.593  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:43.593  3424  3573 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-21 17:20:43.773  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:43.803  3424  5934 D SSRM:n  : SIOP:: AP = 340, PST = 284 (W:6), CP = 247, LCD = 1
,09-21 17:20:43.953  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:44.133  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:44.313  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:44.453  3424  3817 V AlarmManager: Expired Alarm result :4
09-21 17:20:44.463  4948  4948 D BtGatt.ScanManager: awakened up at time 262071
09-21 17:20:44.463  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-21 17:20:44.463  3424  3797 V AlarmManager:  remove PendingIntent] PendingIntent{1666c22: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:44.473  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
09-21 17:20:44.473  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:44.473  4948  5060 D BtGatt.GattService: current time is 262087350734
09-21 17:20:44.473  4948  5060 D BtGatt.GattService: Batch record : [-93, 108, -84, 117, 25, 82, 1, -128, -95, 13, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -56, 58, -112, 69, -31, 21, -27, 69, 74, 40, -83, -51, -30, 0, -93, 108, -84, 117, 25, 82, 1, -128, -96, 10, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -55, 58, -41, 92, 6, -55, -9, 69, 49, -39, -89, -69, -45, 0]
09-21 17:20:44.473  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{1da96b3: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
09-21 17:20:44.473  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -56, 58, -112, 69, -31, 21, -27, 69, 74, 40, -83, -51, -30]
09-21 17:20:44.473  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:44.473  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:44.473  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -55, 58, -41, 92, 6, -55, -9, 69, 49, -39, -89, -69, -45]
09-21 17:20:44.473  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:44.473  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:44.483  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:44.483  9340  9351 D ScanRecord: first manudata for manu ID
09-21 17:20:44.483  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:44.483  9340  9351 D ScanRecord: first manudata for manu ID
09-21 17:20:44.493  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{56ee470: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:44.493  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:20:44.493  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{87193e9: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:44.503  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{2a3286e: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:44.503  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{8ddeb0f: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:44.513  3424  3443 V AlarmManager:  remove PendingIntent] PendingIntent{b5d79c: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:44.673  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:44.853  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:45.033  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:45.213  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:45.393  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:45.483  3424  3817 V AlarmManager: Expired Alarm result :4
,09-21 17:20:45.483  4948  4948 D BtGatt.ScanManager: awakened up at time 263096
,09-21 17:20:45.483  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:20:45.493  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-21 17:20:45.493  3424  4233 V AlarmManager:  remove PendingIntent] PendingIntent{add5d7a: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:45.493  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:20:45.493  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{918292b: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:45.513  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{e16d188: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:45.523  3424  3797 V AlarmManager:  remove PendingIntent] PendingIntent{abed721: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:45.573  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:45.753  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:45.933  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:46.113  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:46.293  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:46.473  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:46.493  3424  3817 V AlarmManager: Expired Alarm result :4
,09-21 17:20:46.503  4948  4948 D BtGatt.ScanManager: awakened up at time 264111
,09-21 17:20:46.503  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-21 17:20:46.503  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{e6e2d07: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.513  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
09-21 17:20:46.513  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:46.513  4948  5060 D BtGatt.GattService: current time is 264121779964
09-21 17:20:46.513  4948  5060 D BtGatt.GattService: Batch record : [-93, 108, -84, 117, 25, 82, 1, -128, -73, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -55, 58, -41, 92, 6, -55, -9, 69, 49, -39, -89, -69, -45, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -105, 0, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0]
,09-21 17:20:46.513  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -55, 58, -41, 92, 6, -55, -9, 69, 49, -39, -89, -69, -45]
09-21 17:20:46.513  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{10b7e34: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
09-21 17:20:46.513  4948  5060 D ScanRecord: parseFromBytes
,09-21 17:20:46.513  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:46.513  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-21 17:20:46.513  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:46.513  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:46.513  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-21 17:20:46.513  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:46.513  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:46.513  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-21 17:20:46.513  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:46.513  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:46.513  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
09-21 17:20:46.513  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:46.523  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:46.523  9340  9351 D ScanRecord: first manudata for manu ID
09-21 17:20:46.523  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:46.523  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:46.523  9340  9351 D ScanRecord: first manudata for manu ID
09-21 17:20:46.523  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:46.523  9340  9351 D ScanRecord: first manudata for manu ID
,09-21 17:20:46.523  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:46.523  9340  9351 D ScanRecord: first manudata for manu ID
,09-21 17:20:46.523  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{290c45d: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.533  3424  3797 V AlarmManager:  remove PendingIntent] PendingIntent{6621d2: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.543  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{43692a3: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.543  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{8fc49a0: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.553  3424  4713 V AlarmManager:  remove PendingIntent] PendingIntent{39a4959: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.553  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{ee0891e: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.563  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{a95b5ff: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.563  3424  3443 V AlarmManager:  remove PendingIntent] PendingIntent{16c5fcc: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:46.653  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:46.833  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:47.013  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:47.193  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:47.373  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:47.403  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.413  9340  9405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 17:20:47.413  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 17:20:47.413  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 17:20:47.413  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:47.413  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 17:20:47.413  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 17:20:47.413  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-21 17:20:47.413  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 17:20:47.423  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-21 17:20:47.423  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 17:20:47.423  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-21 17:20:47.423  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.423  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.423  9340  9405 D BluetoothLeScanner: Stop Scan
,09-21 17:20:47.433  4948  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:20:47.433  4948  4960 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:20:47.433  4948  4960 D BtGatt.GattService: stopScan() - queue size =1
09-21 17:20:47.433  4948  5111 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-21 17:20:47.433  4948  5111 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
09-21 17:20:47.443  4948  5103 D BtGatt.ScanManager: filter size is 1
09-21 17:20:47.443  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:47.443  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 17:20:47.443  4948  5103 D BtGatt.ScanManager: delete FilterIndex - 3
09-21 17:20:47.443  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:47.443  4948  5111 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-21 17:20:47.443  4948  5111 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-21 17:20:47.443  4948  5445 D BtGatt.GattService: unregisterClient() - clientIf=7
09-21 17:20:47.443  3424  3797 V AlarmManager:  remove PendingIntent] PendingIntent{41d2215: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:47.443  4948  5060 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-21 17:20:47.443  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:47.443  4948  5103 D BtGatt.ScanManager: stopping BLe Batch
09-21 17:20:47.443  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 17:20:47.443  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-21 17:20:47.443  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 17:20:47.443  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 17:20:47.443  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 17:20:47.453  4948  5060 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-21 17:20:47.453  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:47.453  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:20:47.453  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 17:20:47.453  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
09-21 17:20:47.463  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:47.463  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:47.463  4948  5060 D BtGatt.GattService: current time is 265071191348
09-21 17:20:47.463  4948  5060 D BtGatt.GattService: Batch record : [-93, 108, -84, 117, 25, 82, 1, -128, -77, 8, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -55, 58, -41, 92, 6, -55, -9, 69, 49, -39, -89, -69, -45, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -101, 9, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-21 17:20:47.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -55, 58, -41, 92, 6, -55, -9, 69, 49, -39, -89, -69, -45]
09-21 17:20:47.463  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:47.463  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{208192a: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
09-21 17:20:47.463  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:47.463  3424  4713 V AlarmManager:  remove PendingIntent] PendingIntent{599b31b: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
09-21 17:20:47.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 17:20:47.463  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:47.463  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:47.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-21 17:20:47.463  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:47.463  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:47.463  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,09-21 17:20:47.463  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:47.463  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.473  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{8e5acb8: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:47.463  9340  9405 D BluetoothLeAdvertiser: stop advertising
09-21 17:20:47.463  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:47.463  9340  9405 D BluetoothLeAdvertiser: wrapper is null
09-21 17:20:47.463  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 17:20:47.463  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-21 17:20:47.463  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:20:47.463  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:20:47.473  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 17:20:47.473  9340  9340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 17:20:47.473  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 17:20:47.473  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 17:20:47.473  9340  9405 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f59c3ff not in the list
,09-21 17:20:47.473  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 17:20:47.473  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
09-21 17:20:47.473  9340  9405 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:20:47.473  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:20:47.473  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:47.473  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:20:47.483  9340  9340 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:20:47.483  9340  9340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 17:20:47.483  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{aa4dc64: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.493  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.493  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.493  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.493  3424  3443 V AlarmManager:  remove PendingIntent] PendingIntent{cb07ecd: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.493  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 17:20:47.503  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.503  3424  4233 V AlarmManager:  remove PendingIntent] PendingIntent{d56a382: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.503  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:47.503  9340  9340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 17:20:47.503  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 17:20:47.503  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 17:20:47.503  9340  9340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:20:47.503  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{c416a93: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.503  9340  9340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 17:20:47.503  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:47.503  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:20:47.513  9340  9340 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:20:47.513  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 17:20:47.513  9340  9340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:20:47.513  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{40e1cef: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.523  9340  9340 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 17:20:47.523  3424  4713 V AlarmManager:  remove PendingIntent] PendingIntent{6ad53fc: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.523  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{84bba85: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.533  3424  3990 V AlarmManager:  remove PendingIntent] PendingIntent{2f120da: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.533  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{b49990b: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:47.553  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:47.733  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:47.913  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:48.023  9340  9340 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 17:20:48.093  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:48.273  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:48.453  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:48.633  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:48.813  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:48.993  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:49.173  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:49.353  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:49.533  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:49.713  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:49.893  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:50.073  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:50.253  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:50.353  3150  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-21 17:20:50.433  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:50.613  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:50.693  3424  5971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-21 17:20:50.793  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:50.973  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:51.153  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:51.333  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:51.513  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:51.693  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:51.873  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:52.053  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:52.233  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:52.413  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:52.483  9340  9405 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-21 17:20:52.483  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:20:52.503  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:20:52.513  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:20:52.513  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.523  9340  9405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 17:20:52.523  9340  9405 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:20:52.523  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:20:52.523  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 17:20:52.523  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 17:20:52.523  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:52.523  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:20:52.533  9340  9405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:20:52.543  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:52.543  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.543  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.553  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:52.553  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.553  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.563  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 17:20:52.563  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 17:20:52.563  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 17:20:52.563  9340  9405 D BluetoothLeScanner: Start Scan
,09-21 17:20:52.563  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.563  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.573  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.573  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.583  4948  5445 D BtGatt.GattService: registerClient() - UUID=f1e5517d-03fe-4f0c-aaa5-6707d4c39e2b
,09-21 17:20:52.593  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:52.623  4948  5060 D BtGatt.GattService: onClientRegistered() - UUID=f1e5517d-03fe-4f0c-aaa5-6707d4c39e2b, clientIf=7
,09-21 17:20:52.623  9340  9350 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-21 17:20:52.623  4948  5119 D BtGatt.GattService: start scan with filters
,09-21 17:20:52.633  4948  5119 D BtGatt.GattService: getScanSettings
,09-21 17:20:52.633  4948  5119 D BtGatt.GattService: Is it foreground application = true
09-21 17:20:52.633  4948  5119 D BtGatt.GattService: not a background application
,09-21 17:20:52.643  4948  5119 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-21 17:20:52.643  4948  5119 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:20:52.643  4948  5119 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:20:52.643  4948  5111 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-21 17:20:52.643  4948  5111 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
,09-21 17:20:52.653  4948  5103 D BtGatt.ScanManager: handling starting scan
09-21 17:20:52.653  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 17:20:52.653  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-21 17:20:52.653  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 17:20:52.653  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 17:20:52.653  4948  5103 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.653  4948  5103 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.663  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 67
,09-21 17:20:52.663  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-21 17:20:52.663  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 17:20:52.663  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 17:20:52.663  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{c02f132: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.663  9340  9340 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:20:52.673  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 17:20:52.673  4948  5060 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-21 17:20:52.673  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:20:52.673  4948  5103 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
09-21 17:20:52.673  4948  5103 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-21 17:20:52.673  4948  5103 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-21 17:20:52.673  4948  5103 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-21 17:20:52.673  4948  5060 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-21 17:20:52.673  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.673  4948  5103 D BtGatt.ScanManager: Starting BLE batch scan
09-21 17:20:52.673  4948  5103 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-21 17:20:52.673  9340  9405 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 17:20:52.673  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 23
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574520
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:52.683  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{16a1e83: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:52.683  4948  5111 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574520
09-21 17:20:52.683  4948  5060 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-21 17:20:52.683  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.683  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:52.683  4948  5060 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-21 17:20:52.683  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.683  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{bcd1800: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.683  9340  9405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 17:20:52.693  9340  9405 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 17:20:52.693  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 17:20:52.693  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 17:20:52.693  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:52.693  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 17:20:52.693  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-21 17:20:52.693  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 17:20:52.693  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 17:20:52.693  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 17:20:52.693  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-21 17:20:52.693  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 17:20:52.693  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{3a36839: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.693  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.693  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:52.693  9340  9405 D BluetoothLeScanner: Stop Scan
,09-21 17:20:52.703  4948  5445 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:20:52.703  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{b6aee7e: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.703  4948  5445 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:20:52.703  4948  5445 D BtGatt.GattService: stopScan() - queue size =1
09-21 17:20:52.703  4948  5111 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-21 17:20:52.703  4948  5111 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
09-21 17:20:52.703  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:52.703  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:52.703  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:52.703  4948  5111 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-21 17:20:52.703  4948  4960 D BtGatt.GattService: unregisterClient() - clientIf=7
09-21 17:20:52.703  4948  5111 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-21 17:20:52.703  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 17:20:52.703  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 17:20:52.703  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 17:20:52.703  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 17:20:52.703  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-21 17:20:52.703  4948  5103 D BtGatt.ScanManager: filter size is 1
09-21 17:20:52.703  4948  5103 D BtGatt.ScanManager: delete FilterIndex - 4
09-21 17:20:52.703  4948  5060 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-21 17:20:52.703  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:20:52.703  4948  5103 D BtGatt.ScanManager: stopping BLe Batch
09-21 17:20:52.703  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 17:20:52.703  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{4a61fdf: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.713  4948  5060 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-21 17:20:52.713  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.713  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-21 17:20:52.713  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.713  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-21 17:20:52.713  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.713  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:52.713  9340  9405 D BluetoothLeAdvertiser: stop advertising
09-21 17:20:52.713  9340  9405 D BluetoothLeAdvertiser: wrapper is null
09-21 17:20:52.713  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 17:20:52.713  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 17:20:52.713  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:20:52.713  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{debb42c: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.713  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:20:52.713  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{4494ef5: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
09-21 17:20:52.713  9340  9405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 17:20:52.713  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:52.713  9340  9340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 17:20:52.713  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 17:20:52.713  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:52.713  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 17:20:52.713  9340  9405 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f59c3ff not in the list
,09-21 17:20:52.713  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:52.713  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
09-21 17:20:52.713  9340  9405 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:20:52.713  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:20:52.723  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{d2ce571: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.723  9340  9340 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:20:52.723  9340  9340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 17:20:52.723  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{6c4f56: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.723  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.723  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.733  9340  9340 D BluetoothAdapter: STATE_ON
09-21 17:20:52.733  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{ce2bd7: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.733  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 17:20:52.733  9340  9340 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.733  9340  9340 D BluetoothAdapter: STATE_ON
09-21 17:20:52.733  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{86e5cc4: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.733  9340  9340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 17:20:52.733  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 17:20:52.733  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:20:52.733  9340  9340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:20:52.743  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{ad967ad: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.743  9340  9405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:20:52.743  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:20:52.743  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 17:20:52.743  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:52.743  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{8f60ae2: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.743  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.743  9340  9405 D BluetoothLeAdvertiser: stop advertising
09-21 17:20:52.743  9340  9405 D BluetoothLeAdvertiser: wrapper is null
09-21 17:20:52.743  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 17:20:52.743  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-21 17:20:52.743  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.753  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:52.753  9340  9405 D BluetoothLeScanner: could not find callback wrapper
09-21 17:20:52.753  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 17:20:52.753  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:20:52.753  9340  9405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a55cc not in the list
,09-21 17:20:52.753  9340  9405 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 17:20:52.753  9340  9340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 17:20:52.753  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:52.753  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 17:20:52.753  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{4dfae73: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.753  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:20:52.763  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{b6a143a: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.763  9340  9340 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 17:20:52.763  9340  9340 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 17:20:52.763  9340  9340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:20:52.763  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.763  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{d3078eb: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:20:52.763  9340  9405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:20:52.773  9340  9340 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 17:20:52.773  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.773  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{33d4648: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.773  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:52.773  9340  9405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 17:20:52.773  9340  9405 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:20:52.773  9340  9405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:20:52.773  9340  9405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-21 17:20:52.773  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 17:20:52.773  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:20:52.773  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 17:20:52.773  3424  4403 V AlarmManager:  remove PendingIntent] PendingIntent{9047ef4: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.783  9340  9405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:20:52.783  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.783  3424  4403 V AlarmManager:  remove PendingIntent] PendingIntent{a50961d: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.783  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:52.783  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.793  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.793  3424  3797 V AlarmManager:  remove PendingIntent] PendingIntent{97af092: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.793  9340  9340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:20:52.793  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.793  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 17:20:52.793  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 17:20:52.793  9340  9405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 17:20:52.793  9340  9405 D BluetoothLeScanner: Start Scan
,09-21 17:20:52.793  9340  9405 D BluetoothAdapter: STATE_ON
09-21 17:20:52.793  3424  3980 V AlarmManager:  remove PendingIntent] PendingIntent{1911a63: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.793  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.803  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.803  9340  9405 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.803  3424  4403 V AlarmManager:  remove PendingIntent] PendingIntent{c649660: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.803  4948  4960 D BtGatt.GattService: registerClient() - UUID=a30b763a-9426-4f46-a46c-8d08e2f65b44
,09-21 17:20:52.803  3424  4233 V AlarmManager:  remove PendingIntent] PendingIntent{ae57719: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.813  3424  3990 V AlarmManager:  remove PendingIntent] PendingIntent{45383de: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.813  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{570f9bf: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.843  4948  5060 D BtGatt.GattService: onClientRegistered() - UUID=a30b763a-9426-4f46-a46c-8d08e2f65b44, clientIf=7
,09-21 17:20:52.843  9340  9351 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-21 17:20:52.843  4948  5119 D BtGatt.GattService: start scan with filters
,09-21 17:20:52.843  4948  5119 D BtGatt.GattService: getScanSettings
,09-21 17:20:52.853  4948  5119 D BtGatt.GattService: Is it foreground application = true
09-21 17:20:52.853  4948  5119 D BtGatt.GattService: not a background application
,09-21 17:20:52.853  4948  5119 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-21 17:20:52.853  4948  5119 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:20:52.853  4948  5119 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:20:52.853  4948  5111 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-21 17:20:52.853  4948  5111 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
,09-21 17:20:52.853  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 17:20:52.853  9340  9405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 17:20:52.853  9340  9405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-21 17:20:52.853  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 17:20:52.853  4948  5103 D BtGatt.ScanManager: handling starting scan
09-21 17:20:52.853  4948  5103 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.863  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:20:52.863  9340  9405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-21 17:20:52.863  9340  9340 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:20:52.863  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 68
09-21 17:20:52.863  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-21 17:20:52.863  9340  9405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 17:20:52.863  4948  5103 D BluetoothAdapter: STATE_ON
,09-21 17:20:52.863  4948  5060 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-21 17:20:52.863  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.863  4948  5103 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
09-21 17:20:52.863  4948  5103 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-21 17:20:52.863  4948  5103 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-21 17:20:52.863  4948  5103 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-21 17:20:52.863  3424  4403 V AlarmManager:  remove PendingIntent] PendingIntent{5ecb88c: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.873  4948  5060 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-21 17:20:52.873  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.873  9340  9405 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 17:20:52.873  4948  5103 D BtGatt.ScanManager: Starting BLE batch scan
09-21 17:20:52.873  4948  5103 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 24
,09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574520
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:52.873  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{e4d6bd5: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:20:52.873  4948  5111 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574520
09-21 17:20:52.873  4948  5060 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-21 17:20:52.873  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:20:52.873  4948  5060 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-21 17:20:52.873  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:52.873  3424  3980 V AlarmManager:  remove PendingIntent] PendingIntent{98fffea: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.883  3424  3990 V AlarmManager:  remove PendingIntent] PendingIntent{b4572db: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.883  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{5f2d178: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.883  3424  3797 V AlarmManager:  remove PendingIntent] PendingIntent{f05f051: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.893  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{46630b6: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.893  3424  4233 V AlarmManager:  remove PendingIntent] PendingIntent{51e61b7: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.893  3424  3990 V AlarmManager:  remove PendingIntent] PendingIntent{a3f8d24: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.903  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{7e8408d: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.903  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{b9ca242: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.913  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{c2d6253: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.913  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{27a5790: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.923  3424  4713 V AlarmManager:  remove PendingIntent] PendingIntent{e255889: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.923  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{9d6a08e: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:52.953  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:53.133  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:53.313  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:53.363  9340  9340 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-21 17:20:53.363  9340  9340 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:20:53.363  9340  9340 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-21 17:20:53.493  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:53.673  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:53.823  3424  5934 D SSRM:n  : SIOP:: AP = 300, PST = 290 (W:14), CP = 250, LCD = 1
,09-21 17:20:53.853  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:53.883  3424  3817 V AlarmManager: Expired Alarm result :4
,09-21 17:20:53.883  4948  4948 D BtGatt.ScanManager: awakened up at time 271495
,09-21 17:20:53.883  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:20:53.893  3424  4403 V AlarmManager:  remove PendingIntent] PendingIntent{f555cbc: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.893  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
,09-21 17:20:53.893  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:53.893  4948  5060 D BtGatt.GattService: current time is 271507151228
09-21 17:20:53.893  4948  5060 D BtGatt.GattService: Batch record : [-93, 108, -84, 117, 25, 82, 1, -128, -89, 1, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -54, 58, 60, -115, 80, 127, 10, -100, -39, 62, 77, 110, -95, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -87, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 17:20:53.893  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -54, 58, 60, -115, 80, 127, 10, -100, -39, 62, 77, 110, -95]
,09-21 17:20:53.893  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:53.893  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:53.893  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-21 17:20:53.893  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:53.903  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{f01f445: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.893  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-21 17:20:53.903  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:53.903  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-21 17:20:53.903  4948  5060 D ScanRecord: parseFromBytes
,09-21 17:20:53.903  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-21 17:20:53.903  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:53.903  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-21 17:20:53.903  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:53.903  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:53.903  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:53.903  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:53.903  9340  9350 D ScanRecord: first manudata for manu ID
,09-21 17:20:53.903  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:53.903  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:53.903  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:53.903  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:53.903  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:53.913  3424  4233 V AlarmManager:  remove PendingIntent] PendingIntent{ea0379a: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.923  3424  3990 V AlarmManager:  remove PendingIntent] PendingIntent{644c8cb: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.923  3424  5102 V AlarmManager:  remove PendingIntent] PendingIntent{87988a8: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.933  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{d528fc1: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.933  3424  3443 V AlarmManager:  remove PendingIntent] PendingIntent{43a3366: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.943  3424  4615 V AlarmManager:  remove PendingIntent] PendingIntent{f5526a7: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.943  3424  4713 V AlarmManager:  remove PendingIntent] PendingIntent{5328754: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:53.953  3424  4266 V AlarmManager:  remove PendingIntent] PendingIntent{ab766fd: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:54.033  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:54.213  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:54.393  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:54.573  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:54.753  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:54.903  3424  3817 V AlarmManager: Expired Alarm result :4
,09-21 17:20:54.903  4948  4948 D BtGatt.ScanManager: awakened up at time 272517
,09-21 17:20:54.913  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:20:54.913  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{3238643: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:54.923  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
09-21 17:20:54.923  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:54.923  4948  5060 D BtGatt.GattService: current time is 272535966227
09-21 17:20:54.923  4948  5060 D BtGatt.GattService: Batch record : [-93, 108, -84, 117, 25, 82, 1, -128, -87, 17, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -54, 58, 60, -115, 80, 127, 10, -100, -39, 62, 77, 110, -95, 0, -93, 108, -84, 117, 25, 82, 1, -128, -86, 10, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -53, 58, 93, -1, -13, -83, -43, 13, -28, -48, 46, -25, -69, 0, 81, 34, 97, 112, -14, -5, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
09-21 17:20:54.923  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{3dac4c0: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
09-21 17:20:54.923  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -54, 58, 60, -115, 80, 127, 10, -100, -39, 62, 77, 110, -95]
09-21 17:20:54.923  4948  5060 D ScanRecord: parseFromBytes
,09-21 17:20:54.923  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:54.923  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -53, 58, 93, -1, -13, -83, -43, 13, -28, -48, 46, -25, -69]
09-21 17:20:54.923  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:54.923  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:54.923  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-21 17:20:54.923  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:54.923  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:54.933  9340  9351 D ScanRecord: parseFromBytes
,09-21 17:20:54.933  9340  9351 D ScanRecord: first manudata for manu ID
09-21 17:20:54.933  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:54.933  9340  9351 D ScanRecord: first manudata for manu ID
09-21 17:20:54.933  3424  3980 V AlarmManager:  remove PendingIntent] PendingIntent{89875f9: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:54.933  9340  9351 D ScanRecord: parseFromBytes
09-21 17:20:54.933  9340  9351 D ScanRecord: first manudata for manu ID
09-21 17:20:54.933  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:54.943  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{472493e: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:54.943  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{aee439f: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:54.953  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{c076cec: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:54.953  3424  4295 V AlarmManager:  remove PendingIntent] PendingIntent{ce178b5: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:55.113  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:55.293  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:55.333  3150  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-21 17:20:55.473  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:55.653  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:55.833  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:55.843  3424  4615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-21 17:20:55.843  3424  4615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-21 17:20:55.843  3424  4615 D BatteryService: online:4, current avg:-30, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-21 17:20:55.843  3424  4615 D BatteryService: stay LED for fully charged
09-21 17:20:55.843  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-21 17:20:55.853  3424  3424 I MotionRecognitionService: Plugged
,09-21 17:20:55.853  3424  3424 D MotionRecognitionService:   cableConnection= 1
09-21 17:20:55.853  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-21 17:20:55.853  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,09-21 17:20:55.863  3424  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-21 17:20:55.863  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-21 17:20:55.863  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-21 17:20:55.863  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-21 17:20:55.873  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-21 17:20:55.883  4988  4988 D CommonServiceConfiguration: getStringValueSetting
,09-21 17:20:55.883  4948  4948 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-21 17:20:55.883  4948  5307 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-21 17:20:55.893  4988  4988 D BatteryMonitor: new battery level: 100
,09-21 17:20:55.893  4717  4717 D BatteryController: saveBatteryData : level[100], status[5]
,09-21 17:20:55.923  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-21 17:20:55.933  3424  3817 V AlarmManager: Expired Alarm result :4
,09-21 17:20:55.933  4948  4948 D BtGatt.ScanManager: awakened up at time 273547
,09-21 17:20:55.943  4948  5103 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:20:55.943  4948  5060 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
09-21 17:20:55.943  3424  4324 V AlarmManager:  remove PendingIntent] PendingIntent{b7d7abb: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
09-21 17:20:55.943  4948  5060 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:20:55.953  4948  5060 D BtGatt.GattService: current time is 273560191380
09-21 17:20:55.953  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{7746bd8: PendingIntentRecord{b24294b com.android.bluetooth broadcastIntent}}
,09-21 17:20:55.953  4948  5060 D BtGatt.GattService: Batch record : [-93, 108, -84, 117, 25, 82, 1, -128, -70, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -53, 58, 93, -1, -13, -83, -43, 13, -28, -48, 46, -25, -69, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-21 17:20:55.953  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -53, 58, 93, -1, -13, -83, -43, 13, -28, -48, 46, -25, -69]
09-21 17:20:55.953  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:55.953  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:55.953  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-21 17:20:55.953  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:55.953  4948  5060 D ScanRecord: first manudata for manu ID
,09-21 17:20:55.953  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 17:20:55.953  4948  5060 D ScanRecord: parseFromBytes
09-21 17:20:55.953  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:55.953  4948  5060 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-21 17:20:55.953  4948  5060 D ScanRecord: parseFromBytes
,09-21 17:20:55.953  4948  5060 D ScanRecord: first manudata for manu ID
09-21 17:20:55.953  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:55.953  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:55.953  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:55.953  9340  9350 D ScanRecord: first manudata for manu ID
,09-21 17:20:55.953  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:55.953  9340  9350 D ScanRecord: first manudata for manu ID
09-21 17:20:55.953  9340  9350 D ScanRecord: parseFromBytes
09-21 17:20:55.953  9340  9350 D ScanRecord: first manudata for manu ID
,09-21 17:20:55.953  3424  4289 V AlarmManager:  remove PendingIntent] PendingIntent{67deb31: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:55.963  3424  4807 V AlarmManager:  remove PendingIntent] PendingIntent{a2c4216: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:55.963  3424  3442 V AlarmManager:  remove PendingIntent] PendingIntent{3ff0797: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:55.973  3424  4281 V AlarmManager:  remove PendingIntent] PendingIntent{db06d84: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:55.973  3424  3990 V AlarmManager:  remove PendingIntent] PendingIntent{d95096d: PendingIntentRecord{3b0d6c4 com.android.bluetooth broadcastIntent}}
,09-21 17:20:56.013  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:56.193  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:20:56.373  3424  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
