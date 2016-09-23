#### Test 85046911dcbf444_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-23 08:42:02.192  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:02.372  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:02.552  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:02.722  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:02.792  9284  9284 I FIPS_bssl: FIPS approved mode (1) | 9284 | app_process
09-23 08:42:02.802  9284  9284 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 08:42:02.802  9284  9284 D AndroidRuntime: CheckJNI is OFF
09-23 08:42:02.802  9284  9284 D AndroidRuntime: readGMSProperty: start
09-23 08:42:02.802  9284  9284 D AndroidRuntime: readGMSProperty: already setted!!
09-23 08:42:02.802  9284  9284 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 08:42:02.802  9284  9284 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 08:42:02.802  9284  9284 D AndroidRuntime: readGMSProperty: end
09-23 08:42:02.802  9284  9284 D AndroidRuntime: addProductProperty: start
09-23 08:42:02.822  9284  9284 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 08:42:02.842  9284  9284 I Radio-JNI: register_android_hardware_Radio DONE
09-23 08:42:02.842  9284  9284 E AffinityControl: AffinityControl: registerfunction enter
09-23 08:42:02.852  9284  9284 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-23 08:42:02.882  3426  4280 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-23 08:42:02.882  3426  4280 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 08:42:02.902  3426  4280 D ResourcesManager: For user 0 new overlays fetched Null
09-23 08:42:02.902  3426  4280 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 08:42:02.902  3426  4280 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-23 08:42:02.902  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:02.902  3426  4280 D ActivityManager: mDVFSHelper.acquire()
09-23 08:42:02.912  3426  4280 V WindowManager: addAppToken: AppWindowToken{d0c36ee7c token=Token{aab916f ActivityRecord{bdfec4e u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-23 08:42:02.912  3426  3529 I InjectionManager: Inside getClassLibPath caller 
09-23 08:42:02.922  3426  3529 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 08:42:02.922  3426  3529 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{efc9114 V.E...... R.....ID 0,0-0,0}
09-23 08:42:02.922  3426  3529 W WindowManager: Failed looking up window
09-23 08:42:02.922  3426  3529 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@f360dbd does not exist
09-23 08:42:02.922  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 08:42:02.922  3426  3529 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 08:42:02.922  3426  3529 D ISSUE_DEBUG: InputChannelName : f619fb2 Starting com.test.thalitest
09-23 08:42:02.932  9293  9293 E Zygote  : v2
09-23 08:42:02.932  9293  9293 I libpersona: KNOX_SDCARD checking this for 10171
09-23 08:42:02.932  9293  9293 I libpersona: KNOX_SDCARD not a persona
09-23 08:42:02.932  9293  9293 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 08:42:02.932  3426  4280 I ActivityManager: Start proc 9293:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-23 08:42:02.932  9293  9293 E Zygote  : accessInfo : 0
09-23 08:42:02.932  9293  9293 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-23 08:42:02.932  3426  4280 D InputDispatcher: Focused application set to: xxxx
09-23 08:42:02.942  9284  9284 D AndroidRuntime: Shutting down VM
09-23 08:42:02.942  3426  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-23 08:42:02.942  3008  3008 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-23 08:42:02.972  6055  6055 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 08:42:02.972  9293  9293 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 08:42:02.972  9293  9293 D ActivityThread: Added TimaKeyStore provider
09-23 08:42:02.982  3426  4279 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426
09-23 08:42:02.982  3426  4279 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 08:42:02.982  3426  4279 D PowerManagerService: mDisplayReady: false
09-23 08:42:02.982  3426  4279 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 08:42:02.982  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 08:42:02.982  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 08:42:02.982  6055  6055 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 08:42:02.982  3426  4279 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 08:42:02.982  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f81ec3c00
09-23 08:42:02.982  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:02.982  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 08:42:02.982  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:02.982  3426  3543 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 08:42:02.992  3426  4814 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426
09-23 08:42:02.992  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 08:42:02.992  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 08:42:02.992  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:02.992  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 08:42:02.992  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:02.992  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 08:42:02.992  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 08:42:02.992  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 08:42:02.992  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:02.992  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:02.992  3426  3533 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 08:42:02.992  3426  3533 D PowerManagerService: mDisplayReady: true
09-23 08:42:02.992  3426  3533 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 08:42:03.002  3426  4280 V WindowStateAnimator: Finishing drawing window Window{d4ef324 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 08:42:03.002  3426  4424 D ActivityManager:  Launching com.test.thalitest, updated priority
09-23 08:42:03.022  3008  3019 D libEGL  : eglTerminate EGLDisplay = 0x7f819bee78
09-23 08:42:03.022  3008  3019 D libEGL  : eglTerminate EGLDisplay = 0x7f819bee78
09-23 08:42:03.022  3426  3507 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-23 08:42:03.022  3426  3426 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-23 08:42:03.042  3008  3017 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-23 08:42:03.042  3008  4129 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-23 08:42:03.052  4281  4281 V ActivityThread: updateVisibility : ActivityRecord{777de46 token=android.os.BinderProxy@16df192 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-23 08:42:03.052  4281  4281 D Launcher: onTrimMemory. Level: 20
09-23 08:42:03.052  3426  4236 V WindowStateAnimator: Finishing drawing window Window{ad1a6b6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 08:42:03.052  6055  6055 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 08:42:03.052  6055  6055 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 08:42:03.052  6055  6055 V ActivityThread: updateVisibility : ActivityRecord{e35a5d6 token=android.os.BinderProxy@94945eb {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-23 08:42:03.062  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc82b9ef8
09-23 08:42:03.062  3008  4325 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-23 08:42:03.062  3008  3019 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-23 08:42:03.072  3008  4325 D libEGL  : eglTerminate EGLDisplay = 0x7f7a4ffe78
09-23 08:42:03.072  3008  3019 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-23 08:42:03.072  3008  3073 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-23 08:42:03.072  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc82b9ef8
09-23 08:42:03.072  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc82b9ec8
09-23 08:42:03.082  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:03.132  3426  3426 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426 (0x0)
09-23 08:42:03.142  3426  3426 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426 (0x0)
09-23 08:42:03.142  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 08:42:03.142  3426  3426 D PowerManagerService: mDisplayReady: false
09-23 08:42:03.142  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 08:42:03.142  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 08:42:03.142  3426  3426 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 08:42:03.142  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 08:42:03.142  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:03.142  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:03.142  3426  3543 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 08:42:03.142  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f81ec3c00
09-23 08:42:03.142  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 08:42:03.142  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 08:42:03.142  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 08:42:03.142  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 08:42:03.142  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:03.142  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 08:42:03.142  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:03.142  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 08:42:03.142  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 08:42:03.142  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:03.142  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:03.142  3426  3533 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 08:42:03.142  3426  3533 D PowerManagerService: mDisplayReady: true
09-23 08:42:03.142  3426  3533 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 08:42:03.262  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:03.352  3426  4424 I WindowManager: Screenshot max retries 4 of Token{aab916f ActivityRecord{bdfec4e u0 com.test.thalitest/.MainActivity t4}} appWin=Window{f619fb2 u0 d0 Starting com.test.thalitest} drawState=1
09-23 08:42:03.352  3426  3529 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 08:42:03.352  3426  3426 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 08:42:03.352  3426  3529 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 08:42:03.352  3426  3426 I KnoxTimeoutHandler: SD activityfalse
09-23 08:42:03.362  3426  5951 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 08:42:03.362  3426  5951 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 08:42:03.362  3426  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-23 08:42:03.382  9293  9293 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 08:42:03.382  3426  3975 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-23 08:42:03.382  9293  9293 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-23 08:42:03.392  3426  5951 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 08:42:03.402  3426  5951 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 08:42:03.402  3426  3529 V WindowStateAnimator: Finishing drawing window Window{f619fb2 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-23 08:42:03.402  3426  3529 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 08:42:03.402  3426  3426 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 08:42:03.402  3426  3529 D ActivityManager: mDVFSHelper.release()
09-23 08:42:03.402  3426  3529 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7e6dc60 u0 com.samsung.android.MtpApplication/.USBConnection t3} time:223045
09-23 08:42:03.402  3426  3426 I KnoxTimeoutHandler: SD activityfalse
09-23 08:42:03.412  9293  9293 D ResourcesManager: For user 0 new overlays fetched Null
09-23 08:42:03.412  3426  5951 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 08:42:03.412  3426  5951 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 08:42:03.412  3426  5951 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 08:42:03.412  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc82b9dd8
09-23 08:42:03.422  9293  9293 I InjectionManager: Inside getClassLibPath caller 
09-23 08:42:03.432  9293  9293 D InjectionManager: InjectionManager
09-23 08:42:03.432  9293  9293 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-23 08:42:03.432  9293  9293 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-23 08:42:03.432  9293  9293 I InjectionManager: featureStore :{}
09-23 08:42:03.442  9293  9293 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 08:42:03.442  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:03.442  9293  9293 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-23 08:42:03.442  9293  9293 D RelationGraph: garbageCollect()
09-23 08:42:03.452  9293  9293 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 08:42:03.482  9293  9293 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-23 08:42:03.522  9293  9293 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-23 08:42:03.522  9293  9293 D ResourcesManager: For user 0 new overlays fetched Null
09-23 08:42:03.522  9293  9293 I InjectionManager: Inside getClassLibPath caller 
09-23 08:42:03.522  9293  9293 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-23 08:42:03.572  9293  9293 I cr_LibraryLoader: Time to load native libraries: 31 ms (timestamps 3183-3214)
09-23 08:42:03.572  9293  9293 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 08:42:03.592  3426  4145 E Watchdog: !@Sync 7 [09-23 08:42:03.608]
09-23 08:42:03.612  3426  3877 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-23 08:42:03.622  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:03.642  9293  9308 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-23 08:42:03.662  9293  9293 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {99e8088}
09-23 08:42:03.662  9293  9293 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 08:42:03.692  9293  9293 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 08:42:03.712  3426  3877 I MdnieScenarioControlService: mGameModeLauncher : false
09-23 08:42:03.712  3426  3877 I MdnieScenarioControlService: setUIMode
09-23 08:42:03.732  9293  9293 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-23 08:42:03.802  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:03.852  3426  3507 W ActivityManager: Activity pause timeout for ActivityRecord{bdfec4e u0 com.test.thalitest/.MainActivity t4}
09-23 08:42:03.882  9293  9293 D libEGL  : eglInitialize EGLDisplay = 0xfff468ec
09-23 08:42:03.952  3426  3955 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-23 08:42:03.952  3426  3955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-23 08:42:03.982  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:04.022  9293  9293 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-23 08:42:04.032  9293  9293 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-23 08:42:04.032  9293  9293 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-23 08:42:04.062  9293  9293 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-23 08:42:04.112  9293  9293 D Activity: performCreate Call Injection manager
,09-23 08:42:04.112  9293  9293 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-23 08:42:04.122  9293  9293 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 08:42:04.122  9293  9293 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8acb7a6 I.E...... R.....ID 0,0-0,0}
,09-23 08:42:04.132  9293  9345 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 08:42:04.132  3426  3444 W WindowManager: Failed looking up window
09-23 08:42:04.132  3426  3444 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@e712e9d does not exist
09-23 08:42:04.132  3426  3444 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 08:42:04.132  3426  3444 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 08:42:04.132  3426  3444 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 08:42:04.132  3426  3444 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-23 08:42:04.132  3426  3444 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-23 08:42:04.132  3426  3444 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 08:42:04.132  3426  4386 D ISSUE_DEBUG: InputChannelName : cd2df12 com.test.thalitest/com.test.thalitest.MainActivity
,09-23 08:42:04.142  3426  3975 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-23 08:42:04.142  3426  3975 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 08:42:04.142  3426  3426 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-23 08:42:04.142  3426  3426 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-23 08:42:04.142  9293  9293 V ActivityThread: updateVisibility : ActivityRecord{c394594 token=android.os.BinderProxy@17a0f6e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-23 08:42:04.152  9293  9308 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-23 08:42:04.162  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:04.182  9293  9293 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9293
,09-23 08:42:04.182  3426  3975 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9293 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 08:42:04.182  3426  3865 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-23 08:42:04.182  3426  3865 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 08:42:04.192  3426  3865 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-23 08:42:04.192  3426  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 08:42:04.202  3426  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 08:42:04.202  9293  9293 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 08:42:04.202  3426  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-23 08:42:04.212  3426  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 08:42:04.212  3426  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-23 08:42:04.212  3426  3865 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 08:42:04.222  3008  3008 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-23 08:42:04.232  9293  9345 D libEGL  : eglInitialize EGLDisplay = 0xdc3ff7c4
,09-23 08:42:04.232  9293  9345 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 08:42:04.242  9293  9345 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-23 08:42:04.242  3426  4280 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426
09-23 08:42:04.242  3426  4280 I libsuspend: !@autosuspend_wakeup_count_disable
,09-23 08:42:04.242  3426  4280 D PowerManagerService: mDisplayReady: false
09-23 08:42:04.242  3426  4280 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 08:42:04.242  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 08:42:04.242  3426  4280 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 08:42:04.242  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 08:42:04.242  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:04.242  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f81ec3c00
09-23 08:42:04.242  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:04.242  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 08:42:04.242  3426  3543 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 08:42:04.242  3426  3529 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 08:42:04.242  3426  3529 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-23 08:42:04.262  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-23 08:42:04.262  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 08:42:04.262  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 08:42:04.262  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:04.262  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 08:42:04.262  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-23 08:42:04.262  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 08:42:04.262  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 08:42:04.262  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:04.262  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-23 08:42:04.262  3426  3533 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 08:42:04.262  3426  3533 D PowerManagerService: mDisplayReady: true
09-23 08:42:04.262  3426  3533 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 08:42:04.272  9293  9293 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-23 08:42:04.282  3426  4280 V WindowStateAnimator: Finishing drawing window Window{cd2df12 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-23 08:42:04.282  9293  9293 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-23 08:42:04.292  3426  3955 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426
,09-23 08:42:04.292  3426  3529 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 08:42:04.292  3426  3426 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 08:42:04.292  3426  3529 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +945ms (total +1s385ms)
,09-23 08:42:04.292  3426  3529 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bdfec4e u0 com.test.thalitest/.MainActivity t4} time:223938
09-23 08:42:04.292  3426  3529 D ViewRootImpl: #3 mView = null
,09-23 08:42:04.302  3008  3017 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
,09-23 08:42:04.302  3426  3426 I KnoxTimeoutHandler: SD activityfalse
,09-23 08:42:04.302  3008  4129 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-23 08:42:04.302  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc82b9ef8
,09-23 08:42:04.302  3426  4424 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426
,09-23 08:42:04.312  9293  9349 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 08:42:04.312  9293  9349 D libEGL  : eglInitialize EGLDisplay = 0xdab3f3f4
,09-23 08:42:04.312  3426  4293 V WindowStateAnimator: Finishing drawing window Window{cd2df12 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-23 08:42:04.312  9293  9293 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17a0f6e time:223957
,09-23 08:42:04.342  9293  9349 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-23 08:42:04.342  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:04.352  3426  5952 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-23 08:42:04.382  9293  9293 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9293
,09-23 08:42:04.452  3426  3426 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426 (0x0)
09-23 08:42:04.452  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 08:42:04.452  3426  3426 D PowerManagerService: mDisplayReady: false
09-23 08:42:04.452  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 08:42:04.452  3426  3426 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 08:42:04.462  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 08:42:04.462  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 08:42:04.462  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:04.462  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:04.462  3426  3543 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 08:42:04.462  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f81ec3c00
09-23 08:42:04.462  3426  3529 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 08:42:04.462  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 08:42:04.462  3426  3529 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-23 08:42:04.472  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 08:42:04.472  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 08:42:04.472  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:04.472  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:04.472  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 08:42:04.472  3426  3533 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 08:42:04.472  3426  3533 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 08:42:04.472  3426  3533 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 08:42:04.472  3426  3533 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 08:42:04.472  3426  3533 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 08:42:04.472  3426  3533 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 08:42:04.472  3426  3533 D PowerManagerService: mDisplayReady: true
09-23 08:42:04.472  3426  3533 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 08:42:04.522  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:04.602  9293  9293 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 08:42:04.702  9293  9356 D jxcore_app_log: JniHelper::setJavaVM(0xf4c74000), pthread_self() = -633865936
,09-23 08:42:04.702  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:04.702  9293  9356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 08:42:04.702  9293  9356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 08:42:04.702  9293  9356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 08:42:04.702  9293  9356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 08:42:04.702  9293  9356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 08:42:04.702  9293  9356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f685656 added. We now have 1 listener(s)
,09-23 08:42:04.712  9293  9356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-23 08:42:04.712  9293  9356 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 08:42:04.712  9293  9356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 08:42:04.712  9293  9356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-23 08:42:04.712  9293  9356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e5aad added. We now have 1 listener(s)
09-23 08:42:04.712  9293  9356 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 08:42:04.712  9293  9356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 08:42:04.712  9293  9356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 08:42:04.712  9293  9356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 08:42:04.712  9293  9356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 08:42:04.712  9293  9356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 08:42:04.722  9293  9356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 08:42:04.722  9293  9356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-23 08:42:04.732  9293  9356 D BluetoothAdapter: STATE_ON
,09-23 08:42:04.732  9293  9356 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:42:04.732  9293  9356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 08:42:04.732  9293  9356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 08:42:04.732  9293  9356 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 08:42:04.732  9293  9356 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 08:42:04.732  9293  9293 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:42:04.742  9293  9293 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:42:04.762  9293  9293 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 08:42:04.852  4020  4020 D Recents : onTaskStackChanged
,09-23 08:42:04.862  4020  4020 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-23 08:42:04.872  4020  4020 D ResourcesManager: For user 0 new overlays fetched Null,
,09-23 08:42:04.882  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:05.062  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:05.082  9293  9357 W jxcore-log: Initializing JXcore engine
09-23 08:42:05.082  9293  9357 W jxcore-log: JXcore engine is ready
,09-23 08:42:05.102  5018  5018 E audit   : type=1400 msg=audit(1474612925.102:264): avc:  denied  { ioctl } for  pid=9357 comm="Thread-156" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1392 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 08:42:05.102  5018  5018 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 08:42:05.102  5018  5018 E audit   : type=1300 msg=audit(1474612925.102:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d8e443c8 items=0 ppid=3184 pid=9357 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 08:42:05.102  5018  5018 E audit   : type=1327 msg=audit(1474612925.102:264): proctitle="com.test.thalitest"
09-23 08:42:05.102  5018  5018 E audit   : type=1320 msg=audit(1474612925.102:264): 
09-23 08:42:05.102  5018  5018 E audit   : type=1400 msg=audit(1474612925.102:265): avc:  denied  { ioctl } for  pid=9357 comm="Thread-156" path="socket:[11183]" dev="sockfs" ino=11183 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 08:42:05.102  5018  5018 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 08:42:05.102  5018  5018 E audit   : type=1300 msg=audit(1474612925.102:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d8e443c8 items=0 ppid=3184 pid=9357 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 08:42:05.102  5018  5018 E audit   : type=1327 msg=audit(1474612925.102:265): proctitle="com.test.thalitest"
09-23 08:42:05.102  5018  5018 E audit   : type=1320 msg=audit(1474612925.102:265): 
,09-23 08:42:05.112  9293  9357 W jxcore-log: Starting JXcore engine
,09-23 08:42:05.142  9293  9357 W jxcore-log: Platform android
09-23 08:42:05.142  9293  9357 W jxcore-log: 
09-23 08:42:05.142  9293  9357 W jxcore-log: Process ARCH arm
09-23 08:42:05.142  9293  9357 W jxcore-log: 
,09-23 08:42:05.212  9293  9357 I jxcore-log: JXcore Cordova bridge is ready!
09-23 08:42:05.212  9293  9357 I jxcore-log: 
09-23 08:42:05.212  9293  9357 W jxcore-log: JXcore engine is started
,09-23 08:42:05.212  9293  9356 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 08:42:05.222  9293  9293 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 08:42:05.242  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:05.422  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:05.602  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:05.782  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:05.922  3426  3902 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
09-23 08:42:05.962  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:06.142  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:06.322  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:06.362  3426  5951 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-23 08:42:06.502  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:06.682  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:06.862  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:07.042  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:07.222  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:07.402  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:07.582  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:07.762  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:07.942  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:08.122  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:08.302  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:08.482  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:08.562  3155  3672 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 08:42:08.662  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:08.842  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:09.022  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:09.072  3426  5999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-23 08:42:09.202  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:09.382  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:09.432  3426  5951 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-23 08:42:09.462  9293  9357 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 08:42:09.462  9293  9357 I jxcore-log: 
,09-23 08:42:09.462  9293  9357 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 08:42:09.462  9293  9357 I jxcore-log: 
,09-23 08:42:09.472  9293  9357 D BluetoothAdapter: STATE_ON
,09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:42:09.482  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 08:42:09.482  9293  9357 D BluetoothAdapter: STATE_ON
,09-23 08:42:09.482  9293  9357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 08:42:09.482  9293  9357 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 08:42:09.482  9293  9357 I jxcore-log: 
09-23 08:42:09.492  9293  9357 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 08:42:09.492  9293  9357 I jxcore-log: 
,09-23 08:42:09.562  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:09.712  9293  9357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 08:42:09.712  9293  9357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b7eba6 added. We now have 2 listener(s)
09-23 08:42:09.712  9293  9357 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 08:42:09.712  9293  9357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 08:42:09.712  9293  9357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 08:42:09.712  9293  9357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 08:42:09.712  9293  9357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58019e7 added. We now have 2 listener(s)
09-23 08:42:09.712  9293  9357 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 08:42:09.722  9293  9357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 08:42:09.722  9293  9357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 08:42:09.732  9293  9357 D BluetoothAdapter: STATE_ON
,09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:42:09.732  9293  9357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 08:42:09.732  9293  9357 D BluetoothAdapter: STATE_ON
,09-23 08:42:09.742  9293  9357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 08:42:09.742  9293  9357 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 08:42:09.742  9293  9357 D ExecuteNativeTests: Running unit tests
09-23 08:42:09.742  9293  9357 D BluetoothAdapter: enable()
,09-23 08:42:09.742  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:09.752  9293  9293 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:42:09.752  9293  9357 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 08:42:09.752  9293  9293 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:42:09.762  3426  3507 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e0d30c2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ceb326 5039:com.samsung.android.providers.context/u0a7}
,09-23 08:42:09.762  9293  9357 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-23 08:42:09.772  3426  4815 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-23 08:42:09.772  3426  4815 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-23 08:42:09.772  3426  4815 D WifiService: setWifiEnabled: true pid=9293, uid=10171
,09-23 08:42:09.782  3426  4815 W ActivityManager: Permission Denial: getCurrentUser() from pid=9293, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-23 08:42:09.782  3426  3856 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-23 08:42:09.782  3426  4815 W WifiService: Failed getting userId using ActivityManagerNative
09-23 08:42:09.782  3426  4815 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9293, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-23 08:42:09.782  3426  4815 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-23 08:42:09.782  3426  4815 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-23 08:42:09.782  3426  4815 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-23 08:42:09.782  3426  4815 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-23 08:42:09.782  3426  4815 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 08:42:09.782  3426  4815 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,09-23 08:42:09.782  3426  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-23 08:42:09.782  3426  3856 D WifiBigDataLog: init : 
09-23 08:42:09.782  3426  4815 D SettingsProvider: isChangeAllowed() : name = wifi_on,
09-23 08:42:09.782  3426  3859 D WifiStateMachine: setFccChannel: channel = 0
,09-23 08:42:09.782  3426  3859 D WifiController: [FCC]setFccChannel() is called !!!
09-23 08:42:09.782  3426  3859 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-23 08:42:09.792  3426  3856 D WifiStateMachine: setFccChannelNative: channel = 0
,09-23 08:42:09.792  3426  3856 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-23 08:42:09.802  3426  3507 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8850ed3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ceb326 5039:com.samsung.android.providers.context/u0a7}
,09-23 08:42:09.932  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:10.112  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:10.282  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:10.462  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:10.642  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:10.822  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:11.002  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:11.182  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:11.362  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:11.542  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:11.722  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:11.902  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:12.042  3426  5951 D SSRM:n  : SIOP:: AP = 300, PST = 264 (W:6), CP = 227, LCD = 1
,09-23 08:42:12.082  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:12.262  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:12.442  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:12.622  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:12.802  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:12.962  3426  3551 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-23 08:42:12.982  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 08:42:12.982  3426  3551 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 08:42:13.162  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:13.342  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:13.522  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:13.532  3155  3672 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 08:42:13.702  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:13.882  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:14.062  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:14.242  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:14.422  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:14.602  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:14.782  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:14.962  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:15.142  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:15.322  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:15.502  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:15.682  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:15.862  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:16.042  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:16.222  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:16.402  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:16.582  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:16.762  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:16.942  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:17.122  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:17.302  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:17.482  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:17.662  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:17.842  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:18.022  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:18.202  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:18.382  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:18.562  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:18.742  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:18.922  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:19.102  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:19.282  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:19.462  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:19.642  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:19.792  9293  9357 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 08:42:19.812  9293  9357 I jxcore-log: *Native tests were executed*
09-23 08:42:19.812  9293  9357 I jxcore-log: 
,09-23 08:42:19.812  9293  9357 I jxcore-log: Total number of executed tests:  1
09-23 08:42:19.812  9293  9357 I jxcore-log: 
09-23 08:42:19.812  9293  9357 I jxcore-log: Number of passed tests:  1
09-23 08:42:19.812  9293  9357 I jxcore-log: 
09-23 08:42:19.812  9293  9357 I jxcore-log: Number of failed tests:  0
09-23 08:42:19.812  9293  9357 I jxcore-log: 
09-23 08:42:19.812  9293  9357 I jxcore-log: Number of ignored tests:  0
09-23 08:42:19.812  9293  9357 I jxcore-log: 
09-23 08:42:19.812  9293  9357 I jxcore-log: Total duration:  2
09-23 08:42:19.812  9293  9357 I jxcore-log: 
09-23 08:42:19.812  9293  9357 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 08:42:19.812  9293  9357 I jxcore-log: 
09-23 08:42:19.812  9293  9357 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 08:42:19.812  9293  9357 I jxcore-log: 
,09-23 08:42:19.812  9293  9357 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 08:42:19.812  9293  9357 I jxcore-log: 
09-23 08:42:19.822  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:19.842  9293  9293 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-23 08:42:20.002  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:20.182  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:20.302  9361  9361 I FIPS_bssl: FIPS approved mode (1) | 9361 | app_process
,09-23 08:42:20.302  9361  9361 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 08:42:20.312  9361  9361 D AndroidRuntime: CheckJNI is OFF
,09-23 08:42:20.312  9361  9361 D AndroidRuntime: readGMSProperty: start
09-23 08:42:20.312  9361  9361 D AndroidRuntime: readGMSProperty: already setted!!
09-23 08:42:20.312  9361  9361 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 08:42:20.312  9361  9361 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 08:42:20.312  9361  9361 D AndroidRuntime: readGMSProperty: end
09-23 08:42:20.312  9361  9361 D AndroidRuntime: addProductProperty: start
,09-23 08:42:20.322  9361  9361 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 08:42:20.342  9361  9361 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 08:42:20.352  9361  9361 E AffinityControl: AffinityControl: registerfunction enter
,09-23 08:42:20.362  9361  9361 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 08:42:20.362  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:20.362  3426  4814 D PackageManager: START PACKAGE DELETE: observer{90032656}
09-23 08:42:20.362  3426  4814 D PackageManager: pkg{<packageName>}
09-23 08:42:20.362  3426  4814 D PackageManager: user{0}
09-23 08:42:20.362  3426  4814 D PackageManager: caller{2000}
09-23 08:42:20.362  3426  4814 D PackageManager: flags{2}
,09-23 08:42:20.362  3426  4814 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-23 08:42:20.362  3426  4814 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-23 08:42:20.362  3426  4814 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-23 08:42:20.362  3426  4814 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-23 08:42:20.362  3426  4814 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-23 08:42:20.372  3426  3551 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-23 08:42:20.372  3426  3551 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-23 08:42:20.372  3426  3551 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-23 08:42:20.372  3426  3551 D ApplicationPolicy: getApplicationUninstallationEnabled
09-23 08:42:20.372  3426  3551 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-23 08:42:20.372  3426  3551 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-23 08:42:20.372  3426  3551 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-23 08:42:20.372  3426  3551 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-23 08:42:20.372  3426  3551 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-23 08:42:20.372  3426  3507 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-23 08:42:20.372  3426  3551 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-23 08:42:20.372  3426  3507 I ActivityManager: Killing 9293:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-23 08:42:20.372  3426  3507 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-23 08:42:20.382  3426  3507 D ActivityManager: mDVFSHelper.acquire()
,09-23 08:42:20.392  3426  3551 D AASAinstall: there is not AASApackages.xml file
,09-23 08:42:20.402  9370  9370 E Zygote  : v2
09-23 08:42:20.402  9370  9370 I libpersona: KNOX_SDCARD checking this for 10171
09-23 08:42:20.402  9370  9370 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 08:42:20.402  9370  9370 I libpersona: KNOX_SDCARD not a persona
,09-23 08:42:20.402  9370  9370 E Zygote  : accessInfo : 0
09-23 08:42:20.402  9370  9370 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-23 08:42:20.402  3426  3507 I ActivityManager: Start proc 9370:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
,09-23 08:42:20.412  3426  3507 I ActivityManager:   Force finishing activity ActivityRecord{bdfec4e u0 com.test.thalitest/.MainActivity t4}
,09-23 08:42:20.412  3426  3507 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-23 08:42:20.422  9370  9370 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 08:42:20.422  9370  9370 D ActivityThread: Added TimaKeyStore provider
,09-23 08:42:20.532  3426  4308 D GraphicsStats: Buffer count: 5
,09-23 08:42:20.532  3426  4386 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@c87c52f)
09-23 08:42:20.532  3426  3446 I WindowState: WIN DEATH: Window{cd2df12 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-23 08:42:20.532  3426  3865 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 08:42:20.532  3426  3865 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 08:42:20.552  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:20.552  3008  3073 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
09-23 08:42:20.552  3008  4325 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-23 08:42:20.552  3426  3865 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 08:42:20.552  3008  4129 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-23 08:42:20.702  3426  3551 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-23 08:42:20.722  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:20.732  3426  3436 I art     : Background sticky concurrent mark sweep GC freed 195877(12MB) AllocSpace objects, 93(2000KB) LOS objects, 25% free, 42MB/56MB, paused 3.705ms total 126.210ms
,09-23 08:42:20.762  3426  3551 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 08:42:20.762  3168  3168 W keystore: ENTER clear_uid from uid 1000 for 10171
,09-23 08:42:20.762  3426  3551 I art     : Starting a blocking GC Explicit
,09-23 08:42:20.772  3426  3529 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-23 08:42:20.772  3426  3529 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-23 08:42:20.772  3426  3529 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-23 08:42:20.772  3426  3529 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-23 08:42:20.772  3426  3529 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-23 08:42:20.772  3426  3529 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 08:42:20.772  3426  3529 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 08:42:20.772  3426  3529 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-23 08:42:20.772  3426  3529 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 08:42:20.772  3426  3529 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 08:42:20.782  3426  3529 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 08:42:20.782  3426  3529 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{794e041 V.E...... R.....ID 0,0-0,0}
,09-23 08:42:20.782  3426  3529 W WindowManager: Failed looking up window
09-23 08:42:20.782  3426  3529 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@9fd79e6 does not exist
09-23 08:42:20.782  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 08:42:20.782  3426  3529 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 08:42:20.782  3426  3529 D ISSUE_DEBUG: InputChannelName : 9f52b27 Starting com.test.thalitest
,09-23 08:42:20.782  3008  3008 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-23 08:42:20.802  4281  4281 D Launcher: onRestart, Launcher: 192173511
,09-23 08:42:20.902  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:20.932  3426  3551 I art     : Explicit concurrent mark sweep GC freed 108799(7MB) AllocSpace objects, 6(1912KB) LOS objects, 32% free, 33MB/49MB, paused 1.563ms total 168.043ms
,09-23 08:42:20.972  3426  3551 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-23 08:42:20.972  3426  3551 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-23 08:42:20.982  3426  3551 D AASAinstall: there is not AASApackages.xml file
09-23 08:42:20.982  3426  3551 D PackageManager: result of delete: 1{90032656}
,09-23 08:42:20.982  3426  3551 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-23 08:42:20.982  3426  3551 D PackageManager: userId{-1}
09-23 08:42:20.982  3426  3551 D PackageManager: andCode{true}
,09-23 08:42:20.982  9361  9361 I art     : System.exit called, status: 0
09-23 08:42:20.982  9361  9361 I AndroidRuntime: VM exiting with result code 0.
,09-23 08:42:21.082  3426  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 08:42:21.092  3426  3507 I WindowManager: Screenshot max retries 4 of Token{6b14519 ActivityRecord{7e6dc60 u0 com.samsung.android.MtpApplication/.USBConnection t3}} appWin=Window{ad1a6b6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
,09-23 08:42:21.092  3426  3426 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-23 08:42:21.112  3426  3507 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-23 08:42:21.122  3426  3507 D InputDispatcher: Focused application released
,09-23 08:42:21.122  3426  3529 W WindowManager: Failed looking up window
09-23 08:42:21.122  3426  3529 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@9fd79e6 does not exist
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:5208)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:208)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6690)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1994)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7403)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 08:42:21.122  3426  3529 E ViewSystem: ViewRootImpl #2 Surface is not valid.
,09-23 08:42:21.122  3426  3529 D ViewRootImpl: #3 mView = null
09-23 08:42:21.122  3426  3529 W WindowManager: Failed looking up window
09-23 08:42:21.122  3426  3529 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@9fd79e6 does not exist
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4612)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3754)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6893)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4238)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 08:42:21.122  3426  3529 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 08:42:21.142  3426  3444 I ActivityManager: Killing 8371:com.google.android.gm/u0a108 (adj 15): DHA:empty #33
,09-23 08:42:21.162  3426  4051 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-23 08:42:21.162  9370  9370 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 08:42:21.162  3426  4051 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 08:42:21.162  3426  3426 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-23 08:42:21.162  4281  4281 D Launcher: onStart, Launcher: 192173511
09-23 08:42:21.162  4281  4281 D Launcher.HomeView: onStart
,09-23 08:42:21.162  4281  4281 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-23 08:42:21.162  3426  3551 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-23 08:42:21.162  3426  3551 I ActivityManager: Killing 9370:com.test.thalitest/u0a171 (adj 9): stop com.test.thalitest cause pkg removed
,09-23 08:42:21.172  3426  3426 I KnoxTimeoutHandler: Shared devices show user statefalse
09-23 08:42:21.172  3426  3426 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-23 08:42:21.182  3426  3551 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-23 08:42:21.202  8812  9386 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-23 08:42:21.202  8812  9386 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-23 08:42:21.212  8812  9386 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-23 08:42:21.212  4281  4281 V ActivityThread: updateVisibility : ActivityRecord{777de46 token=android.os.BinderProxy@16df192 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-23 08:42:21.222  4281  4281 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-23 08:42:21.222  4281  4281 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-23 08:42:21.222  4281  4281 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,09-23 08:42:21.222  4281  4281 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-23 08:42:21.222  4281  4281 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-23 08:42:21.222  4281  4281 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-23 08:42:21.222  4281  4281 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-23 08:42:21.222  4281  4281 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
,09-23 08:42:21.222  4281  4281 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-23 08:42:21.222  3426  4826 V WindowStateAnimator: Finishing drawing window Window{ad1a6b6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-23 08:42:21.232  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc82b9dd8
,09-23 08:42:21.232  3008  3008 I SurfaceFlinger: id=21 createSurf (1592x384),1 flag=4, VSBConnecti

```
