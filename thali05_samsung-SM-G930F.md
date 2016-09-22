#### Test 85046911aad23fc_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-22 10:50:11.842  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:12.022  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:12.202  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:12.382  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:12.502  9453  9453 I FIPS_bssl: FIPS approved mode (1) | 9453 | app_process
09-22 10:50:12.502  9453  9453 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 10:50:12.502  9453  9453 D AndroidRuntime: CheckJNI is OFF
09-22 10:50:12.502  9453  9453 D AndroidRuntime: readGMSProperty: start
09-22 10:50:12.502  9453  9453 D AndroidRuntime: readGMSProperty: already setted!!
09-22 10:50:12.502  9453  9453 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-22 10:50:12.502  9453  9453 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-22 10:50:12.502  9453  9453 D AndroidRuntime: readGMSProperty: end
09-22 10:50:12.502  9453  9453 D AndroidRuntime: addProductProperty: start
09-22 10:50:12.522  9453  9453 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 10:50:12.542  9453  9453 I Radio-JNI: register_android_hardware_Radio DONE
09-22 10:50:12.552  9453  9453 E AffinityControl: AffinityControl: registerfunction enter
09-22 10:50:12.562  9453  9453 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-22 10:50:12.562  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:12.582  3443  4291 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-22 10:50:12.592  3443  4291 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-22 10:50:12.612  3443  4291 D ResourcesManager: For user 0 new overlays fetched Null
09-22 10:50:12.612  3443  4291 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 10:50:12.612  3443  4291 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-22 10:50:12.612  3443  4291 D ActivityManager: mDVFSHelper.acquire()
09-22 10:50:12.622  3443  4291 V WindowManager: addAppToken: AppWindowToken{d097bfcee token=Token{78eea69 ActivityRecord{ce984f0 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-22 10:50:12.622  3443  3561 I InjectionManager: Inside getClassLibPath caller 
09-22 10:50:12.632  3443  3561 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 10:50:12.632  3443  3561 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2e2bbc6 V.E...... R.....ID 0,0-0,0}
09-22 10:50:12.642  9462  9462 E Zygote  : v2
09-22 10:50:12.642  9462  9462 I libpersona: KNOX_SDCARD checking this for 10171
09-22 10:50:12.642  9462  9462 I libpersona: KNOX_SDCARD not a persona
09-22 10:50:12.642  9462  9462 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-22 10:50:12.642  3443  3561 W WindowManager: Failed looking up window
09-22 10:50:12.642  3443  3561 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@e47787 does not exist
09-22 10:50:12.642  3443  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 10:50:12.642  3443  3561 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 10:50:12.642  3443  3561 D ISSUE_DEBUG: InputChannelName : 71c36b4 Starting com.test.thalitest
09-22 10:50:12.642  3443  4291 I ActivityManager: Start proc 9462:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-22 10:50:12.642  9462  9462 E Zygote  : accessInfo : 0
09-22 10:50:12.642  9462  9462 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-22 10:50:12.642  3443  4291 D InputDispatcher: Focused application set to: xxxx
09-22 10:50:12.642  9453  9453 D AndroidRuntime: Shutting down VM
09-22 10:50:12.642  3443  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-22 10:50:12.652  3005  3005 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-22 10:50:12.662  9462  9462 D TimaKeyStoreProvider: TimaSignature is unavailable
09-22 10:50:12.662  9462  9462 D ActivityThread: Added TimaKeyStore provider
09-22 10:50:12.672  6341  6341 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 10:50:12.682  3443  3982 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443
09-22 10:50:12.682  3443  3982 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 10:50:12.682  3443  3982 D PowerManagerService: mDisplayReady: false
09-22 10:50:12.682  3443  3982 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 10:50:12.682  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 10:50:12.682  6341  6341 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 10:50:12.682  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 10:50:12.682  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f85e83c00
09-22 10:50:12.682  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:12.682  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-22 10:50:12.682  3443  3982 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 10:50:12.682  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:12.682  3443  3581 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-22 10:50:12.682  3443  3975 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443
09-22 10:50:12.692  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 10:50:12.692  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 10:50:12.692  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 10:50:12.692  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 10:50:12.692  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:12.692  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:12.692  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 10:50:12.692  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 10:50:12.692  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:12.692  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:12.692  3443  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 10:50:12.692  3443  3567 D PowerManagerService: mDisplayReady: true
09-22 10:50:12.692  3443  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 10:50:12.702  3443  4847 D ActivityManager:  Launching com.test.thalitest, updated priority
09-22 10:50:12.712  4296  4296 V ActivityThread: updateVisibility : ActivityRecord{583ed31 token=android.os.BinderProxy@26f3227 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-22 10:50:12.722  3005  4464 D libEGL  : eglTerminate EGLDisplay = 0x7f7e4ffe78
09-22 10:50:12.722  3005  4464 D libEGL  : eglTerminate EGLDisplay = 0x7f7e4ffe78
09-22 10:50:12.722  3443  3443 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-22 10:50:12.722  3443  3532 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-22 10:50:12.732  3005  4332 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-22 10:50:12.732  3005  4464 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-22 10:50:12.732  3443  4834 V WindowStateAnimator: Finishing drawing window Window{65ec72e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-22 10:50:12.732  4296  4296 D Launcher: onTrimMemory. Level: 20
09-22 10:50:12.742  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:12.742  3443  4308 V WindowStateAnimator: Finishing drawing window Window{ba9745c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-22 10:50:12.742  6341  6341 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 10:50:12.742  6341  6341 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-22 10:50:12.742  6341  6341 V ActivityThread: updateVisibility : ActivityRecord{1f1a5db token=android.os.BinderProxy@97c123c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-22 10:50:12.752  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fcdc99a18
09-22 10:50:12.752  3005  3014 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-22 10:50:12.752  3005  4332 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-22 10:50:12.762  3005  4332 D libEGL  : eglTerminate EGLDisplay = 0x7f7e5fee78
09-22 10:50:12.762  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fcdc99a18
09-22 10:50:12.762  3005  3016 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-22 10:50:12.762  3005  3066 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-22 10:50:12.782  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fcdc99a18
09-22 10:50:12.832  3443  3443 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443 (0x0)
09-22 10:50:12.832  3443  3443 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3443 (0x0)
09-22 10:50:12.832  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 10:50:12.832  3443  3443 D PowerManagerService: mDisplayReady: false
09-22 10:50:12.832  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 10:50:12.832  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 10:50:12.832  3443  3443 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 10:50:12.832  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 10:50:12.832  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:12.832  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:12.832  3443  3581 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-22 10:50:12.842  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f85e83c00
09-22 10:50:12.842  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-22 10:50:12.842  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 10:50:12.842  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 10:50:12.842  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 10:50:12.842  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:12.842  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 10:50:12.842  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:12.842  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 10:50:12.842  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 10:50:12.842  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:12.842  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:12.842  3443  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 10:50:12.842  3443  3567 D PowerManagerService: mDisplayReady: true
09-22 10:50:12.842  3443  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-22 10:50:12.892  3443  6274 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:14), CP = 229, CUR = 9, LCD = 1
09-22 10:50:12.922  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:13.052  3443  4847 I WindowManager: Screenshot max retries 4 of Token{78eea69 ActivityRecord{ce984f0 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{71c36b4 u0 d0 Starting com.test.thalitest} drawState=1
09-22 10:50:13.052  3443  3561 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 10:50:13.052  3443  3443 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 10:50:13.052  3443  3561 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-22 10:50:13.062  3443  3443 I KnoxTimeoutHandler: SD activityfalse
09-22 10:50:13.062  3443  6274 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 10:50:13.062  3443  6274 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 10:50:13.072  3443  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-22 10:50:13.082  9462  9462 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 10:50:13.082  3443  4293 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-22 10:50:13.092  9462  9462 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-22 10:50:13.102  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:13.102  3443  3561 V WindowStateAnimator: Finishing drawing window Window{71c36b4 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-22 10:50:13.102  9462  9462 D ResourcesManager: For user 0 new overlays fetched Null
09-22 10:50:13.102  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fcdc998f8
09-22 10:50:13.102  3443  3561 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 10:50:13.112  3443  3443 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-22 10:50:13.112  3443  3561 D ActivityManager: mDVFSHelper.release()
09-22 10:50:13.112  3443  3561 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{105efb u0 com.samsung.android.MtpApplication/.USBConnection t3} time:212651
09-22 10:50:13.112  3443  6274 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-22 10:50:13.112  3443  3443 I KnoxTimeoutHandler: SD activityfalse
09-22 10:50:13.112  3443  6274 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 10:50:13.122  9462  9462 I InjectionManager: Inside getClassLibPath caller 
09-22 10:50:13.122  3443  6274 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-22 10:50:13.122  3443  6274 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 10:50:13.122  3443  6274 D GameManagerService: identifyGamePackage. com.test.thalitest
09-22 10:50:13.132  9462  9462 D InjectionManager: InjectionManager
09-22 10:50:13.132  9462  9462 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-22 10:50:13.132  9462  9462 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-22 10:50:13.132  9462  9462 I InjectionManager: featureStore :{}
09-22 10:50:13.142  9462  9462 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 10:50:13.142  9462  9462 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-22 10:50:13.142  9462  9462 D RelationGraph: garbageCollect()
09-22 10:50:13.152  9462  9462 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-22 10:50:13.182  9462  9462 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-22 10:50:13.212  9462  9462 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-22 10:50:13.212  9462  9462 D ResourcesManager: For user 0 new overlays fetched Null
09-22 10:50:13.212  9462  9462 I InjectionManager: Inside getClassLibPath caller 
09-22 10:50:13.222  9462  9462 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-22 10:50:13.272  9462  9462 I cr_LibraryLoader: Time to load native libraries: 29 ms (timestamps 2780-2809)
09-22 10:50:13.272  9462  9462 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-22 10:50:13.282  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:13.322  3443  3879 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-22 10:50:13.332  9462  9478 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-22 10:50:13.362  9462  9462 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {58d353f}
09-22 10:50:13.362  9462  9462 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-22 10:50:13.382  9462  9462 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-22 10:50:13.412  9462  9462 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-22 10:50:13.422  3443  3879 I MdnieScenarioControlService: mGameModeLauncher : false
09-22 10:50:13.422  3443  3879 I MdnieScenarioControlService: setUIMode
09-22 10:50:13.462  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:13.552  3443  3532 W ActivityManager: Activity pause timeout for ActivityRecord{ce984f0 u0 com.test.thalitest/.MainActivity t4}
09-22 10:50:13.602  9462  9462 D libEGL  : eglInitialize EGLDisplay = 0xff96152c
09-22 10:50:13.642  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-22 10:50:13.692  3443  3982 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-22 10:50:13.702  3443  3982 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-22 10:50:13.762  3443  4847 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-22 10:50:13.762  3443  4847 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4341, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-22 10:50:13.762  3443  4847 D BatteryService: online:4, current avg:-4, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-22 10:50:13.762  3443  4847 D BatteryService: stay LED for fully charged
09-22 10:50:13.762  3443  3443 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-22 10:50:13.772  3443  3443 I MotionRecognitionService: Plugged
09-22 10:50:13.772  3443  3443 D MotionRecognitionService:   cableConnection= 1
09-22 10:50:13.772  3443  3443 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-22 10:50:13.772  3443  3443 D MotionRecognitionService: skip setTransmitPower. 
,09-22 10:50:13.772  3443  3858 D WifiController: ApOrStaEnabledState  msg.what= 155652
09-22 10:50:13.772  3943  3943 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-22 10:50:13.772  3943  3943 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-22 10:50:13.782  3943  3943 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-22 10:50:13.782  5066  5066 D CommonServiceConfiguration: getStringValueSetting
09-22 10:50:13.782  5022  5022 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-22 10:50:13.782  5022  5405 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-22 10:50:13.792  5066  5066 D BatteryMonitor: new battery level: 100
,09-22 10:50:13.792  4747  4747 D BatteryController: saveBatteryData : level[100], status[5]
,09-22 10:50:13.812  3943  3943 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-22 10:50:13.812  3943  3943 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-22 10:50:13.822  9462  9462 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-22 10:50:13.822  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:13.842  9462  9462 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 10:50:13.842  9462  9462 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-22 10:50:13.872  9462  9462 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-22 10:50:13.922  9462  9462 D Activity: performCreate Call Injection manager
,09-22 10:50:13.922  9462  9462 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-22 10:50:13.932  9462  9462 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-22 10:50:13.942  9462  9462 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7548cca I.E...... R.....ID 0,0-0,0}
,09-22 10:50:13.942  9462  9516 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-22 10:50:13.952  3443  4597 W WindowManager: Failed looking up window
09-22 10:50:13.952  3443  4597 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@7e44567 does not exist
09-22 10:50:13.952  3443  4597 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 10:50:13.952  3443  4597 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 10:50:13.952  3443  4597 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 10:50:13.952  3443  4597 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-22 10:50:13.952  3443  4597 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-22 10:50:13.952  3443  4597 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-22 10:50:13.952  3443  4293 D ISSUE_DEBUG: InputChannelName : e011f14 com.test.thalitest/com.test.thalitest.MainActivity
,09-22 10:50:13.952  3443  4308 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,09-22 10:50:13.952  3443  4308 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 10:50:13.952  3443  3443 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-22 10:50:13.952  3443  3443 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-22 10:50:13.962  9462  9462 V ActivityThread: updateVisibility : ActivityRecord{bd20ab1 token=android.os.BinderProxy@1885212 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-22 10:50:13.972  9462  9478 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-22 10:50:13.992  9462  9462 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9462
,09-22 10:50:14.002  3443  3466 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9462 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-22 10:50:14.002  3443  3864 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-22 10:50:14.002  3443  3864 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-22 10:50:14.002  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:14.002  3443  3864 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-22 10:50:14.012  3443  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-22 10:50:14.012  3443  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-22 10:50:14.022  9462  9462 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-22 10:50:14.022  3443  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-22 10:50:14.022  3443  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-22 10:50:14.022  3443  3864 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-22 10:50:14.032  3005  3005 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-22 10:50:14.052  3443  6275 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-22 10:50:14.062  9462  9516 D libEGL  : eglInitialize EGLDisplay = 0xdc77f7c4
09-22 10:50:14.062  9462  9516 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 10:50:14.062  9462  9516 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-22 10:50:14.072  3443  4053 I libsuspend: !@autosuspend_wakeup_count_disable
,09-22 10:50:14.072  3443  4053 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443
09-22 10:50:14.072  3443  4053 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 10:50:14.072  3443  4053 D PowerManagerService: mDisplayReady: false
,09-22 10:50:14.072  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-22 10:50:14.072  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f85e83c00
09-22 10:50:14.072  3443  4053 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 10:50:14.072  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-22 10:50:14.072  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 10:50:14.072  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:14.072  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:14.072  3443  3581 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-22 10:50:14.072  3443  3561 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-22 10:50:14.072  3443  3561 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-22 10:50:14.092  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 10:50:14.092  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 10:50:14.092  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:14.092  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 10:50:14.092  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:14.092  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 10:50:14.092  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-22 10:50:14.092  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-22 10:50:14.092  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:14.092  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:14.092  3443  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 10:50:14.092  3443  3567 D PowerManagerService: mDisplayReady: true
09-22 10:50:14.092  3443  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-22 10:50:14.102  9462  9462 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-22 10:50:14.112  3443  4588 V WindowStateAnimator: Finishing drawing window Window{e011f14 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-22 10:50:14.122  9462  9462 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-22 10:50:14.122  3443  4308 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443
09-22 10:50:14.122  3443  3561 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-22 10:50:14.122  3443  3443 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-22 10:50:14.122  3443  3561 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s78ms (total +1s507ms)
09-22 10:50:14.122  3443  3561 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ce984f0 u0 com.test.thalitest/.MainActivity t4} time:213669
,09-22 10:50:14.132  3443  3561 D ViewRootImpl: #3 mView = null
09-22 10:50:14.132  3005  3014 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-22 10:50:14.132  3443  3443 I KnoxTimeoutHandler: SD activityfalse
,09-22 10:50:14.132  3005  3016 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-22 10:50:14.132  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fcdc99a18
09-22 10:50:14.132  3443  3465 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443
,09-22 10:50:14.142  9462  9520 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 10:50:14.142  9462  9520 D libEGL  : eglInitialize EGLDisplay = 0xd9f2c3f4
09-22 10:50:14.142  3443  4309 V WindowStateAnimator: Finishing drawing window Window{e011f14 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-22 10:50:14.142  9462  9462 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1885212 time:213687
,09-22 10:50:14.172  9462  9520 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-22 10:50:14.182  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:14.222  9462  9462 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9462
,09-22 10:50:14.292  3443  3443 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3443 (0x0)
09-22 10:50:14.292  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable
09-22 10:50:14.292  3443  3443 D PowerManagerService: mDisplayReady: false
09-22 10:50:14.292  3443  3443 I libsuspend: !@autosuspend_wakeup_count_disable done
09-22 10:50:14.292  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 10:50:14.292  3443  3443 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-22 10:50:14.292  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 10:50:14.292  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:14.292  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:14.292  3443  3581 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-22 10:50:14.292  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f85e83c00
,09-22 10:50:14.292  3443  3561 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-22 10:50:14.292  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-22 10:50:14.292  3443  3561 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-22 10:50:14.302  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 10:50:14.302  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 10:50:14.302  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:14.302  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:14.302  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable
09-22 10:50:14.302  3443  3567 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-22 10:50:14.302  3443  3567 I libsuspend: !@autosuspend_wakeup_count_enable done
09-22 10:50:14.302  3443  3567 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-22 10:50:14.302  3443  3567 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-22 10:50:14.302  3443  3567 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-22 10:50:14.302  3443  3567 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-22 10:50:14.302  3443  3567 D PowerManagerService: mDisplayReady: true
09-22 10:50:14.302  3443  3567 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-22 10:50:14.362  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:14.452  9462  9462 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 10:50:14.542  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:14.542  9462  9527 D jxcore_app_log: JniHelper::setJavaVM(0xf4db4000), pthread_self() = -656672464
,09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd69c2b added. We now have 1 listener(s)
,09-22 10:50:14.552  4022  4022 D Recents : onTaskStackChanged
,09-22 10:50:14.552  9462  9527 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
09-22 10:50:14.552  9462  9527 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,09-22 10:50:14.552  9462  9527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:50:14.552  9462  9527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-22 10:50:14.552  9462  9527 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f2646 added. We now have 1 listener(s)
,09-22 10:50:14.552  9462  9527 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:50:14.562  9462  9527 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 10:50:14.562  9462  9527 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 10:50:14.562  9462  9527 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 10:50:14.562  9462  9527 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-22 10:50:14.562  4022  4022 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-22 10:50:14.562  9462  9527 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-22 10:50:14.562  9462  9527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 10:50:14.562  9462  9527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-22 10:50:14.562  9462  9527 D BluetoothAdapter: STATE_ON
,09-22 10:50:14.572  4022  4022 D ResourcesManager: For user 0 new overlays fetched Null
,09-22 10:50:14.572  9462  9527 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:50:14.572  9462  9527 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 10:50:14.572  9462  9527 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 10:50:14.572  9462  9527 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 10:50:14.572  9462  9527 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-22 10:50:14.582  9462  9462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:50:14.592  9462  9462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:50:14.602  9462  9462 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 10:50:14.722  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:14.902  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:14.922  9462  9528 W jxcore-log: Initializing JXcore engine
09-22 10:50:14.922  9462  9528 W jxcore-log: JXcore engine is ready
,09-22 10:50:14.942  5033  5033 E audit   : type=1400 msg=audit(1474534214.942:262): avc:  denied  { ioctl } for  pid=9528 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3094 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 10:50:14.942  5033  5033 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-22 10:50:14.942  5033  5033 E audit   : type=1300 msg=audit(1474534214.942:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d81bf3c8 items=0 ppid=3176 pid=9528 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-22 10:50:14.942  5033  5033 E audit   : type=1327 msg=audit(1474534214.942:262): proctitle="com.test.thalitest"
09-22 10:50:14.942  5033  5033 E audit   : type=1320 msg=audit(1474534214.942:262): 
09-22 10:50:14.942  5033  5033 E audit   : type=1400 msg=audit(1474534214.942:263): avc:  denied  { ioctl } for  pid=9528 comm="Thread-160" path="socket:[10096]" dev="sockfs" ino=10096 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 10:50:14.942  5033  5033 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-22 10:50:14.942  5033  5033 E audit   : type=1300 msg=audit(1474534214.942:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d81bf3c8 items=0 ppid=3176 pid=9528 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-22 10:50:14.942  5033  5033 E audit   : type=1327 msg=audit(1474534214.942:263): proctitle="com.test.thalitest"
09-22 10:50:14.942  5033  5033 E audit   : type=1320 msg=audit(1474534214.942:263): 
,09-22 10:50:14.952  9462  9528 W jxcore-log: Starting JXcore engine
,09-22 10:50:14.992  9462  9528 W jxcore-log: Platform android
09-22 10:50:14.992  9462  9528 W jxcore-log: 
09-22 10:50:14.992  9462  9528 W jxcore-log: Process ARCH arm
09-22 10:50:14.992  9462  9528 W jxcore-log: 
,09-22 10:50:15.052  9462  9528 I jxcore-log: JXcore Cordova bridge is ready!
09-22 10:50:15.052  9462  9528 I jxcore-log: 
09-22 10:50:15.052  9462  9528 W jxcore-log: JXcore engine is started
,09-22 10:50:15.062  9462  9527 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 10:50:15.072  9462  9462 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 10:50:15.082  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:15.262  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:15.442  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:15.622  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:15.622  3443  3904 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-22 10:50:15.802  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:15.982  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:16.072  3443  6274 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-22 10:50:16.162  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:16.342  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:16.522  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:16.702  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:16.882  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:17.062  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:17.242  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:17.422  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:17.602  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:17.782  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:17.962  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:18.142  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:18.322  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:18.502  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:18.682  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:18.862  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:19.042  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:19.142  3443  6274 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-22 10:50:19.222  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:19.242  9462  9528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 10:50:19.242  9462  9528 I jxcore-log: 
,09-22 10:50:19.242  9462  9528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 10:50:19.242  9462  9528 I jxcore-log: 
,09-22 10:50:19.252  9462  9528 D BluetoothAdapter: STATE_ON
,09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:50:19.252  9462  9528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 10:50:19.252  9462  9528 D BluetoothAdapter: STATE_ON
,09-22 10:50:19.262  9462  9528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 10:50:19.262  9462  9528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 10:50:19.262  9462  9528 I jxcore-log: 
09-22 10:50:19.262  9462  9528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 10:50:19.262  9462  9528 I jxcore-log: 
,09-22 10:50:19.402  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:19.492  9462  9528 D executeNativeTests: Running unit tests
,09-22 10:50:19.492  9462  9528 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-22 10:50:19.492  9462  9528 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-22 10:50:19.492  9462  9528 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-22 10:50:19.492  9462  9528 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 10:50:19.492  9462  9528 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-22 10:50:19.492  9462  9528 I jxcore-log: *Native tests were executed*
09-22 10:50:19.492  9462  9528 I jxcore-log: 
09-22 10:50:19.492  9462  9528 I jxcore-log: Total number of executed tests:  1
09-22 10:50:19.492  9462  9528 I jxcore-log: 
09-22 10:50:19.492  9462  9528 I jxcore-log: Number of passed tests:  1
09-22 10:50:19.492  9462  9528 I jxcore-log: 
09-22 10:50:19.492  9462  9528 I jxcore-log: Number of failed tests:  0
09-22 10:50:19.492  9462  9528 I jxcore-log: 
09-22 10:50:19.492  9462  9528 I jxcore-log: Number of ignored tests:  0
09-22 10:50:19.492  9462  9528 I jxcore-log: 
,09-22 10:50:19.492  9462  9528 I jxcore-log: Total duration:  1
09-22 10:50:19.492  9462  9528 I jxcore-log: 
09-22 10:50:19.502  9462  9528 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 10:50:19.502  9462  9528 I jxcore-log: 
09-22 10:50:19.502  9462  9528 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:50:19.502  9462  9528 I jxcore-log: 
,09-22 10:50:19.522  9462  9462 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-22 10:50:19.582  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:19.762  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:19.942  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:19.952  9529  9529 I FIPS_bssl: FIPS approved mode (1) | 9529 | app_process
,09-22 10:50:19.962  9529  9529 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 10:50:19.962  9529  9529 D AndroidRuntime: CheckJNI is OFF
,09-22 10:50:19.962  9529  9529 D AndroidRuntime: readGMSProperty: start
09-22 10:50:19.962  9529  9529 D AndroidRuntime: readGMSProperty: already setted!!
09-22 10:50:19.962  9529  9529 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-22 10:50:19.962  9529  9529 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-22 10:50:19.962  9529  9529 D AndroidRuntime: readGMSProperty: end
09-22 10:50:19.962  9529  9529 D AndroidRuntime: addProductProperty: start
,09-22 10:50:19.982  9529  9529 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-22 10:50:20.002  9529  9529 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 10:50:20.002  9529  9529 E AffinityControl: AffinityControl: registerfunction enter
,09-22 10:50:20.012  9529  9529 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 10:50:20.022  3443  4291 D PackageManager: START PACKAGE DELETE: observer{141192177}
09-22 10:50:20.022  3443  4291 D PackageManager: pkg{<packageName>}
09-22 10:50:20.022  3443  4291 D PackageManager: user{0}
09-22 10:50:20.022  3443  4291 D PackageManager: caller{2000}
09-22 10:50:20.022  3443  4291 D PackageManager: flags{2}
,09-22 10:50:20.022  3443  4291 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-22 10:50:20.022  3443  4291 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-22 10:50:20.022  3443  4291 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-22 10:50:20.022  3443  4291 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-22 10:50:20.022  3443  4291 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-22 10:50:20.022  3443  3590 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-22 10:50:20.022  3443  3590 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-22 10:50:20.022  3443  3590 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-22 10:50:20.022  3443  3590 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-22 10:50:20.022  3443  3590 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-22 10:50:20.022  3443  3590 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-22 10:50:20.022  3443  3590 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-22 10:50:20.022  3443  3590 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-22 10:50:20.022  3443  3590 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-22 10:50:20.022  3443  3532 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-22 10:50:20.022  3443  3590 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-22 10:50:20.022  3443  3532 I ActivityManager: Killing 9462:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-22 10:50:20.032  3443  3532 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-22 10:50:20.032  3443  3532 D ActivityManager: mDVFSHelper.acquire()
,09-22 10:50:20.052  3443  3590 D AASAinstall: there is not AASApackages.xml file
,09-22 10:50:20.052  9538  9538 E Zygote  : v2
09-22 10:50:20.052  9538  9538 I libpersona: KNOX_SDCARD checking this for 10171
09-22 10:50:20.052  9538  9538 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-22 10:50:20.052  9538  9538 I libpersona: KNOX_SDCARD not a persona
,09-22 10:50:20.052  9538  9538 E Zygote  : accessInfo : 0
09-22 10:50:20.052  9538  9538 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-22 10:50:20.052  3443  3532 I ActivityManager: Start proc 9538:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
,09-22 10:50:20.062  3443  3532 I ActivityManager:   Force finishing activity ActivityRecord{ce984f0 u0 com.test.thalitest/.MainActivity t4}
09-22 10:50:20.062  3443  3532 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-22 10:50:20.072  9538  9538 D TimaKeyStoreProvider: TimaSignature is unavailable
09-22 10:50:20.072  9538  9538 D ActivityThread: Added TimaKeyStore provider
,09-22 10:50:20.122  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:20.152  3443  4308 D GraphicsStats: Buffer count: 5
09-22 10:50:20.152  3443  4588 I WindowState: WIN DEATH: Window{e011f14 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 10:50:20.162  3443  4383 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@6347544)
,09-22 10:50:20.162  3443  3864 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-22 10:50:20.162  3443  3864 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-22 10:50:20.162  3005  3066 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
09-22 10:50:20.172  3443  3864 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-22 10:50:20.172  3005  4332 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-22 10:50:20.172  3005  3014 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-22 10:50:20.282  3443  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-22 10:50:20.302  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:20.332  3443  3453 I art     : Background sticky concurrent mark sweep GC freed 199309(12MB) AllocSpace objects, 82(1780KB) LOS objects, 25% free, 42MB/56MB, paused 3.824ms total 112.172ms
,09-22 10:50:20.352  3443  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-22 10:50:20.352  3443  3561 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-22 10:50:20.352  3443  3561 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-22 10:50:20.352  3443  3561 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-22 10:50:20.352  3443  3561 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-22 10:50:20.352  3443  3561 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-22 10:50:20.352  3443  3561 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 10:50:20.352  3443  3561 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:50:20.352  3164  3164 W keystore: ENTER clear_uid from uid 1000 for 10171
09-22 10:50:20.352  3443  3561 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-22 10:50:20.352  3443  3561 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-22 10:50:20.352  3443  3561 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 10:50:20.352  3443  3561 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 10:50:20.352  3443  3561 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{16f47ae V.E...... R.....ID 0,0-0,0}
,09-22 10:50:20.352  3443  3561 W WindowManager: Failed looking up window
09-22 10:50:20.352  3443  3561 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2ccb94f does not exist
09-22 10:50:20.352  3443  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 10:50:20.352  3443  3561 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 10:50:20.362  3443  3561 D ISSUE_DEBUG: InputChannelName : 3bb28dc Starting com.test.thalitest
,09-22 10:50:20.362  3443  3590 I art     : Starting a blocking GC Explicit
,09-22 10:50:20.372  3005  3005 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-22 10:50:20.392  4296  4296 D Launcher: onRestart, Launcher: 169219624
,09-22 10:50:20.482  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:20.532  3443  3590 I art     : Explicit concurrent mark sweep GC freed 107954(7MB) AllocSpace objects, 6(1912KB) LOS objects, 32% free, 33MB/49MB, paused 1.608ms total 168.193ms
,09-22 10:50:20.572  3443  3590 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-22 10:50:20.572  3443  3590 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-22 10:50:20.572  3443  3590 D AASAinstall: there is not AASApackages.xml file
09-22 10:50:20.572  3443  3590 D PackageManager: result of delete: 1{141192177}
,09-22 10:50:20.572  3443  3590 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-22 10:50:20.572  3443  3590 D PackageManager: userId{-1}
09-22 10:50:20.572  3443  3590 D PackageManager: andCode{true}
,09-22 10:50:20.572  9529  9529 I art     : System.exit called, status: 0
,09-22 10:50:20.572  9529  9529 I AndroidRuntime: VM exiting with result code 0.
,09-22 10:50:20.662  3443  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-22 10:50:20.692  3443  3532 I WindowManager: Screenshot max retries 4 of Token{50b1b18 ActivityRecord{105efb u0 com.samsung.android.MtpApplication/.USBConnection t3}} appWin=Window{65ec72e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
,09-22 10:50:20.692  3443  3443 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-22 10:50:20.702  3443  3532 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-22 10:50:20.722  3443  3590 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-22 10:50:20.732  3443  3590 I ActivityManager: Killing 9538:com.test.thalitest/u0a171 (adj 9): stop com.test.thalitest cause pkg removed
,09-22 10:50:20.732  4296  4296 D Launcher: onStart, Launcher: 169219624
09-22 10:50:20.732  4296  4296 D Launcher.HomeView: onStart
,09-22 10:50:20.732  3005  3005 I SurfaceFlinger: id=21 createSurf (1440x2560),1 flag=404, uhalitest
,09-22 10:50:20.732  4296  4296 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-22 10:50:20.742  4296  4296 V ActivityThread: updateVisibility : ActivityRecord{583ed31 token=android.os.BinderProxy@26f3227 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-22 10:50:20.742  4296  4296 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-22 10:50:20.742  4296  4296 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-22 10:50:20.742  4296  4296 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
09-22 10:50:20.742  4296  4296 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
,09-22 10:50:20.742  4296  4296 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-22 10:50:20.742  3443  3590 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-22 10:50:20.742  4296  4296 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-22 10:50:20.742  4296  4296 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-22 10:50:20.742  4296  4296 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-22 10:50:20.742  4296  4296 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-22 10:50:20.742  8991  9552 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest,
,09-22 10:50:20.752  3443  3561 D ViewRootImpl: #3 mView = null
,09-22 10:50:20.752  3005  3016 I SurfaceFlinger: id=21 Removed uhalitest (7/11)
09-22 10:50:20.752  3005  3014 I SurfaceFlinger: id=21 Removed uhalitest (-2/11)
,09-22 10:50:20.752  8991  9552 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-22 10:50:20.752  3443  3590 I ActivityManager:   Force finishing activity ActivityRecord{ce984f0 u0 com.test.thalitest/.MainActivity t4 f}
,09-22 10:50:20.752  3443  3590 W ActivityManager: Duplicate finish request for ActivityRecord{ce984f0 u0 com.test.thalitest/.MainActivity t4 f}
,09-22 10:50:20.762  8991  9552 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-22 10:50:20.762  3005  3005 I SurfaceFlinger: id=22 createSurf (1440x2560),1 flag=4, MauncherAct
,09-22 10:50:20.772  4296  4616 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-22 10:50:20.792  3443  4309 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-22 10:50:20.792  3443  4309 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-22 10:50:20.802  3443  3443 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-22 10:50:20.802  3443  3532 D InputDispatcher: Focused application released
,09-22 10:50:20.802  3443  3904 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/4_task.xml
,09-22 10:50:20.812  3443  3443 I KnoxTimeoutHandler: Shared devices show user statefalse
09-22 10:50:20.812  3443  3443 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-22 10:50:20.812  3443  3904 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/4_task.xml
,09-22 10:50:20.822  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fcdc998f8

```
