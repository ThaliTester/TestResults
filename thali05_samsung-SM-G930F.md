#### Test 86147834a13d096_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-22 12:57:38.653  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:38.833  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:39.013  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:39.193  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:39.373  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:39.383  9239  9239 I FIPS_bssl: FIPS approved mode (1) | 9239 | app_process
09-22 12:57:39.393  9239  9239 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 12:57:39.393  9239  9239 D AndroidRuntime: CheckJNI is OFF
09-22 12:57:39.393  9239  9239 D AndroidRuntime: readGMSProperty: start
09-22 12:57:39.393  9239  9239 D AndroidRuntime: readGMSProperty: already setted!!
09-22 12:57:39.393  9239  9239 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-22 12:57:39.393  9239  9239 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-22 12:57:39.393  9239  9239 D AndroidRuntime: readGMSProperty: end
09-22 12:57:39.393  9239  9239 D AndroidRuntime: addProductProperty: start
09-22 12:57:39.413  9239  9239 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 12:57:39.433  9239  9239 I Radio-JNI: register_android_hardware_Radio DONE
09-22 12:57:39.433  9239  9239 E AffinityControl: AffinityControl: registerfunction enter
09-22 12:57:39.443  9239  9239 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-22 12:57:39.473  3445  3964 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-22 12:57:39.473  3445  3964 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-22 12:57:39.493  3445  3964 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:57:39.493  3445  3964 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:57:39.493  3445  3964 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-22 12:57:39.503  3445  3964 D ActivityManager: mDVFSHelper.acquire()
09-22 12:57:39.503  3445  3964 V WindowManager: addAppToken: AppWindowToken{d015e14e2 token=Token{71359ad ActivityRecord{e70d6c4 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-22 12:57:39.513  3445  3563 I InjectionManager: Inside getClassLibPath caller 
09-22 12:57:39.523  3445  3563 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 12:57:39.523  3445  3563 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3895e3a V.E...... R.....ID 0,0-0,0}
09-22 12:57:39.523  3445  3563 W WindowManager: Failed looking up window
09-22 12:57:39.523  3445  3563 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@70efaeb does not exist
09-22 12:57:39.523  3445  3563 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 12:57:39.523  3445  3563 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 12:57:39.523  3445  3563 D ISSUE_DEBUG: InputChannelName : e96a048 Starting com.test.thalitest
09-22 12:57:39.533  9248  9248 E Zygote  : v2
09-22 12:57:39.533  9248  9248 I libpersona: KNOX_SDCARD checking this for 10171
09-22 12:57:39.533  9248  9248 I libpersona: KNOX_SDCARD not a persona
09-22 12:57:39.533  9248  9248 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-22 12:57:39.533  3445  3964 I ActivityManager: Start proc 9248:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-22 12:57:39.533  9248  9248 E Zygote  : accessInfo : 0
09-22 12:57:39.533  3445  3964 D InputDispatcher: Focused application set to: xxxx
09-22 12:57:39.533  9248  9248 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-22 12:57:39.533  9239  9239 D AndroidRuntime: Shutting down VM
09-22 12:57:39.533  3445  3852 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-22 12:57:39.543  3006  3006 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-22 12:57:39.553  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:39.563  9248  9248 D TimaKeyStoreProvider: TimaSignature is unavailable
09-22 12:57:39.563  9248  9248 D ActivityThread: Added TimaKeyStore provider
09-22 12:57:39.583  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:57:39.583  3445  4845 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3445
09-22 12:57:39.583  3445  4845 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:57:39.583  3445  4845 D PowerManagerService: mDisplayReady: false
09-22 12:57:39.583  3445  4845 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:57:39.583  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:57:39.583  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:57:39.583  3445  4845 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:57:39.583  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:57:39.593  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9a503c00
09-22 12:57:39.583  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:39.593  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-22 12:57:39.583  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:39.583  3445  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-22 12:57:39.593  3445  4221 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3445
09-22 12:57:39.593  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:57:39.593  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:57:39.593  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:57:39.593  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:57:39.593  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:39.593  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:39.593  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:57:39.593  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:57:39.593  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:39.593  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:39.593  3445  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:57:39.593  3445  3567 D PowerManagerService: mDisplayReady: true
09-22 12:57:39.593  3445  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:57:39.603  3445  3972 D ActivityManager:  Launching com.test.thalitest, updated priority
09-22 12:57:39.613  3445  4424 V WindowStateAnimator: Finishing drawing window Window{91fd888 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-22 12:57:39.613  3445  3445 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-22 12:57:39.613  3445  3531 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-22 12:57:39.633  3006  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f99ffee78
09-22 12:57:39.633  3006  3016 D libEGL  : eglTerminate EGLDisplay = 0x7f99ffee78
09-22 12:57:39.643  3006  3828 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-22 12:57:39.643  3006  3014 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-22 12:57:39.653  4290  4290 V ActivityThread: updateVisibility : ActivityRecord{6460869 token=android.os.BinderProxy@42c27ed {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-22 12:57:39.653  4290  4290 D Launcher: onTrimMemory. Level: 20
09-22 12:57:39.653  3445  3962 V WindowStateAnimator: Finishing drawing window Window{a974c7a u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-22 12:57:39.653  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:57:39.653  6039  6039 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 12:57:39.653  6039  6039 V ActivityThread: updateVisibility : ActivityRecord{5e291c1 token=android.os.BinderProxy@ca7a7ca {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-22 12:57:39.663  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ff225ebf8
09-22 12:57:39.663  3006  4120 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-22 12:57:39.663  3006  3016 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-22 12:57:39.673  3006  3014 D libEGL  : eglTerminate EGLDisplay = 0x7f9a280e78
09-22 12:57:39.673  3006  3016 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-22 12:57:39.673  3006  3828 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-22 12:57:39.693  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ff225ebf8
09-22 12:57:39.693  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ff225ebf8
09-22 12:57:39.733  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:39.743  3445  3445 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3445 (0x0)
09-22 12:57:39.743  3445  3445 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3445 (0x0)
09-22 12:57:39.743  3445  3445 D PowerManagerService: mDisplayReady: false
09-22 12:57:39.743  3445  3445 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:57:39.743  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:57:39.743  3445  3445 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:57:39.743  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:57:39.743  3445  3445 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:57:39.743  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:39.743  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:39.743  3445  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-22 12:57:39.743  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9a503c00
09-22 12:57:39.743  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-22 12:57:39.743  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:57:39.743  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:57:39.743  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:57:39.743  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:39.743  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:57:39.743  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:39.743  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:57:39.743  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:57:39.743  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:39.743  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:39.743  3445  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:57:39.743  3445  3567 D PowerManagerService: mDisplayReady: true
09-22 12:57:39.743  3445  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:57:39.913  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:39.953  3445  3972 I WindowManager: Screenshot max retries 4 of Token{71359ad ActivityRecord{e70d6c4 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{e96a048 u0 d0 Starting com.test.thalitest} drawState=1
09-22 12:57:39.963  3445  3563 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:57:39.963  3445  3445 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:57:39.963  3445  3563 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-22 12:57:39.963  3445  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:57:39.973  3445  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:57:39.973  3445  3445 I KnoxTimeoutHandler: SD activityfalse
09-22 12:57:39.973  3445  3852 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-22 12:57:39.983  9248  9248 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 12:57:39.993  3445  3467 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-22 12:57:39.993  3445  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-22 12:57:39.993  3445  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:57:39.993  9248  9248 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-22 12:57:40.003  3445  3563 V WindowStateAnimator: Finishing drawing window Window{e96a048 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-22 12:57:40.003  3445  3563 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:57:40.003  3445  3563 D ActivityManager: mDVFSHelper.release()
09-22 12:57:40.003  3445  3445 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 12:57:40.003  3445  3563 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{cc1c304 u0 com.samsung.android.MtpApplication/.USBConnection t3} time:237462
09-22 12:57:40.003  3445  3445 I KnoxTimeoutHandler: SD activityfalse
09-22 12:57:40.013  9248  9248 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:57:40.013  3445  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-22 12:57:40.013  3445  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:57:40.013  3445  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 12:57:40.013  9248  9248 I InjectionManager: Inside getClassLibPath caller 
09-22 12:57:40.023  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7ff225ead8
09-22 12:57:40.033  9248  9248 D InjectionManager: InjectionManager
09-22 12:57:40.033  9248  9248 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-22 12:57:40.033  9248  9248 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-22 12:57:40.033  9248  9248 I InjectionManager: featureStore :{}
09-22 12:57:40.033  9248  9248 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 12:57:40.043  9248  9248 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-22 12:57:40.043  9248  9248 D RelationGraph: garbageCollect()
09-22 12:57:40.043  9248  9248 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 12:57:40.073  9248  9248 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-22 12:57:40.093  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:40.103  9248  9248 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-22 12:57:40.113  9248  9248 D ResourcesManager: For user 0 new overlays fetched Null
09-22 12:57:40.113  9248  9248 I InjectionManager: Inside getClassLibPath caller 
09-22 12:57:40.113  9248  9248 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-22 12:57:40.153  9248  9248 I cr_LibraryLoader: Time to load native libraries: 29 ms (timestamps 7588-7617)
09-22 12:57:40.153  9248  9248 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-22 12:57:40.223  3445  3876 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-22 12:57:40.223  9248  9263 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-22 12:57:40.243  9248  9248 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {92266a8}
09-22 12:57:40.243  9248  9248 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-22 12:57:40.273  9248  9248 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-22 12:57:40.273  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:40.303  9248  9248 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-22 12:57:40.323  3445  3876 I MdnieScenarioControlService: mGameModeLauncher : false
09-22 12:57:40.323  3445  3876 I MdnieScenarioControlService: setUIMode
09-22 12:57:40.453  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:40.453  3445  3531 W ActivityManager: Activity pause timeout for ActivityRecord{e70d6c4 u0 com.test.thalitest/.MainActivity t4}
09-22 12:57:40.513  9248  9248 D libEGL  : eglInitialize EGLDisplay = 0xffb1611c
09-22 12:57:40.613  3445  3962 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-22 12:57:40.613  3445  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-22 12:57:40.633  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:40.693  9248  9248 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-22 12:57:40.713  9248  9248 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-22 12:57:40.713  9248  9248 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-22 12:57:40.753  9248  9248 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-22 12:57:40.813  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:40.813  9248  9248 D Activity: performCreate Call Injection manager
09-22 12:57:40.823  9248  9248 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-22 12:57:40.833  9248  9248 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 12:57:40.843  9248  9248 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{23afa87 I.E...... R.....ID 0,0-0,0}
09-22 12:57:40.853  9248  9300 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-22 12:57:40.873  3445  3467 W WindowManager: Failed looking up window
09-22 12:57:40.873  3445  3467 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@d8c4acb does not exist
09-22 12:57:40.873  3445  3467 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 12:57:40.873  3445  3467 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 12:57:40.873  3445  3467 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 12:57:40.873  3445  3467 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-22 12:57:40.873  3445  3467 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-22 12:57:40.873  3445  3467 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-22 12:57:40.873  3445  3962 D ISSUE_DEBUG: InputChannelName : 787e2a8 com.test.thalitest/com.test.thalitest.MainActivity
09-22 12:57:40.883  3445  4281 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-22 12:57:40.883  3445  4281 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:57:40.883  3445  3445 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:57:40.893  3445  3445 I KnoxTimeoutHandler: Shared devices show user statefalse
09-22 12:57:40.893  9248  9248 V ActivityThread: updateVisibility : ActivityRecord{300ddd token=android.os.BinderProxy@4fe06af {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-22 12:57:40.913  9248  9263 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-22 12:57:40.943  9248  9248 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9248
09-22 12:57:40.953  3445  4281 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9248 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-22 12:57:40.953  3445  3864 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-22 12:57:40.953  3445  3864 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-22 12:57:40.963  3445  3864 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-22 12:57:40.963  3445  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-22 12:57:40.973  3445  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-22 12:57:40.973  3445  5948 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-22 12:57:40.983  9248  9248 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 12:57:40.983  3445  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-22 12:57:40.983  3445  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-22 12:57:40.983  3445  3864 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-22 12:57:40.993  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:41.003  3006  3006 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
09-22 12:57:41.023  9248  9300 D libEGL  : eglInitialize EGLDisplay = 0xdc93f7c4
09-22 12:57:41.023  9248  9300 I OpenGLRenderer: Initialized EGL, version 1.4
09-22 12:57:41.033  9248  9300 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-22 12:57:41.043  3445  4300 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3445
09-22 12:57:41.043  3445  4300 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:57:41.043  3445  4300 D PowerManagerService: mDisplayReady: false
09-22 12:57:41.043  3445  4300 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:57:41.043  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:57:41.043  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9a503c00
09-22 12:57:41.043  3445  4300 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:57:41.043  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-22 12:57:41.043  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:57:41.043  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:41.043  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:41.043  3445  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-22 12:57:41.043  3445  3563 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-22 12:57:41.043  3445  3563 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-22 12:57:41.043  3006  3051 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=238508394021)
09-22 12:57:41.063  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:57:41.063  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:57:41.063  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:41.063  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:57:41.063  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:41.063  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:57:41.063  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:57:41.063  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:57:41.063  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:41.063  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:41.063  3445  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:57:41.063  3445  3567 D PowerManagerService: mDisplayReady: true
09-22 12:57:41.063  3445  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:57:41.083  9248  9248 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-22 12:57:41.093  3445  3972 V WindowStateAnimator: Finishing drawing window Window{787e2a8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-22 12:57:41.103  9248  9248 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-22 12:57:41.103  3445  4281 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3445
09-22 12:57:41.113  3445  3563 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:57:41.113  3445  3445 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 12:57:41.113  3445  3563 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s158ms (total +1s601ms)
09-22 12:57:41.113  3445  3964 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3445
09-22 12:57:41.113  3445  3563 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e70d6c4 u0 com.test.thalitest/.MainActivity t4} time:238572
09-22 12:57:41.113  3445  3445 I KnoxTimeoutHandler: SD activityfalse
09-22 12:57:41.113  9248  9304 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 12:57:41.113  9248  9304 D libEGL  : eglInitialize EGLDisplay = 0xdab7f3f4
09-22 12:57:41.123  3445  3563 D ViewRootImpl: #3 mView = null
09-22 12:57:41.123  3445  4444 V WindowStateAnimator: Finishing drawing window Window{787e2a8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-22 12:57:41.123  3006  4385 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-22 12:57:41.123  3006  3016 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
09-22 12:57:41.123  9248  9248 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4fe06af time:238584
09-22 12:57:41.133  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7ff225ebf8
09-22 12:57:41.153  9248  9304 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-22 12:57:41.173  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:41.203  9248  9248 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9248
09-22 12:57:41.263  3445  3445 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3445 (0x0)
09-22 12:57:41.263  3445  3445 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:57:41.263  3445  3445 D PowerManagerService: mDisplayReady: false
09-22 12:57:41.263  3445  3445 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:57:41.263  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:57:41.263  3445  3445 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:57:41.263  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:57:41.263  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:41.263  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:41.263  3445  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-22 12:57:41.263  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9a503c00
09-22 12:57:41.263  3445  3563 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-22 12:57:41.263  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-22 12:57:41.263  3445  3563 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-22 12:57:41.273  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:57:41.273  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:57:41.273  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:41.273  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:57:41.273  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:41.273  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:57:41.273  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:57:41.273  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:57:41.273  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:57:41.273  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:57:41.273  3445  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:57:41.273  3445  3567 D PowerManagerService: mDisplayReady: true
09-22 12:57:41.273  3445  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:57:41.353  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:41.423  9248  9248 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-22 12:57:41.453  4016  4016 D Recents : onTaskStackChanged
09-22 12:57:41.463  4016  4016 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-22 12:57:41.473  4016  4016 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 12:57:41.523  9248  9311 D jxcore_app_log: JniHelper::setJavaVM(0xf4ff4000), pthread_self() = -644613840
,09-22 12:57:41.523  9248  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 12:57:41.523  9248  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 12:57:41.523  9248  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 12:57:41.523  9248  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 12:57:41.523  9248  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-22 12:57:41.523  9248  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7719377 added. We now have 1 listener(s)
,09-22 12:57:41.533  9248  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-22 12:57:41.533  9248  9311 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-22 12:57:41.533  9248  9311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 12:57:41.533  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:41.533  9248  9311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-22 12:57:41.533  9248  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b7cf02 added. We now have 1 listener(s)
09-22 12:57:41.533  9248  9311 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 12:57:41.533  9248  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 12:57:41.533  9248  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 12:57:41.533  9248  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 12:57:41.533  9248  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 12:57:41.533  9248  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-22 12:57:41.543  9248  9311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:57:41.543  9248  9311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E,
,09-22 12:57:41.543  9248  9311 D BluetoothAdapter: STATE_ON
,09-22 12:57:41.553  9248  9311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:57:41.553  9248  9311 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 12:57:41.553  9248  9311 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 12:57:41.553  9248  9311 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 12:57:41.553  9248  9311 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-22 12:57:41.553  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:41.563  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:41.583  9248  9248 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 12:57:41.713  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:41.833  9248  9312 W jxcore-log: Initializing JXcore engine
09-22 12:57:41.833  9248  9312 W jxcore-log: JXcore engine is ready
,09-22 12:57:41.853  5006  5006 E audit   : type=1400 msg=audit(1474541861.853:262): avc:  denied  { ioctl } for  pid=9312 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3111 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 12:57:41.853  5006  5006 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-22 12:57:41.853  5006  5006 E audit   : type=1300 msg=audit(1474541861.853:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d8d453c8 items=0 ppid=3175 pid=9312 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-22 12:57:41.853  5006  5006 E audit   : type=1327 msg=audit(1474541861.853:262): proctitle="com.test.thalitest"
09-22 12:57:41.853  5006  5006 E audit   : type=1320 msg=audit(1474541861.853:262): 
09-22 12:57:41.853  5006  5006 E audit   : type=1400 msg=audit(1474541861.853:263): avc:  denied  { ioctl } for  pid=9312 comm="Thread-160" path="socket:[38919]" dev="sockfs" ino=38919 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 12:57:41.853  5006  5006 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-22 12:57:41.853  5006  5006 E audit   : type=1300 msg=audit(1474541861.853:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d8d453c8 items=0 ppid=3175 pid=9312 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-22 12:57:41.853  5006  5006 E audit   : type=1327 msg=audit(1474541861.853:263): proctitle="com.test.thalitest"
09-22 12:57:41.853  5006  5006 E audit   : type=1320 msg=audit(1474541861.853:263): 
,09-22 12:57:41.853  9248  9312 W jxcore-log: Starting JXcore engine
,09-22 12:57:41.893  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:41.893  9248  9312 W jxcore-log: Platform android
09-22 12:57:41.893  9248  9312 W jxcore-log: 
09-22 12:57:41.893  9248  9312 W jxcore-log: Process ARCH arm
09-22 12:57:41.893  9248  9312 W jxcore-log: 
,09-22 12:57:41.963  9248  9312 I jxcore-log: JXcore Cordova bridge is ready!
09-22 12:57:41.963  9248  9312 I jxcore-log: 
09-22 12:57:41.963  9248  9312 W jxcore-log: JXcore engine is started
,09-22 12:57:41.973  9248  9311 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 12:57:41.973  9248  9248 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 12:57:42.073  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:42.253  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:42.433  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:42.523  3445  3901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-22 12:57:42.613  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:42.793  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:42.973  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:42.983  3445  5947 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-22 12:57:43.153  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:43.333  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:43.513  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:43.693  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:43.873  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:44.053  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:44.123  3445  5947 D SSRM:n  : SIOP:: AP = 310, PST = 280 (W:6), CP = 236, LCD = 1
,09-22 12:57:44.233  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:44.413  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:44.593  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:44.773  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:44.953  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:45.133  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:45.313  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:45.493  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:45.673  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:45.853  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:45.923  3445  3467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-22 12:57:45.923  3445  3467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-22 12:57:45.923  3445  3467 D BatteryService: online:4, current avg:-75, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-236
09-22 12:57:45.923  3445  3467 D BatteryService: stay LED for fully charged
09-22 12:57:45.923  3445  3445 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-22 12:57:45.923  3445  3445 I MotionRecognitionService: Plugged
,09-22 12:57:45.923  3445  3445 D MotionRecognitionService:   cableConnection= 1
09-22 12:57:45.923  3445  3445 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-22 12:57:45.923  3445  3445 D MotionRecognitionService: skip setTransmitPower. 
,09-22 12:57:45.933  3445  3858 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-22 12:57:45.933  3932  3932 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-22 12:57:45.933  3932  3932 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-22 12:57:45.933  3932  3932 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-22 12:57:45.943  5038  5038 D CommonServiceConfiguration: getStringValueSetting
,09-22 12:57:45.943  4998  4998 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-22 12:57:45.943  4998  5380 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-22 12:57:45.953  5038  5038 D BatteryMonitor: new battery level: 100
,09-22 12:57:45.963  4728  4728 D BatteryController: saveBatteryData : level[100], status[5]
,09-22 12:57:45.963  3932  3932 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-22 12:57:45.963  3932  3932 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-22 12:57:46.023  3445  5947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-22 12:57:46.033  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:46.213  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:46.393  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:46.573  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:46.753  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:46.933  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:47.113  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:47.293  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:47.473  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:47.653  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:47.833  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:47.903  9248  9312 I jxcore-log: 2016-09-22 10:57:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-22 12:57:47.903  9248  9312 I jxcore-log: 
,09-22 12:57:47.903  9248  9312 I jxcore-log: 2016-09-22 10:57:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-22 12:57:47.903  9248  9312 I jxcore-log: 
,09-22 12:57:47.923  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:57:47.923  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 12:57:47.923  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:47.933  9248  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 12:57:47.933  9248  9312 I jxcore-log: 2016-09-22 10:57:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-22 12:57:47.933  9248  9312 I jxcore-log: 
09-22 12:57:47.933  9248  9312 I jxcore-log: 2016-09-22 10:57:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-22 12:57:47.933  9248  9312 I jxcore-log: 
,09-22 12:57:48.013  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:48.083  9248  9312 I jxcore-log: Running unit tests
09-22 12:57:48.083  9248  9312 I jxcore-log: 
,09-22 12:57:48.083  9248  9312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 12:57:48.083  9248  9312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ca524 added. We now have 2 listener(s)
09-22 12:57:48.083  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-22 12:57:48.083  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 12:57:48.083  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 12:57:48.083  9248  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 12:57:48.083  9248  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86b788d added. We now have 2 listener(s)
,09-22 12:57:48.083  9248  9312 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 12:57:48.083  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 12:57:48.083  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:57:48.093  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:57:48.103  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 12:57:48.103  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.103  9248  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 12:57:48.103  9248  9312 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 12:57:48.103  9248  9312 D executeNativeTests: Running unit tests
,09-22 12:57:48.113  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:48.113  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:48.143  9248  9312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 12:57:48.143  9248  9312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9137e43 added. We now have 3 listener(s)
09-22 12:57:48.143  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-22 12:57:48.143  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 12:57:48.143  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 12:57:48.143  9248  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 12:57:48.143  9248  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 added. We now have 3 listener(s)
09-22 12:57:48.143  9248  9312 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 12:57:48.153  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 12:57:48.153  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:57:48.163  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:57:48.173  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 12:57:48.173  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.173  9248  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 12:57:48.173  9248  9312 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 12:57:48.183  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 12:57:48.183  9248  9312 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-22 12:57:48.183  9248  9312 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 12:57:48.183  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 12:57:48.183  9248  9312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 12:57:48.183  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 12:57:48.183  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 12:57:48.183  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 12:57:48.183  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:48.183  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 12:57:48.183  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9137e43 removed from the list
09-22 12:57:48.183  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 12:57:48.183  9248  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 removed from the list
,09-22 12:57:48.183  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:48.183  9248  9312 D io.jxcore.node.ConnectivityMonitor: stop
09-22 12:57:48.183  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 12:57:48.183  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:48.183  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 12:57:48.193  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 12:57:48.193  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
09-22 12:57:48.193  9248  9312 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-22 12:57:48.193  9248  9312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 12:57:48.193  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 12:57:48.193  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 12:57:48.193  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:48.193  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 12:57:48.193  9248  9312 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9137e43 not in the list
,09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 12:57:48.193  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
09-22 12:57:48.193  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 12:57:48.193  9248  9312 D io.jxcore.node.ConnectivityMonitor: stop
09-22 12:57:48.193  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:48.193  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 12:57:48.193  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 12:57:48.193  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 12:57:48.193  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 12:57:48.193  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
,09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 12:57:48.203  9248  9312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 12:57:48.203  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 12:57:48.203  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 12:57:48.203  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 12:57:48.203  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:48.203  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 12:57:48.203  9248  9312 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9137e43 not in the list
09-22 12:57:48.203  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 12:57:48.203  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
09-22 12:57:48.203  9248  9312 D io.jxcore.node.ConnectivityMonitor: stop
09-22 12:57:48.203  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:48.203  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 12:57:48.203  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:48.203  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 12:57:48.203  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 12:57:48.203  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 12:57:48.203  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 12:57:48.203  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
09-22 12:57:48.203  9248  9312 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-22 12:57:48.213  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:57:48.223  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:57:48.223  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 12:57:48.233  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.233  9248  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 12:57:48.233  9248  9312 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 12:57:48.233  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 12:57:48.233  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 12:57:48.233  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 12:57:48.233  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:57:48.233  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 12:57:48.243  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:48.243  9248  9312 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:57:48.243  9248  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 12:57:48.243  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:48.253  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.253  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.253  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.263  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 12:57:48.263  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.263  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.263  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 12:57:48.263  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 12:57:48.273  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.273  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.273  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-22 12:57:48.283  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.283  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.283  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-22 12:57:48.283  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 12:57:48.283  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-22 12:57:48.283  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 12:57:48.283  9248  9312 D BluetoothLeScanner: Start Scan
09-22 12:57:48.283  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.283  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.293  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.293  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:48.303  4998  5012 D BtGatt.GattService: registerClient() - UUID=9d7112c3-62d1-4413-8f0f-b92aeaf44898
,09-22 12:57:48.343  4998  5093 D BtGatt.GattService: onClientRegistered() - UUID=9d7112c3-62d1-4413-8f0f-b92aeaf44898, clientIf=7
,09-22 12:57:48.343  9248  9258 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-22 12:57:48.353  4998  5011 D BtGatt.GattService: start scan with filters
,09-22 12:57:48.353  4998  5011 D BtGatt.GattService: getScanSettings
,09-22 12:57:48.373  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:48.373  4998  5011 D BtGatt.GattService: Is it foreground application = true
09-22 12:57:48.373  4998  5011 D BtGatt.GattService: not a background application
,09-22 12:57:48.383  4998  5011 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-22 12:57:48.393  4998  5011 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-22 12:57:48.393  4998  5011 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-22 12:57:48.393  4998  5156 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-22 12:57:48.393  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 12:57:48.393  4998  5156 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 22, currDate: 22
09-22 12:57:48.393  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 12:57:48.393  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 12:57:48.393  4998  5142 D BtGatt.ScanManager: handling starting scan
09-22 12:57:48.393  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 12:57:48.403  4998  5142 D BtGatt.ScanManager: isFilteringSupported
09-22 12:57:48.403  4998  5142 D BluetoothAdapter: enableStandAloneBleMode=
09-22 12:57:48.403  4998  5142 D BluetoothAdapter: STATE_ON
09-22 12:57:48.403  4998  5142 D BluetoothAdapter: STATE_ON
09-22 12:57:48.413  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 12:57:48.413  4998  5142 D BluetoothAdapter: STATE_ON
09-22 12:57:48.413  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 12:57:48.413  9248  9248 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 12:57:48.413  4998  5142 D BluetoothAdapter: STATE_ON
09-22 12:57:48.413  4998  5142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@92266a8
09-22 12:57:48.413  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 12:57:48.423  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 49
09-22 12:57:48.423  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-22 12:57:48.423  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 7
09-22 12:57:48.423  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{ccee169: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:48.423  4998  5156 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24575697
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:48.433  9248  9312 I io.jxcore.node.ConnectionHelper: start: OK
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:48.433  4998  5093 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-22 12:57:48.433  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:48.433  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{cfa27ee: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-22 12:57:48.433  4998  5142 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:48.433  4998  5156 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24575697
09-22 12:57:48.433  4998  5142 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-22 12:57:48.433  4998  5142 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,09-22 12:57:48.433  4998  5142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-22 12:57:48.433  4998  5093 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-22 12:57:48.433  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:48.433  4998  5142 D BtGatt.ScanManager: Starting BLE batch scan
09-22 12:57:48.433  4998  5142 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-22 12:57:48.443  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{ec1b48f: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.443  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{317a31c: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.443  4998  5093 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-22 12:57:48.443  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-22 12:57:48.453  4998  5093 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-22 12:57:48.453  3445  4424 V AlarmManager:  remove PendingIntent] PendingIntent{86b2b25: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:48.453  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:48.453  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{64d4fa: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.453  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{f89d508: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.463  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{8c854a1: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.463  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{c9b46c6: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.473  3445  4444 V AlarmManager:  remove PendingIntent] PendingIntent{d1a687: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.473  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{d6b39b4: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.483  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{77499dd: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.483  3445  4283 V AlarmManager:  remove PendingIntent] PendingIntent{1750952: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.493  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{f182423: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:48.553  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:48.733  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:48.913  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:48.913  9248  9248 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-22 12:57:48.913  9248  9248 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 12:57:48.913  9248  9248 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 12:57:49.093  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:49.273  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:49.453  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:49.453  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:57:49.453  4998  4998 D BtGatt.ScanManager: awakened up at time 246919
,09-22 12:57:49.463  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:57:49.463  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{ea5f6d9: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:49.473  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
09-22 12:57:49.473  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:49.473  4998  5093 D BtGatt.GattService: current time is 246931211592
09-22 12:57:49.473  4998  5093 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 12:57:49.473  3445  4221 V AlarmManager:  remove PendingIntent] PendingIntent{2b6689e: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:49.473  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 12:57:49.473  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:49.473  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:49.473  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-22 12:57:49.473  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:49.473  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:49.473  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 12:57:49.473  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:49.473  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:49.473  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 12:57:49.473  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:49.473  4998  5093 D ScanRecord: first manudata for manu ID
,09-22 12:57:49.483  9248  9259 D ScanRecord: parseFromBytes
09-22 12:57:49.483  9248  9259 D ScanRecord: first manudata for manu ID
09-22 12:57:49.493  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{3bedf7f: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:49.493  9248  9259 D ScanRecord: parseFromBytes
09-22 12:57:49.493  9248  9259 D ScanRecord: first manudata for manu ID
09-22 12:57:49.493  9248  9259 D ScanRecord: parseFromBytes
09-22 12:57:49.493  9248  9259 D ScanRecord: first manudata for manu ID
09-22 12:57:49.493  9248  9259 D ScanRecord: parseFromBytes
09-22 12:57:49.493  9248  9259 D ScanRecord: first manudata for manu ID
09-22 12:57:49.503  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{b980b4c: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:49.503  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{bf62795: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:49.513  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{a1c70aa: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:49.523  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{5ebf49b: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:49.523  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{4e09038: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:49.533  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{2dea811: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:49.543  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{e28ed76: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:49.563  3445  3581 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-22 12:57:49.583  3445  3581 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-22 12:57:49.633  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:49.813  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:49.993  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:50.173  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:50.353  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:50.473  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:57:50.473  4998  4998 D BtGatt.ScanManager: awakened up at time 247938
,09-22 12:57:50.493  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:57:50.493  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{22a77e4: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:50.503  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
,09-22 12:57:50.503  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{af4b44d: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:50.503  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:50.503  4998  5093 D BtGatt.GattService: current time is 247964706245
09-22 12:57:50.503  4998  5093 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,09-22 12:57:50.503  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{9ae6b02: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:50.503  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 12:57:50.503  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:50.503  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:50.503  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-22 12:57:50.503  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:50.503  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:50.503  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:50.503  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:50.503  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:50.503  9248  9258 D ScanRecord: first manudata for manu ID
,09-22 12:57:50.513  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{96a5c13: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:50.513  3445  4221 V AlarmManager:  remove PendingIntent] PendingIntent{4092e50: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:50.523  3445  4444 V AlarmManager:  remove PendingIntent] PendingIntent{5e54849: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:50.533  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:50.533  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{1c354e: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:50.583  3150  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-22 12:57:50.713  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:50.893  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:51.073  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:51.193  3445  5983 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-22 12:57:51.253  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:51.433  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:51.503  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:57:51.513  4998  4998 D BtGatt.ScanManager: awakened up at time 248971
,09-22 12:57:51.513  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:57:51.513  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{edadf7c: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:51.513  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
09-22 12:57:51.513  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:51.513  4998  5093 D BtGatt.GattService: current time is 248979808091
,09-22 12:57:51.523  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{9312005: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:51.523  4998  5093 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 12:57:51.523  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 12:57:51.523  4998  5093 D ScanRecord: parseFromBytes
,09-22 12:57:51.523  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:51.523  9248  9259 D ScanRecord: parseFromBytes
09-22 12:57:51.523  9248  9259 D ScanRecord: first manudata for manu ID
,09-22 12:57:51.543  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{a8a585a: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:51.553  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{36f3a8b: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:51.563  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{cb47768: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:51.573  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{7a8b781: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:51.583  3445  4283 V AlarmManager:  remove PendingIntent] PendingIntent{985a026: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:51.613  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:51.793  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:51.973  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:52.153  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:52.333  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:52.513  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:52.523  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:57:52.523  4998  4998 D BtGatt.ScanManager: awakened up at time 249987
,09-22 12:57:52.523  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:57:52.533  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{20da214: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.533  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
,09-22 12:57:52.533  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:52.533  4998  5093 D BtGatt.GattService: current time is 249999832282
09-22 12:57:52.543  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{6a84abd: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.543  4998  5093 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -80, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-22 12:57:52.543  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 12:57:52.543  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:52.543  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-22 12:57:52.543  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:52.543  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-22 12:57:52.543  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:52.543  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-22 12:57:52.543  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:52.543  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 12:57:52.543  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:52.543  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-22 12:57:52.543  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:52.543  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:52.543  9248  9258 D ScanRecord: first manudata for manu ID
,09-22 12:57:52.543  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:52.543  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:52.543  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:52.543  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:52.543  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:52.543  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:52.543  9248  9258 D ScanRecord: first manudata for manu ID
,09-22 12:57:52.563  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{79b98b2: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.563  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{1727003: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.573  3445  4424 V AlarmManager:  remove PendingIntent] PendingIntent{12ccb80: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.573  3445  4444 V AlarmManager:  remove PendingIntent] PendingIntent{b13d5b9: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.583  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{8a68dfe: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.583  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{ea2095f: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.593  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{8531fac: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.593  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{a131475: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:52.693  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:52.873  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:53.053  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:53.233  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:53.413  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:53.443  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:53.443  9248  9312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 12:57:53.443  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 12:57:53.443  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 12:57:53.443  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:57:53.443  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 12:57:53.443  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 12:57:53.443  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-22 12:57:53.453  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 12:57:53.453  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 12:57:53.453  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 12:57:53.453  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-22 12:57:53.453  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:53.453  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:53.453  9248  9312 D BluetoothLeScanner: Stop Scan
,09-22 12:57:53.473  4998  5377 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-22 12:57:53.473  4998  5377 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-22 12:57:53.473  4998  5377 D BtGatt.GattService: stopScan() - queue size =1
09-22 12:57:53.473  4998  5156 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
,09-22 12:57:53.473  4998  5156 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 22, currDate: 22
09-22 12:57:53.473  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:53.473  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-22 12:57:53.473  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:53.473  4998  5012 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-22 12:57:53.473  4998  5142 D BtGatt.ScanManager: filter size is 1
09-22 12:57:53.473  4998  5156 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB,
09-22 12:57:53.473  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{1d98c0a: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:53.473  4998  5156 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-22 12:57:53.473  4998  5142 D BtGatt.ScanManager: delete FilterIndex - 3
09-22 12:57:53.473  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 12:57:53.473  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 12:57:53.473  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 12:57:53.473  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-22 12:57:53.473  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 12:57:53.473  4998  5093 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-22 12:57:53.473  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:53.473  4998  5142 D BtGatt.ScanManager: stopping BLe Batch
09-22 12:57:53.483  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 12:57:53.483  4998  5093 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-22 12:57:53.483  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:53.483  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:57:53.483  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:57:53.493  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:57:53.493  9248  9312 D BluetoothLeAdvertiser: stop advertising
09-22 12:57:53.493  9248  9312 D BluetoothLeAdvertiser: wrapper is null
,09-22 12:57:53.493  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 12:57:53.493  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 12:57:53.493  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
09-22 12:57:53.493  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-22 12:57:53.493  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:57:53.493  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{c07dc7b: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.493  4998  5093 D BtGatt.GattService: current time is 250952685974
09-22 12:57:53.493  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{6a88a98: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:53.493  4998  5093 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-22 12:57:53.493  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 12:57:53.493  4998  5093 D ScanRecord: parseFromBytes
,09-22 12:57:53.493  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:53.493  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 12:57:53.493  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:53.503  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{98d82f1: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:53.493  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:53.493  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 12:57:53.503  9248  9248 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 12:57:53.503  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 12:57:53.503  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:57:53.503  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 12:57:53.503  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 12:57:53.503  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 12:57:53.503  9248  9312 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9137e43 not in the list
09-22 12:57:53.503  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 12:57:53.503  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
09-22 12:57:53.503  9248  9312 D io.jxcore.node.ConnectivityMonitor: stop
09-22 12:57:53.503  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 12:57:53.513  9248  9248 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:57:53.513  9248  9248 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 12:57:53.513  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{c665d2d: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.513  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:53.513  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:53.513  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{5c79262: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.513  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:53.523  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 12:57:53.523  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{e5f5ff3: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.523  9248  9248 D BluetoothAdapter: STATE_ON
09-22 12:57:53.523  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:53.523  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 12:57:53.523  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 12:57:53.523  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 12:57:53.523  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 12:57:53.523  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{6ca14b0: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.533  9248  9248 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 12:57:53.533  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:57:53.533  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 12:57:53.533  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{6789f29: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.533  9248  9248 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:57:53.533  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:57:53.533  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 12:57:53.543  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{45304e5: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.543  9248  9248 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 12:57:53.543  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{f50bba: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.553  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{dc4da6b: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.553  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{11fc9c8: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.563  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{2b40a61: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:53.583  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:53.773  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:53.773  3150  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-22 12:57:53.953  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:54.043  9248  9248 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 12:57:54.133  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:54.153  3445  5947 D SSRM:n  : SIOP:: AP = 310, PST = 283 (W:6), CP = 246, CUR = -75, LCD = 1
,09-22 12:57:54.313  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:54.493  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:54.673  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:54.853  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:55.033  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:55.213  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:55.393  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:55.573  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:55.753  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:55.853  3445  4133 E Watchdog: !@Sync 8 [09-22 12:57:55.862]
,09-22 12:57:55.933  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:56.113  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:56.293  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:56.473  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:56.653  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:56.833  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:57.013  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:57.193  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:57.263  4361  4447 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-22 12:57:57.263  4361  4447 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-22 12:57:57.363  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:57.373  4361  4447 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 112ms lastUpdatedAfter : 156591ms
,09-22 12:57:57.553  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:57.733  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:57.913  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:58.093  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:58.273  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:58.453  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:58.503  9248  9312 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-22 12:57:58.513  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:57:58.523  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:57:58.533  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 12:57:58.543  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.543  9248  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 12:57:58.543  9248  9312 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 12:57:58.553  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 12:57:58.553  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 12:57:58.553  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 12:57:58.553  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:57:58.553  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 12:57:58.563  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:58.563  9248  9312 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:57:58.573  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.573  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:58.573  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.583  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.583  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.593  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 12:57:58.593  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 12:57:58.593  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 12:57:58.593  9248  9312 D BluetoothLeScanner: Start Scan
,09-22 12:57:58.593  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.593  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.603  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.603  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.603  4998  5011 D BtGatt.GattService: registerClient() - UUID=b1222805-3dc7-48ea-83a8-708d09d187ef
,09-22 12:57:58.623  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:58.653  4998  5093 D BtGatt.GattService: onClientRegistered() - UUID=b1222805-3dc7-48ea-83a8-708d09d187ef, clientIf=7
,09-22 12:57:58.653  9248  9259 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-22 12:57:58.653  4998  5012 D BtGatt.GattService: start scan with filters
,09-22 12:57:58.653  4998  5012 D BtGatt.GattService: getScanSettings
,09-22 12:57:58.663  4998  5012 D BtGatt.GattService: Is it foreground application = true
09-22 12:57:58.663  4998  5012 D BtGatt.GattService: not a background application
,09-22 12:57:58.663  4998  5012 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-22 12:57:58.673  4998  5012 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-22 12:57:58.673  4998  5012 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-22 12:57:58.673  4998  5156 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-22 12:57:58.673  4998  5156 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 22, currDate: 22
,09-22 12:57:58.673  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 12:57:58.673  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 12:57:58.673  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 12:57:58.673  4998  5142 D BtGatt.ScanManager: handling starting scan
09-22 12:57:58.673  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 12:57:58.683  4998  5142 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.683  4998  5142 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.693  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{ca409e0: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.693  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 50
,09-22 12:57:58.693  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-22 12:57:58.693  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 12:57:58.693  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 12:57:58.703  3445  4444 V AlarmManager:  remove PendingIntent] PendingIntent{1aa499: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.693  9248  9248 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 12:57:58.693  4998  5093 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-22 12:57:58.693  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.703  4998  5142 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
09-22 12:57:58.703  4998  5142 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-22 12:57:58.703  4998  5142 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-22 12:57:58.703  4998  5142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-22 12:57:58.703  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 12:57:58.703  4998  5093 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-22 12:57:58.703  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 8
,09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24575697
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-22 12:57:58.703  4998  5142 D BtGatt.ScanManager: Starting BLE batch scan
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:58.703  4998  5142 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-22 12:57:58.713  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{d4e35e: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:58.703  4998  5156 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24575697
09-22 12:57:58.713  9248  9312 I io.jxcore.node.ConnectionHelper: start: OK
09-22 12:57:58.713  4998  5093 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-22 12:57:58.713  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.713  4998  5093 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-22 12:57:58.713  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.713  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{9fa33f: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.713  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.723  9248  9312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 12:57:58.723  9248  9312 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 12:57:58.723  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 12:57:58.723  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 12:57:58.723  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 12:57:58.723  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 12:57:58.723  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 12:57:58.723  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 12:57:58.723  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 12:57:58.723  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 12:57:58.723  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 12:57:58.723  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 12:57:58.723  3445  4283 V AlarmManager:  remove PendingIntent] PendingIntent{96fe40c: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.723  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.723  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:57:58.723  9248  9312 D BluetoothLeScanner: Stop Scan
,09-22 12:57:58.733  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{967f155: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.733  4998  5465 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-22 12:57:58.733  4998  5465 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-22 12:57:58.733  4998  5465 D BtGatt.GattService: stopScan() - queue size =1
,09-22 12:57:58.733  4998  5156 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-22 12:57:58.733  4998  5156 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 22, currDate: 22
09-22 12:57:58.733  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:58.733  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-22 12:57:58.733  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
,09-22 12:57:58.733  4998  5156 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-22 12:57:58.733  4998  5156 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-22 12:57:58.733  4998  5142 D BtGatt.ScanManager: filter size is 1
09-22 12:57:58.733  4998  5142 D BtGatt.ScanManager: delete FilterIndex - 4
09-22 12:57:58.733  4998  5011 D BtGatt.GattService: unregisterClient() - clientIf=7
09-22 12:57:58.733  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 12:57:58.733  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 12:57:58.733  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 12:57:58.733  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 12:57:58.733  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 12:57:58.733  4998  5093 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
,09-22 12:57:58.733  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.733  4998  5142 D BtGatt.ScanManager: stopping BLe Batch
09-22 12:57:58.733  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{987d76a: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.733  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 12:57:58.733  4998  5093 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-22 12:57:58.743  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-22 12:57:58.743  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-22 12:57:58.743  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:57:58.743  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-22 12:57:58.743  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.743  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:57:58.743  9248  9312 D BluetoothLeAdvertiser: stop advertising
09-22 12:57:58.743  9248  9312 D BluetoothLeAdvertiser: wrapper is null
09-22 12:57:58.743  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{875345b: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:58.743  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 12:57:58.743  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-22 12:57:58.743  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:57:58.743  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 12:57:58.743  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{93d34f8: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.743  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{5034dd1: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.743  9248  9248 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 12:57:58.743  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 12:57:58.743  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:57:58.743  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 12:57:58.743  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 12:57:58.743  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 12:57:58.743  9248  9312 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9137e43 not in the list
09-22 12:57:58.743  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 12:57:58.743  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
09-22 12:57:58.743  9248  9312 D io.jxcore.node.ConnectivityMonitor: stop
09-22 12:57:58.743  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 12:57:58.753  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{1df60d: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.753  9248  9248 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:57:58.753  9248  9248 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 12:57:58.753  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.753  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{8c7e9c2: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.763  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.763  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.763  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{463d3d3: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.763  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 12:57:58.763  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.763  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.763  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 12:57:58.763  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{13dab10: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.763  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 12:57:58.763  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:57:58.763  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 12:57:58.773  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 12:57:58.773  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 12:57:58.773  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{fc0e609: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.773  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 12:57:58.773  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.773  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.773  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{f2ee00e: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.773  9248  9312 D BluetoothLeAdvertiser: stop advertising
09-22 12:57:58.773  9248  9312 D BluetoothLeAdvertiser: wrapper is null
09-22 12:57:58.773  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 12:57:58.773  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 12:57:58.773  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.783  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:57:58.783  9248  9312 D BluetoothLeScanner: could not find callback wrapper
09-22 12:57:58.783  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 12:57:58.783  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 12:57:58.783  9248  9248 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 12:57:58.783  9248  9312 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8975cc0 not in the list
09-22 12:57:58.783  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:57:58.783  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 12:57:58.783  9248  9312 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-22 12:57:58.783  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 12:57:58.783  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{a224d41: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.793  9248  9248 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:57:58.793  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:57:58.793  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{56ae2e6: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.793  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 12:57:58.793  9248  9248 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 12:57:58.793  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.793  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{388e027: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 12:57:58.803  9248  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 12:57:58.803  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{abd82d4: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.803  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.803  9248  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 12:57:58.803  9248  9312 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 12:57:58.803  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 12:57:58.803  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{4857c7d: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.803  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 12:57:58.803  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 12:57:58.803  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:57:58.803  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 12:57:58.803  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:58.813  9248  9312 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:57:58.813  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:57:58.813  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{cf26379: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.813  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.813  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 12:57:58.823  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.823  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{61968be: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.823  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.823  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 12:57:58.823  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 12:57:58.823  9248  9312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 12:57:58.823  9248  9312 D BluetoothLeScanner: Start Scan
09-22 12:57:58.823  9248  9248 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 12:57:58.823  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{7afad1f: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.823  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.823  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.833  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.833  3445  4424 V AlarmManager:  remove PendingIntent] PendingIntent{186586c: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.833  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.833  4998  5012 D BtGatt.GattService: registerClient() - UUID=11acda91-96d4-49bc-b0c1-1e563c5dc361
,09-22 12:57:58.833  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{4acbe35: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.873  4998  5093 D BtGatt.GattService: onClientRegistered() - UUID=11acda91-96d4-49bc-b0c1-1e563c5dc361, clientIf=7
,09-22 12:57:58.873  9248  9259 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-22 12:57:58.873  4998  5377 D BtGatt.GattService: start scan with filters
,09-22 12:57:58.873  4998  5377 D BtGatt.GattService: getScanSettings
,09-22 12:57:58.883  4998  5377 D BtGatt.GattService: Is it foreground application = true
,09-22 12:57:58.883  4998  5377 D BtGatt.GattService: not a background application
,09-22 12:57:58.883  4998  5377 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-22 12:57:58.883  4998  5377 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-22 12:57:58.883  4998  5377 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-22 12:57:58.883  4998  5156 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-22 12:57:58.883  4998  5156 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 22, currDate: 22
09-22 12:57:58.883  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 12:57:58.883  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 12:57:58.883  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 12:57:58.883  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 12:57:58.883  4998  5142 D BtGatt.ScanManager: handling starting scan
09-22 12:57:58.893  4998  5142 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.893  4998  5142 D BluetoothAdapter: STATE_ON
,09-22 12:57:58.893  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 12:57:58.893  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 12:57:58.893  9248  9248 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 12:57:58.893  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{17f52ca: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.893  4998  5093 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-22 12:57:58.893  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.893  4998  5142 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
09-22 12:57:58.903  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{abfc3b: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:57:58.893  4998  5142 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-22 12:57:58.893  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 12:57:58.893  4998  5142 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-22 12:57:58.893  4998  5142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-22 12:57:58.893  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 51
09-22 12:57:58.893  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-22 12:57:58.893  4998  5093 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-22 12:57:58.893  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.893  4998  5142 D BtGatt.ScanManager: Starting BLE batch scan
09-22 12:57:58.893  4998  5142 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-22 12:57:58.903  4998  5093 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-22 12:57:58.903  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 9
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24575697
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-22 12:57:58.903  4998  5093 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-22 12:57:58.903  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:58.903  3445  4283 V AlarmManager:  remove PendingIntent] PendingIntent{b68f58: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:58.903  9248  9312 I io.jxcore.node.ConnectionHelper: start: OK
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-22 12:57:58.903  4998  5156 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24575697
,09-22 12:57:58.903  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{37808b1: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.913  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{6a7d196: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.913  3445  4444 V AlarmManager:  remove PendingIntent] PendingIntent{7542117: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.913  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{fb14904: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.923  3445  4424 V AlarmManager:  remove PendingIntent] PendingIntent{fd37eed: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.923  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{6077122: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.923  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{7efb7b3: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.933  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{27bf170: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.933  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{ef61ce9: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.933  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{cf7d6e: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.943  3445  4221 V AlarmManager:  remove PendingIntent] PendingIntent{1a41c0f: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.943  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{606b49c: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:58.983  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:59.173  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:59.353  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:59.393  9248  9248 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-22 12:57:59.393  9248  9248 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 12:57:59.393  9248  9248 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 12:57:59.523  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:59.713  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:59.893  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:57:59.903  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:57:59.913  4998  4998 D BtGatt.ScanManager: awakened up at time 257373
,09-22 12:57:59.913  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:57:59.913  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{7fa027a: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.923  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
09-22 12:57:59.923  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:57:59.923  4998  5093 D BtGatt.GattService: current time is 257386036892
09-22 12:57:59.923  4998  5093 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -78, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
09-22 12:57:59.923  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{6906a2b: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:57:59.923  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-22 12:57:59.923  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:59.923  4998  5093 D ScanRecord: first manudata for manu ID
,09-22 12:57:59.923  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 12:57:59.923  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:59.923  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:59.923  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-22 12:57:59.923  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:59.923  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:59.933  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 12:57:59.933  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:59.933  4998  5093 D ScanRecord: first manudata for manu ID
,09-22 12:57:59.933  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-22 12:57:59.933  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:59.933  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:57:59.933  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-22 12:57:59.933  4998  5093 D ScanRecord: parseFromBytes
09-22 12:57:59.933  4998  5093 D ScanRecord: first manudata for manu ID
,09-22 12:57:59.933  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:59.933  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:59.933  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:59.933  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:59.933  9248  9258 D ScanRecord: parseFromBytes
,09-22 12:57:59.933  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:59.933  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:59.933  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:59.933  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:59.933  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:57:59.933  9248  9258 D ScanRecord: parseFromBytes
09-22 12:57:59.933  9248  9258 D ScanRecord: first manudata for manu ID
,09-22 12:57:59.943  3445  4424 V AlarmManager:  remove PendingIntent] PendingIntent{4187e88: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.943  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{a2b8021: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.953  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{15cc46: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.953  3445  4444 V AlarmManager:  remove PendingIntent] PendingIntent{1a97e07: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.963  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{9fafb34: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.963  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{69efd5d: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.973  3445  4221 V AlarmManager:  remove PendingIntent] PendingIntent{5d266d2: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.973  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{e55f3a3: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:57:59.993  3445  3812 V AlarmManager: Expired Alarm result :8
,09-22 12:58:00.073  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:00.253  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:00.433  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:00.603  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:00.713  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:58:00.713  3445  3812 V AlarmManager: Send whitelist package alarm :PendingIntent{fc64dd7: PendingIntentRecord{eada3b6 com.samsung.android.app.aodservice broadcastIntent}}
,09-22 12:58:00.723  3932  3932 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-22 12:58:00.723  3932  3932 D KeyguardUpdateMonitor: handleTimeUpdate
,09-22 12:58:00.733  3932  3932 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-22 12:58:00.793  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:00.803  3932  3932 D DateView: received broadcast android.intent.action.TIME_TICK
,09-22 12:58:00.833  4636  4636 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-22 12:58:00.843  4636  4636 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-22 12:58:00.853  4728  4728 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-22 12:58:00.853  4728  4728 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-22 12:58:00.853  3445  4281 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-22 12:58:00.853  3445  4281 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,09-22 12:58:00.853  3445  4281 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-22 12:58:00.853  3445  4281 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-22 12:58:00.853  3165  3165 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-22 12:58:00.863  3445  4281 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-22 12:58:00.863  3445  4281 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-22 12:58:00.863  3445  4281 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-22 12:58:00.863  4728  4728 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@c2f656c, service=Device Physical Context Monitor
09-22 12:58:00.863  4728  4728 I AlpmModeManager: startAlpmMode : state  = BLANK
09-22 12:58:00.863  4728  4728 D DefaultClockView: Window showed. Time views updating
,09-22 12:58:00.863  3445  4303 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3445
09-22 12:58:00.863  3445  4303 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:58:00.863  3445  4303 D PowerManagerService: mDisplayReady: false
,09-22 12:58:00.863  3445  4303 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:58:00.863  3445  4303 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:58:00.863  4728  4728 D AODUpdatePositionController: updatePosition: direction[2] updatePosition: X[37] Y[475] NewPositionTimer[56]
09-22 12:58:00.863  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:58:00.863  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9a503c00
09-22 12:58:00.863  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:58:00.863  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-22 12:58:00.863  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:58:00.863  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:58:00.863  3445  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,09-22 12:58:00.863  3445  3563 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-22 12:58:00.863  3445  3563 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-22 12:58:00.873  4728  4728 D DefaultClockView: LocalTime Pattern : HH:mm
,09-22 12:58:00.873  4728  4728 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 12:58 time02: null ampm: null
,09-22 12:58:00.883  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-22 12:58:00.883  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 12:58:00.883  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:58:00.883  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:58:00.883  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:58:00.883  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:58:00.883  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 12:58:00.883  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-22 12:58:00.883  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:58:00.883  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:58:00.883  3165  3212 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
09-22 12:58:00.883  3445  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-22 12:58:00.883  3445  3815 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
09-22 12:58:00.883  3445  3567 D PowerManagerService: mDisplayReady: true
09-22 12:58:00.883  3445  3814 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 58, 0,
,09-22 12:58:00.883  3445  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 12:58:00.883  3445  3814 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 58, 0
,09-22 12:58:00.893  3165  3213 D Sensorhubs: sendContextData: -63, 14, 10, 58, 0
,09-22 12:58:00.893  3445  3814 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-22 12:58:00.893  3445  3814 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-22 12:58:00.893  3445  3814 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-22 12:58:00.893  4728  4728 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-22 12:58:00.893  3445  3814 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
09-22 12:58:00.893  4728  4728 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
09-22 12:58:00.893  3445  3814 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,09-22 12:58:00.893  3445  3817 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-22 12:58:00.893  4728  4728 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:czw., 22 wrz 12:58
09-22 12:58:00.893  4728  4728 I AODService.ClockTimer: startAlarm : TICK
09-22 12:58:00.903  3445  4300 V AlarmManager: Add whitelist package alarm :PendingIntent{f4c1e1e: PendingIntentRecord{eada3b6 com.samsung.android.app.aodservice broadcastIntent}}
,09-22 12:58:00.903  4728  4728 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,09-22 12:58:00.903  4728  4728 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,09-22 12:58:00.903  3445  4283 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
,09-22 12:58:00.903  3445  4283 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-22 12:58:00.913  3445  3964 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3445
,09-22 12:58:00.913  4728  4728 D DefaultClockView: RootView invalidate()
,09-22 12:58:00.913  3445  4846 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3445
09-22 12:58:00.913  4728  4728 I AODService: onSContextChanged: AODScreenShown state is already true
,09-22 12:58:00.923  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:58:00.933  4998  4998 D BtGatt.ScanManager: awakened up at time 258389
,09-22 12:58:00.933  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:58:00.933  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{f2e7ccc: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:00.933  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
09-22 12:58:00.943  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:58:00.943  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{2997b15: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:00.943  4998  5093 D BtGatt.GattService: current time is 258400235853
,09-22 12:58:00.943  4998  5093 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -79, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -88, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-22 12:58:00.943  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{617fe2a: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:58:00.943  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-22 12:58:00.943  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:00.943  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:00.943  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 12:58:00.943  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:00.943  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:00.943  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-22 12:58:00.943  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:00.943  4998  5093 D ScanRecord: first manudata for manu ID
,09-22 12:58:00.943  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:00.943  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:58:00.943  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:00.943  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:58:00.943  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:00.943  9248  9258 D ScanRecord: first manudata for manu ID
,09-22 12:58:00.943  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{624341b: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:00.953  3445  4444 V AlarmManager:  remove PendingIntent] PendingIntent{d2c99b8: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:00.953  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{f23b391: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:00.953  3445  4408 V AlarmManager:  remove PendingIntent] PendingIntent{60fd2f6: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:00.963  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:01.063  3445  3445 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3445 (0x0)
,09-22 12:58:01.063  3445  3445 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 12:58:01.063  3445  3445 D PowerManagerService: mDisplayReady: false
09-22 12:58:01.063  3445  3445 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 12:58:01.063  3445  3445 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 12:58:01.063  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:58:01.063  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:58:01.063  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9a503c00
09-22 12:58:01.063  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:58:01.063  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-22 12:58:01.063  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-22 12:58:01.063  3445  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-22 12:58:01.063  3445  3563 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-22 12:58:01.063  3445  3563 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-22 12:58:01.093  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:58:01.093  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:58:01.093  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:58:01.093  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 12:58:01.093  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:58:01.093  3445  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 12:58:01.093  3445  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 12:58:01.093  3445  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 12:58:01.093  3445  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 12:58:01.093  3445  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 12:58:01.093  3445  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 12:58:01.093  3445  3567 D PowerManagerService: mDisplayReady: true
09-22 12:58:01.093  3445  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-22 12:58:01.143  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:01.333  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:01.503  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:01.683  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:01.863  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:01.943  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:58:01.943  4998  4998 D BtGatt.ScanManager: awakened up at time 259408
,09-22 12:58:01.953  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:58:01.953  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{ed9964: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:01.953  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
,09-22 12:58:01.953  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:58:01.953  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{13ef7cd: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:58:01.953  4998  5093 D BtGatt.GattService: current time is 259418676776
09-22 12:58:01.953  4998  5093 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 12:58:01.963  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-22 12:58:01.963  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:01.963  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 12:58:01.963  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:01.963  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-22 12:58:01.963  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:01.963  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-22 12:58:01.963  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:01.963  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 12:58:01.963  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:01.963  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:01.963  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:01.963  9248  9258 D, ScanRecord: first manudata for manu ID
09-22 12:58:01.963  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:01.963  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:01.963  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:58:01.963  9248  9258 D ScanRecord: parseFromBytes
09-22 12:58:01.963  9248  9258 D ScanRecord: first manudata for manu ID
09-22 12:58:01.973  3445  4221 V AlarmManager:  remove PendingIntent] PendingIntent{cde2882: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:01.983  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{17b0b93: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:01.983  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{59ce7d0: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:01.993  3445  4283 V AlarmManager:  remove PendingIntent] PendingIntent{d5043c9: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:02.003  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{64a4ace: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:02.003  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{9c0cdef: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:02.013  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{bb0b0fc: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:02.013  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{f105385: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:02.043  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:02.223  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:02.403  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:02.583  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:02.763  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:02.943  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:02.963  3445  3812 V AlarmManager: Expired Alarm result :4
,09-22 12:58:02.963  4998  4998 D BtGatt.ScanManager: awakened up at time 260426
,09-22 12:58:02.963  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:58:02.973  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{7f65a0b: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:02.983  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
,09-22 12:58:02.983  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:58:02.983  4998  5093 D BtGatt.GattService: current time is 260446665890
09-22 12:58:02.983  4998  5093 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-22 12:58:02.983  3445  3964 V AlarmManager:  remove PendingIntent] PendingIntent{2d5e0e8: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:58:02.983  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-22 12:58:02.983  4998  5093 D ScanRecord: parseFromBytes
,09-22 12:58:02.983  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:02.983  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 12:58:02.983  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:02.983  4998  5093 D ScanRecord: first manudata for manu ID
,09-22 12:58:02.983  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 12:58:02.983  4998  5093 D ScanRecord: parseFromBytes
09-22 12:58:02.993  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:02.993  4998  5093 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-22 12:58:02.993  4998  5093 D ScanRecord: parseFromBytes
,09-22 12:58:02.993  4998  5093 D ScanRecord: first manudata for manu ID
09-22 12:58:02.993  9248  9259 D ScanRecord: parseFromBytes
09-22 12:58:02.993  9248  9259 D ScanRecord: first manudata for manu ID
09-22 12:58:02.993  9248  9259 D ScanRecord: parseFromBytes
09-22 12:58:02.993  9248  9259 D ScanRecord: first manudata for manu ID
09-22 12:58:02.993  9248  9259 D ScanRecord: parseFromBytes
09-22 12:58:02.993  9248  9259 D ScanRecord: first manudata for manu ID
,09-22 12:58:02.993  9248  9259 D ScanRecord: parseFromBytes
09-22 12:58:02.993  9248  9259 D ScanRecord: first manudata for manu ID
09-22 12:58:02.993  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{b07a301: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.003  3445  4300 V AlarmManager:  remove PendingIntent] PendingIntent{9b0e5a6: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.003  3445  4281 V AlarmManager:  remove PendingIntent] PendingIntent{aae8be7: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.013  3445  4283 V AlarmManager:  remove PendingIntent] PendingIntent{69c2394: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.013  3445  3962 V AlarmManager:  remove PendingIntent] PendingIntent{bca6e3d: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.023  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{2f5b632: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.033  3445  3467 V AlarmManager:  remove PendingIntent] PendingIntent{ccdff83: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.033  3445  4317 V AlarmManager:  remove PendingIntent] PendingIntent{9e1e500: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.123  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:03.303  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:03.483  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:03.663  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:03.843  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:03.903  9248  9312 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 12:58:03.903  9248  9312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 12:58:03.903  9248  9312 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 12:58:03.903  9248  9312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 12:58:03.903  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 12:58:03.903  9248  9312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 12:58:03.903  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 12:58:03.903  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 12:58:03.903  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 12:58:03.903  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 12:58:03.903  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-22 12:58:03.913  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:58:03.913  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:58:03.913  9248  9312 D BluetoothLeScanner: Stop Scan
,09-22 12:58:03.923  4998  5377 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-22 12:58:03.923  4998  5377 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-22 12:58:03.923  4998  5377 D BtGatt.GattService: stopScan() - queue size =1
09-22 12:58:03.923  4998  5156 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-22 12:58:03.923  4998  5156 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 22, currDate: 22
,09-22 12:58:03.923  4998  5156 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 1
09-22 12:58:03.923  4998  5142 D BtGatt.ScanManager: filter size is 1
09-22 12:58:03.923  4998  5142 D BtGatt.ScanManager: delete FilterIndex - 5
09-22 12:58:03.933  3445  4221 V AlarmManager:  remove PendingIntent] PendingIntent{6f4b139: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:03.923  4998  5011 D BtGatt.GattService: unregisterClient() - clientIf=7
09-22 12:58:03.933  4998  5093 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-22 12:58:03.933  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-22 12:58:03.933  4998  5142 D BtGatt.ScanManager: stopping BLe Batch
09-22 12:58:03.933  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 12:58:03.933  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-22 12:58:03.933  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-22 12:58:03.933  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 12:58:03.933  9248  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 12:58:03.933  4998  5093 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-22 12:58:03.933  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:58:03.933  4998  5142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-22 12:58:03.943  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 12:58:03.943  4998  5093 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-22 12:58:03.943  4998  5093 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-22 12:58:03.943  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 1
09-22 12:58:03.943  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{f45037e: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.943  9248  9312 D BluetoothAdapter: STATE_ON
,09-22 12:58:03.943  9248  9312 D BluetoothAdapter: STATE_ON
09-22 12:58:03.943  9248  9312 D BluetoothLeAdvertiser: stop advertising
09-22 12:58:03.943  9248  9312 D BluetoothLeAdvertiser: wrapper is null
,09-22 12:58:03.943  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 12:58:03.953  3445  3466 V AlarmManager:  remove PendingIntent] PendingIntent{d00512c: PendingIntentRecord{72f0aab com.android.bluetooth broadcastIntent}}
09-22 12:58:03.943  9248  9312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 12:58:03.953  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{8e710df: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:03.943  9248  9312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:58:03.953  9248  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 12:58:03.953  4998  5156 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 1
,09-22 12:58:03.953  4998  5156 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-22 12:58:03.953  4998  5156 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-22 12:58:03.953  9248  9248 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 12:58:03.953  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:58:03.953  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 12:58:03.963  9248  9248 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:58:03.963  3445  4283 V AlarmManager:  remove PendingIntent] PendingIntent{ab75418: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:03.963  9248  9248 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 12:58:03.963  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:58:03.963  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{e3e4e71: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
09-22 12:58:03.963  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:58:03.973  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:58:03.973  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{8d40456: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.973  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 12:58:03.973  9248  9248 D BluetoothAdapter: STATE_ON
,09-22 12:58:03.973  9248  9248 D BluetoothAdapter: STATE_ON
09-22 12:58:03.973  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 12:58:03.973  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 12:58:03.973  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:58:03.983  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 12:58:03.983  3445  4303 V AlarmManager:  remove PendingIntent] PendingIntent{c1c3cd7: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.983  9248  9248 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 12:58:03.983  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 12:58:03.983  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 12:58:03.983  3445  4846 V AlarmManager:  remove PendingIntent] PendingIntent{57dcf73: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:03.993  9248  9248 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 12:58:03.993  9248  9248 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 12:58:03.993  9248  9248 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 12:58:03.993  3445  3972 V AlarmManager:  remove PendingIntent] PendingIntent{1b88e30: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:04.003  9248  9248 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 12:58:04.003  3445  4845 V AlarmManager:  remove PendingIntent] PendingIntent{75aa9: PendingIntentRecord{146c510 com.android.bluetooth broadcastIntent}}
,09-22 12:58:04.023  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:04.173  3445  5947 D SSRM:n  : SIOP:: AP = 290, PST = 286 (W:14), CP = 244, CUR = -75, LCD = 1
,09-22 12:58:04.203  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:04.383  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:04.503  9248  9248 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 12:58:04.503  9248  9248 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 12:58:04.503  9248  9248 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 12:58:04.563  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:04.743  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:04.923  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 12:58:05.103  3445  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
