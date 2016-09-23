#### Test 863677678d24e91_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-23 14:06:42.069  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:42.249  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:42.429  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:42.609  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:42.789  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:42.829  9373  9373 I FIPS_bssl: FIPS approved mode (1) | 9373 | app_process
09-23 14:06:42.839  9373  9373 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 14:06:42.839  9373  9373 D AndroidRuntime: CheckJNI is OFF
09-23 14:06:42.839  9373  9373 D AndroidRuntime: readGMSProperty: start
09-23 14:06:42.839  9373  9373 D AndroidRuntime: readGMSProperty: already setted!!
09-23 14:06:42.839  9373  9373 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 14:06:42.839  9373  9373 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 14:06:42.839  9373  9373 D AndroidRuntime: readGMSProperty: end
09-23 14:06:42.839  9373  9373 D AndroidRuntime: addProductProperty: start
09-23 14:06:42.859  9373  9373 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 14:06:42.879  9373  9373 I Radio-JNI: register_android_hardware_Radio DONE
09-23 14:06:42.879  9373  9373 E AffinityControl: AffinityControl: registerfunction enter
09-23 14:06:42.889  9373  9373 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-23 14:06:42.919  3421  3854 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-23 14:06:42.919  3421  3854 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 14:06:42.939  3421  3854 D ResourcesManager: For user 0 new overlays fetched Null
09-23 14:06:42.939  3421  3854 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:06:42.939  3421  3854 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-23 14:06:42.939  3421  3854 D ActivityManager: mDVFSHelper.acquire()
09-23 14:06:42.949  3421  3854 V WindowManager: addAppToken: AppWindowToken{d0d990d12 token=Token{6db549d ActivityRecord{3212774 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-23 14:06:42.949  3421  3585 I InjectionManager: Inside getClassLibPath caller 
09-23 14:06:42.959  3421  3585 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 14:06:42.959  3421  3585 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6c52c6a V.E...... R.....ID 0,0-0,0}
09-23 14:06:42.959  3421  3585 W WindowManager: Failed looking up window
09-23 14:06:42.959  3421  3585 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@978655b does not exist
09-23 14:06:42.959  3421  3585 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 14:06:42.959  3421  3585 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 14:06:42.959  3421  3585 D ISSUE_DEBUG: InputChannelName : 68711f8 Starting com.test.thalitest
09-23 14:06:42.959  9382  9382 E Zygote  : v2
09-23 14:06:42.959  9382  9382 I libpersona: KNOX_SDCARD checking this for 10171
09-23 14:06:42.959  9382  9382 I libpersona: KNOX_SDCARD not a persona
09-23 14:06:42.959  9382  9382 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 14:06:42.969  3421  3854 I ActivityManager: Start proc 9382:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-23 14:06:42.969  3421  3854 D InputDispatcher: Focused application set to: xxxx
09-23 14:06:42.969  9382  9382 E Zygote  : accessInfo : 0
09-23 14:06:42.969  9382  9382 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-23 14:06:42.969  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:42.969  3421  3857 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-23 14:06:42.969  9373  9373 D AndroidRuntime: Shutting down VM
09-23 14:06:42.979  3004  3004 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-23 14:06:42.999  9382  9382 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 14:06:42.999  9382  9382 D ActivityThread: Added TimaKeyStore provider
09-23 14:06:43.019  6092  6092 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:06:43.029  3421  4239 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
09-23 14:06:43.029  3421  4239 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:06:43.029  3421  4239 D PowerManagerService: mDisplayReady: false
09-23 14:06:43.029  3421  4239 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:06:43.029  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:06:43.029  6092  6092 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:06:43.029  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:06:43.029  3421  4239 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:06:43.029  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:43.029  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:43.029  3421  3603 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 14:06:43.029  3004  3004 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f98043c00
09-23 14:06:43.029  3421  4431 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
09-23 14:06:43.029  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 14:06:43.039  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:06:43.039  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:06:43.039  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:43.039  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:06:43.039  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:43.039  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:06:43.039  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:06:43.039  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:06:43.039  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:43.039  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:43.039  3421  3593 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:06:43.039  3421  3593 D PowerManagerService: mDisplayReady: true
09-23 14:06:43.039  3421  3593 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 14:06:43.049  3421  4238 D ActivityManager:  Launching com.test.thalitest, updated priority
09-23 14:06:43.049  3421  4285 V WindowStateAnimator: Finishing drawing window Window{43e0352 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 14:06:43.069  3421  3421 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-23 14:06:43.069  3421  3559 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-23 14:06:43.089  3004  4320 D libEGL  : eglTerminate EGLDisplay = 0x7f907fee78
09-23 14:06:43.089  3004  4320 D libEGL  : eglTerminate EGLDisplay = 0x7f907fee78
09-23 14:06:43.089  3004  3013 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-23 14:06:43.089  3004  3015 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-23 14:06:43.099  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fe0f3b6a8
09-23 14:06:43.099  3421  4989 V WindowStateAnimator: Finishing drawing window Window{b4923b4 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 14:06:43.109  6092  6092 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:06:43.109  6092  6092 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 14:06:43.109  6092  6092 V ActivityThread: updateVisibility : ActivityRecord{6e394e4 token=android.os.BinderProxy@f3d2fa6 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-23 14:06:43.109  3004  3015 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-23 14:06:43.109  3004  4320 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-23 14:06:43.109  4286  4286 D Launcher: onTrimMemory. Level: 20
09-23 14:06:43.109  4286  4286 V ActivityThread: updateVisibility : ActivityRecord{c5cf262 token=android.os.BinderProxy@47bdf00 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-23 14:06:43.119  3004  3067 D libEGL  : eglTerminate EGLDisplay = 0x7f917bee78
09-23 14:06:43.119  3004  4320 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-23 14:06:43.119  3004  4462 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-23 14:06:43.119  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fe0f3b6a8
09-23 14:06:43.119  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fe0f3b678
09-23 14:06:43.149  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:43.179  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421 (0x0)
09-23 14:06:43.179  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421 (0x0)
09-23 14:06:43.179  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:06:43.179  3421  3421 D PowerManagerService: mDisplayReady: false
09-23 14:06:43.179  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:06:43.179  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:06:43.179  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:06:43.179  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:06:43.179  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:43.179  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:43.179  3421  3603 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 14:06:43.179  3004  3004 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f98043c00
09-23 14:06:43.179  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 14:06:43.189  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:06:43.189  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:06:43.189  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:06:43.189  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:43.189  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:06:43.189  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:43.189  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:06:43.189  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:06:43.189  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:43.189  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:43.189  3421  3593 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:06:43.189  3421  3593 D PowerManagerService: mDisplayReady: true
09-23 14:06:43.189  3421  3593 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 14:06:43.329  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:43.389  3421  4238 I WindowManager: Screenshot max retries 4 of Token{6db549d ActivityRecord{3212774 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{68711f8 u0 d0 Starting com.test.thalitest} drawState=1
09-23 14:06:43.389  3421  3585 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:06:43.389  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:06:43.389  3421  3585 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 14:06:43.399  3421  3421 I KnoxTimeoutHandler: SD activityfalse
09-23 14:06:43.399  3421  5963 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:06:43.399  3421  5963 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:06:43.399  3421  3857 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-23 14:06:43.419  9382  9382 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 14:06:43.429  3421  4767 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-23 14:06:43.429  9382  9382 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-23 14:06:43.429  3421  5963 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 14:06:43.429  3421  5963 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:06:43.439  3421  3585 V WindowStateAnimator: Finishing drawing window Window{68711f8 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-23 14:06:43.439  3421  3585 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:06:43.439  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 14:06:43.439  3421  3585 D ActivityManager: mDVFSHelper.release()
09-23 14:06:43.439  3421  3585 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{61e41ee u0 com.samsung.android.MtpApplication/.USBConnection t3} time:261914
09-23 14:06:43.439  3004  3004 D libEGL  : eglInitialize EGLDisplay = 0x7fe0f3b588
09-23 14:06:43.439  3421  3421 I KnoxTimeoutHandler: SD activityfalse
09-23 14:06:43.449  9382  9382 D ResourcesManager: For user 0 new overlays fetched Null
09-23 14:06:43.449  3421  5963 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 14:06:43.449  3421  5963 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:06:43.449  3421  5963 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 14:06:43.449  9382  9382 I InjectionManager: Inside getClassLibPath caller 
09-23 14:06:43.469  3421  5963 D SSRM:n  : SIOP:: AP = 280, PST = 276 (W:10), CP = 236, LCD = 1
09-23 14:06:43.469  9382  9382 D InjectionManager: InjectionManager
09-23 14:06:43.469  9382  9382 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-23 14:06:43.469  9382  9382 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-23 14:06:43.469  9382  9382 I InjectionManager: featureStore :{}
09-23 14:06:43.479  9382  9382 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 14:06:43.479  9382  9382 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-23 14:06:43.479  9382  9382 D RelationGraph: garbageCollect()
09-23 14:06:43.489  9382  9382 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 14:06:43.509  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:43.509  9382  9382 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-23 14:06:43.549  9382  9382 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-23 14:06:43.559  9382  9382 D ResourcesManager: For user 0 new overlays fetched Null
09-23 14:06:43.559  9382  9382 I InjectionManager: Inside getClassLibPath caller 
09-23 14:06:43.559  9382  9382 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-23 14:06:43.619  9382  9382 I cr_LibraryLoader: Time to load native libraries: 32 ms (timestamps 2056-2088)
09-23 14:06:43.619  9382  9382 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 14:06:43.649  3421  3881 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-23 14:06:43.689  9382  9397 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-23 14:06:43.689  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:43.709  9382  9382 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {57c08af}
09-23 14:06:43.709  9382  9382 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 14:06:43.729  9382  9382 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 14:06:43.749  3421  3881 I MdnieScenarioControlService: mGameModeLauncher : false
09-23 14:06:43.749  3421  3881 I MdnieScenarioControlService: setUIMode
09-23 14:06:43.769  9382  9382 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-23 14:06:43.869  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:43.889  3421  3559 W ActivityManager: Activity pause timeout for ActivityRecord{3212774 u0 com.test.thalitest/.MainActivity t4}
09-23 14:06:43.979  9382  9382 D libEGL  : eglInitialize EGLDisplay = 0xffc158fc
09-23 14:06:44.049  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:44.069  3421  4419 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-23 14:06:44.069  3421  4419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-23 14:06:44.159  9382  9382 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-23 14:06:44.179  9382  9382 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 14:06:44.179  9382  9382 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-23 14:06:44.209  9382  9382 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-23 14:06:44.229  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:44.249  9382  9382 D Activity: performCreate Call Injection manager
,09-23 14:06:44.249  9382  9382 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-23 14:06:44.259  9382  9382 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 14:06:44.259  9382  9382 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{48122fa I.E...... R.....ID 0,0-0,0}
,09-23 14:06:44.269  9382  9434 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 14:06:44.279  3421  4989 W WindowManager: Failed looking up window
09-23 14:06:44.279  3421  4989 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@11bad3b does not exist
09-23 14:06:44.279  3421  4989 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 14:06:44.279  3421  4989 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 14:06:44.279  3421  4989 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 14:06:44.279  3421  4989 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-23 14:06:44.279  3421  4989 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-23 14:06:44.279  3421  4989 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 14:06:44.279  3421  4298 D ISSUE_DEBUG: InputChannelName : e32ec58 com.test.thalitest/com.test.thalitest.MainActivity
,09-23 14:06:44.279  3421  3485 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,09-23 14:06:44.279  3421  3485 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-23 14:06:44.279  3421  3421 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-23 14:06:44.279  3421  3421 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-23 14:06:44.289  9382  9382 V ActivityThread: updateVisibility : ActivityRecord{211d308 token=android.os.BinderProxy@44b3a42 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-23 14:06:44.299  9382  9397 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-23 14:06:44.329  9382  9382 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9382
,09-23 14:06:44.329  3421  3485 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9382 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 14:06:44.329  3421  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-23 14:06:44.329  3421  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 14:06:44.339  3421  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-23 14:06:44.339  3421  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-23 14:06:44.349  3421  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 14:06:44.349  9382  9382 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-23 14:06:44.349  3421  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-23 14:06:44.359  3421  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-23 14:06:44.359  3421  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 14:06:44.369  3004  3004 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-23 14:06:44.379  9382  9434 D libEGL  : eglInitialize EGLDisplay = 0xdc47f7c4
,09-23 14:06:44.379  9382  9434 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 14:06:44.389  9382  9434 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-23 14:06:44.389  3421  4284 I libsuspend: !@autosuspend_wakeup_count_disable
,09-23 14:06:44.389  3421  4284 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
09-23 14:06:44.389  3421  4284 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:06:44.389  3421  4284 D PowerManagerService: mDisplayReady: false
,09-23 14:06:44.389  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-23 14:06:44.389  3421  4284 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:06:44.389  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:06:44.389  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-23 14:06:44.389  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:44.389  3421  3603 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 14:06:44.389  3421  3585 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 14:06:44.389  3421  3585 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-23 14:06:44.409  3004  3004 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f98043c00
09-23 14:06:44.409  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-23 14:06:44.409  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:44.409  3421  5964 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-23 14:06:44.409  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:06:44.409  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:06:44.409  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:44.409  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:44.419  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:06:44.419  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:06:44.419  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:06:44.419  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:06:44.419  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:44.419  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:44.419  3421  3593 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:06:44.419  3421  3593 D PowerManagerService: mDisplayReady: true
09-23 14:06:44.419  3421  3593 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 14:06:44.429  9382  9382 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-23 14:06:44.439  3421  4419 V WindowStateAnimator: Finishing drawing window Window{e32ec58 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-23 14:06:44.439  9382  9382 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-23 14:06:44.449  3421  3981 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
09-23 14:06:44.449  3421  3585 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-23 14:06:44.449  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-23 14:06:44.449  3421  3585 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s57ms (total +1s501ms)
09-23 14:06:44.449  3421  3585 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3212774 u0 com.test.thalitest/.MainActivity t4} time:262925
,09-23 14:06:44.449  3421  3585 D ViewRootImpl: #3 mView = null
,09-23 14:06:44.449  3421  3421 I KnoxTimeoutHandler: SD activityfalse
09-23 14:06:44.449  3004  4462 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
,09-23 14:06:44.449  3004  3013 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-23 14:06:44.459  3421  4989 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
,09-23 14:06:44.459  9382  9438 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 14:06:44.459  9382  9438 D libEGL  : eglInitialize EGLDisplay = 0xdaa8c3f4
,09-23 14:06:44.469  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fe0f3b6a8
,09-23 14:06:44.469  3421  3854 V WindowStateAnimator: Finishing drawing window Window{e32ec58 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-23 14:06:44.469  9382  9382 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@44b3a42 time:262945
09-23 14:06:44.479  9382  9438 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-23 14:06:44.529  9382  9382 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9382
,09-23 14:06:44.589  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:44.609  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421 (0x0)
09-23 14:06:44.609  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:06:44.609  3421  3421 D PowerManagerService: mDisplayReady: false
09-23 14:06:44.609  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:06:44.609  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:06:44.609  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:06:44.609  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:06:44.609  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:44.609  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:44.609  3421  3603 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-23 14:06:44.609  3421  3585 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 14:06:44.609  3004  3004 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f98043c00
09-23 14:06:44.609  3421  3585 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-23 14:06:44.609  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-23 14:06:44.629  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:06:44.629  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:06:44.629  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:44.629  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:06:44.629  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:44.629  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:06:44.629  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:06:44.629  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:06:44.629  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:06:44.629  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:06:44.629  3421  3593 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:06:44.629  3421  3593 D PowerManagerService: mDisplayReady: true
09-23 14:06:44.629  3421  3593 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 14:06:44.769  9382  9382 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 14:06:44.769  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:44.869  9382  9445 D jxcore_app_log: JniHelper::setJavaVM(0xf4b74000), pthread_self() = -633341648
,09-23 14:06:44.869  9382  9445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 14:06:44.869  9382  9445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 14:06:44.869  9382  9445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 14:06:44.869  9382  9445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 14:06:44.869  9382  9445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 14:06:44.869  9382  9445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce83eaa added. We now have 1 listener(s)
,09-23 14:06:44.869  9382  9445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-23 14:06:44.869  9382  9445 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 14:06:44.869  9382  9445 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 14:06:44.869  9382  9445 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 14:06:44.879  9382  9445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3f4e11 added. We now have 1 listener(s)
09-23 14:06:44.879  9382  9445 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 14:06:44.879  9382  9445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 14:06:44.879  9382  9445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 14:06:44.879  9382  9445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 14:06:44.879  9382  9445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 14:06:44.879  9382  9445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-23 14:06:44.879  9382  9445 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:06:44.879  9382  9445 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
09-23 14:06:44.889  9382  9445 D BluetoothAdapter: STATE_ON
09-23 14:06:44.899  4021  4021 D Recents : onTaskStackChanged
09-23 14:06:44.899  9382  9445 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:06:44.899  9382  9445 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 14:06:44.899  9382  9445 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 14:06:44.899  9382  9445 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 14:06:44.899  9382  9445 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 14:06:44.899  4021  4021 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-23 14:06:44.899  9382  9382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:06:44.909  9382  9382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 14:06:44.909  4021  4021 D ResourcesManager: For user 0 new overlays fetched Null
09-23 14:06:44.929  9382  9382 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 14:06:44.949  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:45.129  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:45.179  9382  9446 W jxcore-log: Initializing JXcore engine
09-23 14:06:45.179  9382  9446 W jxcore-log: JXcore engine is ready
09-23 14:06:45.199  4963  4963 E audit   : type=1400 msg=audit(1474632405.199:262): avc:  denied  { ioctl } for  pid=9446 comm="Thread-172" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3213 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 14:06:45.199  4963  4963 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 14:06:45.199  4963  4963 E audit   : type=1300 msg=audit(1474632405.199:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=1 a3=d90ca3c8 items=0 ppid=3178 pid=9446 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-172" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 14:06:45.199  4963  4963 E audit   : type=1327 msg=audit(1474632405.199:262): proctitle="com.test.thalitest"
09-23 14:06:45.199  4963  4963 E audit   : type=1320 msg=audit(1474632405.199:262): 
09-23 14:06:45.199  4963  4963 E audit   : type=1400 msg=audit(1474632405.199:263): avc:  denied  { ioctl } for  pid=9446 comm="Thread-172" path="socket:[11248]" dev="sockfs" ino=11248 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 14:06:45.199  4963  4963 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 14:06:45.199  4963  4963 E audit   : type=1300 msg=audit(1474632405.199:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=1 a3=d90ca3c8 items=0 ppid=3178 pid=9446 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-172" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 14:06:45.199  4963  4963 E audit   : type=1327 msg=audit(1474632405.199:263): proctitle="com.test.thalitest"
09-23 14:06:45.199  4963  4963 E audit   : type=1320 msg=audit(1474632405.199:263): 
09-23 14:06:45.209  9382  9446 W jxcore-log: Starting JXcore engine
09-23 14:06:45.249  9382  9446 W jxcore-log: Platform android
09-23 14:06:45.249  9382  9446 W jxcore-log: 
09-23 14:06:45.249  9382  9446 W jxcore-log: Process ARCH arm
09-23 14:06:45.249  9382  9446 W jxcore-log: 
09-23 14:06:45.309  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:45.319  9382  9446 I jxcore-log: JXcore Cordova bridge is ready!
09-23 14:06:45.319  9382  9446 I jxcore-log: 
09-23 14:06:45.319  9382  9446 W jxcore-log: JXcore engine is started
09-23 14:06:45.319  9382  9445 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-23 14:06:45.329  9382  9382 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-23 14:06:45.489  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:45.669  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 14:06:45.849  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:45.949  3421  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-23 14:06:46.029  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:46.209  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:46.389  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:46.409  3421  5963 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-23 14:06:46.569  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:46.749  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:46.929  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:47.109  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:47.289  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:47.469  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:47.649  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:47.829  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:48.009  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:48.189  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:48.369  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:48.549  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:48.729  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:48.909  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:49.089  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:49.269  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:49.449  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:49.469  3421  5963 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-23 14:06:49.629  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:49.809  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:49.989  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:50.009  3149  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 14:06:50.169  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:50.349  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:50.429  3421  6023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-23 14:06:50.529  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:50.709  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:50.889  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:51.069  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:51.249  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:51.279  9382  9446 I jxcore-log: 2016-09-23 12:06:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 14:06:51.279  9382  9446 I jxcore-log: 
,09-23 14:06:51.279  9382  9446 I jxcore-log: 2016-09-23 12:06:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 14:06:51.279  9382  9446 I jxcore-log: 
,09-23 14:06:51.289  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:06:51.289  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:06:51.299  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.299  9382  9446 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 14:06:51.299  9382  9446 I jxcore-log: 2016-09-23 12:06:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 14:06:51.299  9382  9446 I jxcore-log: 
,09-23 14:06:51.299  9382  9446 I jxcore-log: 2016-09-23 12:06:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 14:06:51.299  9382  9446 I jxcore-log: 
,09-23 14:06:51.429  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:51.449  9382  9446 I jxcore-log: Running unit tests
09-23 14:06:51.449  9382  9446 I jxcore-log: 
,09-23 14:06:51.449  9382  9446 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 14:06:51.449  9382  9446 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3172a8c added. We now have 2 listener(s)
09-23 14:06:51.449  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 14:06:51.449  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 14:06:51.449  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 14:06:51.449  9382  9446 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 14:06:51.449  9382  9446 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41bf5d5 added. We now have 2 listener(s)
09-23 14:06:51.449  9382  9446 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 14:06:51.449  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 14:06:51.459  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:06:51.459  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:06:51.469  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:06:51.469  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.479  9382  9446 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 14:06:51.479  9382  9446 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 14:06:51.479  9382  9446 D executeNativeTests: Running unit tests
,09-23 14:06:51.479  9382  9382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:06:51.489  9382  9382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:06:51.519  9382  9446 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 14:06:51.519  9382  9446 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d9e2cb added. We now have 3 listener(s)
09-23 14:06:51.519  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 14:06:51.519  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 14:06:51.519  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 14:06:51.519  9382  9446 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 14:06:51.519  9382  9446 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 added. We now have 3 listener(s)
09-23 14:06:51.519  9382  9446 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 14:06:51.519  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 14:06:51.519  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:06:51.539  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.539  9382  9391 I art     : Background sticky concurrent mark sweep GC freed 35798(1633KB) AllocSpace objects, 7(188KB) LOS objects, 11% free, 8MB/9MB, paused 7.166ms total 50.234ms
,09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:06:51.539  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:06:51.539  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.549  9382  9446 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 14:06:51.549  9382  9446 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 14:06:51.549  9382  9446 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-23 14:06:51.549  9382  9446 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 14:06:51.549  9382  9446 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 14:06:51.549  9382  9446 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 14:06:51.549  9382  9446 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 14:06:51.549  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:51.549  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d9e2cb removed from the list
09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 14:06:51.549  9382  9446 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 removed from the list
09-23 14:06:51.549  9382  9382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 14:06:51.549  9382  9446 D io.jxcore.node.ConnectivityMonitor: stop
09-23 14:06:51.549  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:06:51.549  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:51.549  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 14:06:51.549  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:06:51.549  9382  9446 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 not in the list
09-23 14:06:51.559  9382  9446 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-23 14:06:51.559  9382  9446 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 14:06:51.559  9382  9446 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 14:06:51.559  9382  9446 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 14:06:51.559  9382  9446 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 14:06:51.559  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:51.559  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:06:51.559  9382  9446 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d9e2cb not in the list
09-23 14:06:51.559  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:06:51.559  9382  9446 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 not in the list
09-23 14:06:51.559  9382  9446 D io.jxcore.node.ConnectivityMonitor: stop
09-23 14:06:51.559  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:51.559  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:06:51.559  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:51.559  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 14:06:51.559  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 14:06:51.559  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 14:06:51.559  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:06:51.559  9382  9446 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 not in the list
,09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 14:06:51.569  9382  9446 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 14:06:51.569  9382  9446 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 14:06:51.569  9382  9446 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 14:06:51.569  9382  9446 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 14:06:51.569  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:51.569  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:06:51.569  9382  9446 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d9e2cb not in the list
09-23 14:06:51.569  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:06:51.569  9382  9446 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 not in the list
09-23 14:06:51.569  9382  9446 D io.jxcore.node.ConnectivityMonitor: stop
09-23 14:06:51.569  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:51.569  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:06:51.569  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 14:06:51.569  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:06:51.569  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 14:06:51.569  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 14:06:51.569  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:06:51.569  9382  9446 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 not in the list
09-23 14:06:51.569  9382  9446 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 14:06:51.569  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 14:06:51.579  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 14:06:51.579  9382  9446 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 14:06:51.589  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.589  9382  9446 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 14:06:51.589  9382  9446 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 14:06:51.589  9382  9446 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 14:06:51.589  9382  9446 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 14:06:51.589  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 14:06:51.589  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:06:51.589  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 14:06:51.599  9382  9446 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
,09-23 14:06:51.599  9382  9446 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 14:06:51.609  9382  9382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 14:06:51.609  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:51.609  9382  9382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 14:06:51.619  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.619  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.619  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.629  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 14:06:51.639  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.639  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.639  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 14:06:51.649  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 14:06:51.649  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.659  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.659  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-23 14:06:51.669  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.669  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.669  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-23 14:06:51.669  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 14:06:51.669  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-23 14:06:51.679  9382  9446 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 14:06:51.679  9382  9446 D BluetoothLeScanner: Start Scan
,09-23 14:06:51.679  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.679  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.689  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.689  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:51.699  4951  5095 D BtGatt.GattService: registerClient() - UUID=388da028-cd16-49f4-8dbc-6d2b95941c1a
,09-23 14:06:51.749  4951  5064 D BtGatt.GattService: onClientRegistered() - UUID=388da028-cd16-49f4-8dbc-6d2b95941c1a, clientIf=7
,09-23 14:06:51.749  9382  9393 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-23 14:06:51.759  4951  5097 D BtGatt.GattService: start scan with filters
,09-23 14:06:51.759  4951  5097 D BtGatt.GattService: getScanSettings
,09-23 14:06:51.779  4951  5097 D BtGatt.GattService: Is it foreground application = true
,09-23 14:06:51.779  4951  5097 D BtGatt.GattService: not a background application
,09-23 14:06:51.789  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:51.789  4951  5097 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-23 14:06:51.799  4951  5097 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:06:51.799  4951  5097 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:06:51.799  4951  5128 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-23 14:06:51.799  4951  5128 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 14:06:51.799  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 14:06:51.809  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 14:06:51.809  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 14:06:51.809  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 14:06:51.809  4951  5117 D BtGatt.ScanManager: handling starting scan
09-23 14:06:51.809  4951  5117 D BtGatt.ScanManager: isFilteringSupported
09-23 14:06:51.809  4951  5117 D BluetoothAdapter: enableStandAloneBleMode=
09-23 14:06:51.809  4951  5117 D BluetoothAdapter: STATE_ON
09-23 14:06:51.819  4951  5117 D BluetoothAdapter: STATE_ON
09-23 14:06:51.819  9382  9446 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 14:06:51.819  4951  5117 D BluetoothAdapter: STATE_ON
09-23 14:06:51.819  9382  9446 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 14:06:51.819  9382  9382 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 14:06:51.819  4951  5117 D BluetoothAdapter: STATE_ON
09-23 14:06:51.829  4951  5117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c08af
09-23 14:06:51.829  4951  5128 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 37
,09-23 14:06:51.829  4951  5128 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-23 14:06:51.829  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 14:06:51.829  3421  4419 V AlarmManager:  remove PendingIntent] PendingIntent{770b59: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.829  4951  5064 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-23 14:06:51.829  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:51.839  4951  5117 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-23 14:06:51.839  4951  5117 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-23 14:06:51.839  4951  5117 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-23 14:06:51.839  4951  5117 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-23 14:06:51.839  9382  9446 I io.jxcore.node.ConnectionHelper: start: OK
09-23 14:06:51.839  3421  3854 V AlarmManager:  remove PendingIntent] PendingIntent{7fb231e: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
09-23 14:06:51.839  4951  5128 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 7
09-23 14:06:51.839  4951  5064 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-23 14:06:51.839  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:51.839  4951  5117 D BtGatt.ScanManager: Starting BLE batch scan
09-23 14:06:51.839  4951  5117 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-23 14:06:51.839  4951  5128 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577206
09-23 14:06:51.839  3421  3486 V AlarmManager:  remove PendingIntent] PendingIntent{1d547ff: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
09-23 14:06:51.839  4951  5128 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-23 14:06:51.839  4951  5128 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 14:06:51.839  4951  5128 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:06:51.839  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:06:51.849  3421  3485 V AlarmManager:  remove PendingIntent] PendingIntent{1f989cc: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:06:51.849  4951  5128 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24577206
,09-23 14:06:51.849  3421  4285 V AlarmManager:  remove PendingIntent] PendingIntent{f040415: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.859  4951  5064 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-23 14:06:51.859  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-23 14:06:51.859  4951  5064 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-23 14:06:51.859  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:51.859  3421  4238 V AlarmManager:  remove PendingIntent] PendingIntent{b32532a: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
09-23 14:06:51.859  3421  4419 V AlarmManager:  remove PendingIntent] PendingIntent{640651b: PendingIntentRecord{61b76b8 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.869  3421  4767 V AlarmManager:  remove PendingIntent] PendingIntent{22dcc91: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.869  3421  4989 V AlarmManager:  remove PendingIntent] PendingIntent{afa77f6: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.869  3421  4239 V AlarmManager:  remove PendingIntent] PendingIntent{b7637f7: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.879  3421  4741 V AlarmManager:  remove PendingIntent] PendingIntent{66d4664: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.879  3421  4419 V AlarmManager:  remove PendingIntent] PendingIntent{d51a0cd: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.889  3421  4974 V AlarmManager:  remove PendingIntent] PendingIntent{64e1d82: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.889  3421  4431 V AlarmManager:  remove PendingIntent] PendingIntent{cc5c93: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:51.969  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:52.149  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:52.329  9382  9382 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 14:06:52.329  9382  9382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 14:06:52.329  9382  9382 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 14:06:52.329  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:52.509  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:52.689  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:52.869  3421  3817 V AlarmManager: Expired Alarm result :4
,09-23 14:06:52.869  4951  4951 D BtGatt.ScanManager: awakened up at time 271342
,09-23 14:06:52.869  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:52.879  4951  5117 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:06:52.879  3421  4298 V AlarmManager:  remove PendingIntent] PendingIntent{2647cc9: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.889  4951  5064 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
,09-23 14:06:52.889  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:52.889  4951  5064 D BtGatt.GattService: current time is 271362783266
09-23 14:06:52.889  4951  5064 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:06:52.889  3421  3975 V AlarmManager:  remove PendingIntent] PendingIntent{f448fce: PendingIntentRecord{61b76b8 com.android.bluetooth broadcastIntent}}
09-23 14:06:52.889  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-23 14:06:52.889  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:52.889  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:52.889  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 14:06:52.889  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:52.889  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:52.889  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-23 14:06:52.889  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:52.889  3421  3854 V AlarmManager:  remove PendingIntent] PendingIntent{b562eef: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
09-23 14:06:52.889  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:52.889  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 14:06:52.889  4951  5064 D ScanRecord: parseFromBytes
,09-23 14:06:52.889  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:52.899  9382  9392 D ScanRecord: parseFromBytes
09-23 14:06:52.899  9382  9392 D ScanRecord: first manudata for manu ID
,09-23 14:06:52.899  9382  9392 D ScanRecord: parseFromBytes
09-23 14:06:52.899  9382  9392 D ScanRecord: first manudata for manu ID
09-23 14:06:52.899  9382  9392 D ScanRecord: parseFromBytes
09-23 14:06:52.899  9382  9392 D ScanRecord: first manudata for manu ID
09-23 14:06:52.899  9382  9392 D ScanRecord: parseFromBytes
,09-23 14:06:52.899  9382  9392 D ScanRecord: first manudata for manu ID
09-23 14:06:52.899  3421  3486 V AlarmManager:  remove PendingIntent] PendingIntent{1d8fdfc: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.909  3421  3485 V AlarmManager:  remove PendingIntent] PendingIntent{3af1c85: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.909  3421  4298 V AlarmManager:  remove PendingIntent] PendingIntent{1ddada: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.919  3421  4284 V AlarmManager:  remove PendingIntent] PendingIntent{400cb0b: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.929  3421  4419 V AlarmManager:  remove PendingIntent] PendingIntent{7b5fde8: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.929  3421  4767 V AlarmManager:  remove PendingIntent] PendingIntent{549fc01: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.939  3421  4989 V AlarmManager:  remove PendingIntent] PendingIntent{50ecaa6: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:52.999  3421  3608 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-23 14:06:53.019  3421  3608 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 14:06:53.049  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:53.229  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:53.409  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:53.489  3421  5963 D SSRM:n  : SIOP:: AP = 330, PST = 280 (W:6), CP = 245, LCD = 1
,09-23 14:06:53.589  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:53.769  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:53.889  3421  3817 V AlarmManager: Expired Alarm result :4
,09-23 14:06:53.899  4951  4951 D BtGatt.ScanManager: awakened up at time 272371
,09-23 14:06:53.899  4951  5117 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:06:53.909  3421  3981 V AlarmManager:  remove PendingIntent] PendingIntent{5e11094: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:53.919  4951  5064 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
,09-23 14:06:53.919  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:53.919  4951  5064 D BtGatt.GattService: current time is 272393315842
09-23 14:06:53.919  4951  5064 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:06:53.919  3421  4238 V AlarmManager:  remove PendingIntent] PendingIntent{a59573d: PendingIntentRecord{61b76b8 com.android.bluetooth broadcastIntent}}
,09-23 14:06:53.919  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-23 14:06:53.919  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:53.919  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:53.919  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 14:06:53.919  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:53.919  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:53.919  9382  9393 D ScanRecord: parseFromBytes
,09-23 14:06:53.919  9382  9393 D ScanRecord: first manudata for manu ID
09-23 14:06:53.929  3421  4974 V AlarmManager:  remove PendingIntent] PendingIntent{6cceb32: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
09-23 14:06:53.919  9382  9393 D ScanRecord: parseFromBytes
09-23 14:06:53.919  9382  9393 D ScanRecord: first manudata for manu ID
,09-23 14:06:53.929  3421  4431 V AlarmManager:  remove PendingIntent] PendingIntent{f959083: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:53.939  3421  4285 V AlarmManager:  remove PendingIntent] PendingIntent{d08a200: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:53.949  3421  3981 V AlarmManager:  remove PendingIntent] PendingIntent{a092a39: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:53.949  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:53.949  3421  4419 V AlarmManager:  remove PendingIntent] PendingIntent{1da887e: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:54.129  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:54.309  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:54.489  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:54.669  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:54.849  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:54.919  3421  3817 V AlarmManager: Expired Alarm result :4
,09-23 14:06:54.929  4951  4951 D BtGatt.ScanManager: awakened up at time 273403
,09-23 14:06:54.939  4951  5117 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:06:54.939  3421  3486 V AlarmManager:  remove PendingIntent] PendingIntent{855de2c: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:54.949  4951  5064 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-23 14:06:54.949  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:54.949  3421  4989 V AlarmManager:  remove PendingIntent] PendingIntent{84930f5: PendingIntentRecord{61b76b8 com.android.bluetooth broadcastIntent}}
,09-23 14:06:54.959  3421  4298 V AlarmManager:  remove PendingIntent] PendingIntent{692ae8a: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:54.959  3421  4284 V AlarmManager:  remove PendingIntent] PendingIntent{65e8cfb: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:54.989  3421  3975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-23 14:06:54.989  3421  3975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-23 14:06:54.989  3421  3975 D BatteryService: online:4, current avg:-79, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-23 14:06:54.989  3421  3975 D BatteryService: stay LED for fully charged
09-23 14:06:54.989  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-23 14:06:54.999  3421  3421 I MotionRecognitionService: Plugged
,09-23 14:06:54.999  3421  3421 D MotionRecognitionService:   cableConnection= 1
09-23 14:06:54.999  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-23 14:06:54.999  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
09-23 14:06:54.999  3149  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 14:06:54.999  3421  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-23 14:06:54.999  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-23 14:06:54.999  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-23 14:06:54.999  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-23 14:06:55.009  5002  5002 D CommonServiceConfiguration: getStringValueSetting
09-23 14:06:55.009  4951  4951 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-23 14:06:55.009  4951  5349 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-23 14:06:55.019  5002  5002 D BatteryMonitor: new battery level: 100
,09-23 14:06:55.019  4696  4696 D BatteryController: saveBatteryData : level[100], status[5]
,09-23 14:06:55.019  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:55.039  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 14:06:55.039  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 14:06:55.209  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:55.389  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:55.569  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:55.749  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:55.929  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:55.959  3421  3817 V AlarmManager: Expired Alarm result :4
,09-23 14:06:55.959  4951  4951 D BtGatt.ScanManager: awakened up at time 274430
,09-23 14:06:55.969  4951  5117 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:06:55.969  3421  4419 V AlarmManager:  remove PendingIntent] PendingIntent{e48e771: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:55.969  4951  5064 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
,09-23 14:06:55.969  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:55.979  3421  3981 V AlarmManager:  remove PendingIntent] PendingIntent{df52956: PendingIntentRecord{61b76b8 com.android.bluetooth broadcastIntent}}
,09-23 14:06:55.969  4951  5064 D BtGatt.GattService: current time is 274449098379
09-23 14:06:55.969  4951  5064 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -95, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -90, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 50, -35, 86, -77, -92, -11, 1, -128, -98, 13, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 116, 49, 14, 3, 1, -37, 18, -106, 3, 99, -94, 0]
09-23 14:06:55.979  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-23 14:06:55.979  4951  5064 D ScanRecord: parseFromBytes
,09-23 14:06:55.979  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:55.979  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-23 14:06:55.979  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:55.979  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:55.979  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 14:06:55.979  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:55.979  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:55.979  3421  4989 V AlarmManager:  remove PendingIntent] PendingIntent{27efdd7: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
09-23 14:06:55.979  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 116, 49, 14, 3, 1, -37, 18, -106, 3, 99, -94]
09-23 14:06:55.979  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:55.979  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:55.979  9382  9393 D ScanRecord: parseFromBytes
,09-23 14:06:55.979  9382  9393 D ScanRecord: first manudata for manu ID
09-23 14:06:55.979  9382  9393 D ScanRecord: parseFromBytes
09-23 14:06:55.979  9382  9393 D ScanRecord: first manudata for manu ID
09-23 14:06:55.979  9382  9393 D ScanRecord: parseFromBytes
09-23 14:06:55.979  9382  9393 D ScanRecord: first manudata for manu ID
09-23 14:06:55.979  9382  9393 D ScanRecord: parseFromBytes
,09-23 14:06:55.979  9382  9393 D ScanRecord: first manudata for manu ID
,09-23 14:06:55.989  3421  4285 V AlarmManager:  remove PendingIntent] PendingIntent{cb3c6c4: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:55.989  3421  4284 V AlarmManager:  remove PendingIntent] PendingIntent{eb389ad: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:55.999  3421  4238 V AlarmManager:  remove PendingIntent] PendingIntent{f3284e2: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.009  3421  3854 V AlarmManager:  remove PendingIntent] PendingIntent{5cba073: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.109  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:56.289  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:56.469  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:56.649  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:56.829  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:56.849  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:56.849  9382  9446 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 14:06:56.849  9382  9446 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 14:06:56.849  9382  9446 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 14:06:56.849  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:56.859  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 14:06:56.859  9382  9446 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 14:06:56.859  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 14:06:56.859  9382  9446 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 14:06:56.859  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 14:06:56.859  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 14:06:56.859  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-23 14:06:56.859  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:56.869  9382  9446 D BluetoothAdapter: STATE_ON
,09-23 14:06:56.869  9382  9446 D BluetoothLeScanner: Stop Scan
,09-23 14:06:56.879  4951  4971 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-23 14:06:56.879  4951  4971 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-23 14:06:56.879  4951  4971 D BtGatt.GattService: stopScan() - queue size =1
09-23 14:06:56.879  4951  5128 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-23 14:06:56.879  4951  5128 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
09-23 14:06:56.879  4951  5128 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-23 14:06:56.879  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-23 14:06:56.879  4951  5128 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-23 14:06:56.879  4951  5117 D BtGatt.ScanManager: filter size is 1
09-23 14:06:56.879  4951  5128 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,09-23 14:06:56.879  4951  5117 D BtGatt.ScanManager: delete FilterIndex - 3
09-23 14:06:56.879  4951  5128 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-23 14:06:56.879  4951  5095 D BtGatt.GattService: unregisterClient() - clientIf=7
09-23 14:06:56.879  4951  5064 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-23 14:06:56.889  3421  4767 V AlarmManager:  remove PendingIntent] PendingIntent{e888b30: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.889  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:56.889  4951  5117 D BtGatt.ScanManager: stopping BLe Batch
09-23 14:06:56.889  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 14:06:56.889  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-23 14:06:56.889  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 14:06:56.889  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 14:06:56.889  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 14:06:56.889  4951  5064 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-23 14:06:56.889  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:56.889  4951  5117 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-23 14:06:56.899  9382  9446 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 14:06:56.899  4951  5064 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
,09-23 14:06:56.899  3421  4298 V AlarmManager:  remove PendingIntent] PendingIntent{1ac13a9: PendingIntentRecord{61b76b8 com.android.bluetooth broadcastIntent}}
09-23 14:06:56.899  4951  5064 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-23 14:06:56.899  4951  5064 D BtGatt.GattService: current time is 275374658456
09-23 14:06:56.899  9382  9446 D BluetoothAdapter: STATE_ON
09-23 14:06:56.899  4951  5064 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 14:06:56.899  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 14:06:56.899  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:56.899  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:56.899  4951  5064 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 14:06:56.899  4951  5064 D ScanRecord: parseFromBytes
09-23 14:06:56.899  4951  5064 D ScanRecord: first manudata for manu ID
09-23 14:06:56.909  9382  9446 D BluetoothAdapter: STATE_ON
09-23 14:06:56.909  9382  9446 D BluetoothLeAdvertiser: stop advertising
09-23 14:06:56.909  9382  9446 D BluetoothLeAdvertiser: wrapper is null
09-23 14:06:56.909  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 14:06:56.909  9382  9446 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 14:06:56.909  3421  4974 V AlarmManager:  remove PendingIntent] PendingIntent{1f80d2e: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.909  9382  9446 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 14:06:56.909  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 14:06:56.909  3421  4238 V AlarmManager:  remove PendingIntent] PendingIntent{a35d0cf: PendingIntentRecord{61b76b8 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.909  9382  9446 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 14:06:56.909  9382  9446 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 14:06:56.909  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 14:06:56.909  9382  9446 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d9e2cb not in the list
09-23 14:06:56.909  9382  9446 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 14:06:56.909  9382  9446 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae19aa8 not in the list
09-23 14:06:56.909  9382  9446 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 14:06:56.909  9382  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 14:06:56.909  9382  9382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 14:06:56.909  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:06:56.909  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 14:06:56.919  3421  4419 V AlarmManager:  remove PendingIntent] PendingIntent{d68aaeb: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.919  9382  9382 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 14:06:56.919  9382  9382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 14:06:56.919  9382  9382 D BluetoothAdapter: STATE_ON
,09-23 14:06:56.929  9382  9382 D BluetoothAdapter: STATE_ON
09-23 14:06:56.929  9382  9382 D BluetoothAdapter: STATE_ON
,09-23 14:06:56.929  3421  3981 V AlarmManager:  remove PendingIntent] PendingIntent{6669048: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.929  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 14:06:56.929  9382  9382 D BluetoothAdapter: STATE_ON
09-23 14:06:56.929  3421  4298 V AlarmManager:  remove PendingIntent] PendingIntent{9518ee1: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.929  9382  9382 D BluetoothAdapter: STATE_ON
09-23 14:06:56.929  9382  9382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 14:06:56.929  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 14:06:56.929  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 14:06:56.939  9382  9382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 14:06:56.939  3421  3981 V AlarmManager:  remove PendingIntent] PendingIntent{4489406: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.939  9382  9382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 14:06:56.939  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 14:06:56.939  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 14:06:56.949  9382  9382 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 14:06:56.949  9382  9382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 14:06:56.949  3421  4298 V AlarmManager:  remove PendingIntent] PendingIntent{cc9ea92: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.949  9382  9382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 14:06:56.949  9382  9382 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 14:06:56.949  3421  3981 V AlarmManager:  remove PendingIntent] PendingIntent{65d8c63: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.959  3421  4285 V AlarmManager:  remove PendingIntent] PendingIntent{e2d2060: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.959  3421  4431 V AlarmManager:  remove PendingIntent] PendingIntent{3543919: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.969  3421  4741 V AlarmManager:  remove PendingIntent] PendingIntent{6981dde: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.969  3421  3854 V AlarmManager:  remove PendingIntent] PendingIntent{f928bbf: PendingIntentRecord{f1463c1 com.android.bluetooth broadcastIntent}}
,09-23 14:06:56.999  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:57.189  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:57.369  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:57.459  9382  9382 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 14:06:57.549  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:57.729  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:57.909  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:58.089  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:58.269  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:58.449  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:58.629  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:58.809  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:58.989  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:59.169  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:59.349  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:59.529  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:59.709  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:59.889  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:06:59.999  3421  3817 V AlarmManager: Expired Alarm result :8
,09-23 14:07:00.069  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:00.249  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:00.359  3421  3817 V AlarmManager: Expired Alarm result :4
,09-23 14:07:00.359  3421  3817 V AlarmManager: Send whitelist package alarm :PendingIntent{297b347: PendingIntentRecord{5b7f902 com.samsung.android.app.aodservice broadcastIntent}}
,09-23 14:07:00.359  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-23 14:07:00.359  3950  3950 D KeyguardUpdateMonitor: handleTimeUpdate
,09-23 14:07:00.379  3950  3950 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-23 14:07:00.419  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:00.449  3950  3950 D DateView: received broadcast android.intent.action.TIME_TICK
,09-23 14:07:00.479  4724  4724 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-23 14:07:00.479  4724  4724 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-23 14:07:00.499  4696  4696 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-23 14:07:00.499  4696  4696 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-23 14:07:00.499  3421  3975 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-23 14:07:00.499  3421  3975 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-23 14:07:00.499  3421  3975 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-23 14:07:00.499  3421  3975 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,09-23 14:07:00.499  3164  3164 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-23 14:07:00.509  3421  3975 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-23 14:07:00.509  3421  3975 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-23 14:07:00.509  3421  3975 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-23 14:07:00.509  4696  4696 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@9bfefda, service=Device Physical Context Monitor
09-23 14:07:00.509  4696  4696 I AlpmModeManager: startAlpmMode : state  = BLANK
09-23 14:07:00.509  4696  4696 D DefaultClockView: Window showed. Time views updating
,09-23 14:07:00.519  3421  4767 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
09-23 14:07:00.519  3421  4767 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:07:00.519  3421  4767 D PowerManagerService: mDisplayReady: false
09-23 14:07:00.519  3421  4767 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:07:00.519  3421  4767 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:07:00.519  4696  4696 D AODUpdatePositionController: updatePosition: direction[7] updatePosition: X[33] Y[705] NewPositionTimer[55]
09-23 14:07:00.519  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-23 14:07:00.519  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:07:00.519  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:07:00.519  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:07:00.519  4696  4696 D DefaultClockView: LocalTime Pattern : HH:mm
09-23 14:07:00.519  3421  3603 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 14:07:00.519  3421  3585 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 14:07:00.519  3421  3585 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-23 14:07:00.519  4696  4696 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 14:07 time02: null ampm: null
,09-23 14:07:00.529  3004  3004 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f98043c00
,09-23 14:07:00.529  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-23 14:07:00.539  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-23 14:07:00.539  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:07:00.539  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:07:00.539  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:07:00.539  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:07:00.539  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:07:00.539  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 14:07:00.539  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 14:07:00.539  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:07:00.539  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:07:00.539  3421  3593 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-23 14:07:00.539  3421  3593 D PowerManagerService: mDisplayReady: true
09-23 14:07:00.539  3421  3593 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 14:07:00.539  3164  3207 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,09-23 14:07:00.539  3421  3820 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
09-23 14:07:00.539  3421  3819 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 12, 7, 0,
,09-23 14:07:00.539  3421  3819 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 7, 0
,09-23 14:07:00.549  3164  3208 D Sensorhubs: sendContextData: -63, 14, 12, 7, 0
,09-23 14:07:00.549  3421  3819 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-23 14:07:00.549  3421  3819 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-23 14:07:00.549  3421  3819 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-23 14:07:00.549  3421  3819 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,09-23 14:07:00.549  3421  3819 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
09-23 14:07:00.549  3421  3822 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-23 14:07:00.549  4696  4696 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-23 14:07:00.559  4696  4696 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-23 14:07:00.559  4696  4696 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pt., 23 wrz 14:07
09-23 14:07:00.559  4696  4696 I AODService.ClockTimer: startAlarm : TICK
,09-23 14:07:00.559  3421  3854 V AlarmManager: Add whitelist package alarm :PendingIntent{48439ea: PendingIntentRecord{5b7f902 com.samsung.android.app.aodservice broadcastIntent}}
,09-23 14:07:00.559  4696  4696 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,09-23 14:07:00.559  4696  4696 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
09-23 14:07:00.559  3421  4767 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-23 14:07:00.559  3421  4767 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-23 14:07:00.559  3421  4419 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,09-23 14:07:00.569  4696  4696 I AODService: onSContextChanged: AODScreenShown state is already true
,09-23 14:07:00.569  4696  4696 D DefaultClockView: RootView invalidate()
09-23 14:07:00.569  3421  4974 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,09-23 14:07:00.599  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:00.719  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
,09-23 14:07:00.719  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 14:07:00.719  3421  3421 D PowerManagerService: mDisplayReady: false
09-23 14:07:00.719  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 14:07:00.719  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-23 14:07:00.719  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 14:07:00.719  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:07:00.719  3004  3004 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f98043c00
09-23 14:07:00.719  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:07:00.719  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-23 14:07:00.719  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-23 14:07:00.719  3421  3603 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 14:07:00.719  3421  3585 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 14:07:00.719  3421  3585 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-23 14:07:00.759  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:07:00.759  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:07:00.759  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:07:00.759  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 14:07:00.759  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:07:00.759  3421  3593 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 14:07:00.759  3421  3593 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 14:07:00.759  3421  3593 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 14:07:00.759  3421  3593 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 14:07:00.759  3421  3593 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 14:07:00.759  3421  3593 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 14:07:00.759  3421  3593 D PowerManagerService: mDisplayReady: true
09-23 14:07:00.759  3421  3593 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 14:07:00.789  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:00.969  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:01.149  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:01.329  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:01.509  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:01.689  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 14:07:01.869  3421  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
