#### Test 85046911b09b63d_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-23 09:56:24.815  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:24.995  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:25.175  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:25.355  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:25.525  9348  9348 I FIPS_bssl: FIPS approved mode (1) | 9348 | app_process
09-23 09:56:25.535  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:25.535  9348  9348 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 09:56:25.535  9348  9348 D AndroidRuntime: CheckJNI is OFF
09-23 09:56:25.535  9348  9348 D AndroidRuntime: readGMSProperty: start
09-23 09:56:25.535  9348  9348 D AndroidRuntime: readGMSProperty: already setted!!
09-23 09:56:25.535  9348  9348 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 09:56:25.535  9348  9348 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 09:56:25.535  9348  9348 D AndroidRuntime: readGMSProperty: end
09-23 09:56:25.535  9348  9348 D AndroidRuntime: addProductProperty: start
09-23 09:56:25.555  9348  9348 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 09:56:25.585  9348  9348 I Radio-JNI: register_android_hardware_Radio DONE
09-23 09:56:25.585  9348  9348 E AffinityControl: AffinityControl: registerfunction enter
09-23 09:56:25.595  9348  9348 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-23 09:56:25.645  3436  3981 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-23 09:56:25.645  3436  3981 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 09:56:25.665  3436  3981 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:56:25.665  3436  3981 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:56:25.665  3436  3981 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-23 09:56:25.675  3436  3981 D ActivityManager: mDVFSHelper.acquire()
09-23 09:56:25.675  3436  3981 V WindowManager: addAppToken: AppWindowToken{d0b345cb5 token=Token{e0760ec ActivityRecord{de5879f u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-23 09:56:25.685  3436  3584 I InjectionManager: Inside getClassLibPath caller 
09-23 09:56:25.695  3436  3584 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:56:25.695  3436  3584 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ee06d6d V.E...... R.....ID 0,0-0,0}
09-23 09:56:25.695  9357  9357 E Zygote  : v2
09-23 09:56:25.695  9357  9357 I libpersona: KNOX_SDCARD checking this for 10171
09-23 09:56:25.695  9357  9357 I libpersona: KNOX_SDCARD not a persona
09-23 09:56:25.695  3436  3584 W WindowManager: Failed looking up window
09-23 09:56:25.695  3436  3584 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@633fda2 does not exist
09-23 09:56:25.695  3436  3584 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 09:56:25.695  3436  3584 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 09:56:25.695  3436  3584 D ISSUE_DEBUG: InputChannelName : 8b68a33 Starting com.test.thalitest
09-23 09:56:25.695  9357  9357 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 09:56:25.705  9357  9357 E Zygote  : accessInfo : 0
09-23 09:56:25.705  9357  9357 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-23 09:56:25.705  3436  3981 I ActivityManager: Start proc 9357:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-23 09:56:25.705  3436  3981 D InputDispatcher: Focused application set to: xxxx
09-23 09:56:25.705  9348  9348 D AndroidRuntime: Shutting down VM
09-23 09:56:25.705  3436  3854 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-23 09:56:25.705  3005  3005 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-23 09:56:25.715  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:25.725  6091  6091 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:56:25.725  9357  9357 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 09:56:25.725  9357  9357 D ActivityThread: Added TimaKeyStore provider
09-23 09:56:25.735  3436  4436 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436
09-23 09:56:25.735  3436  4436 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:56:25.735  3436  4436 D PowerManagerService: mDisplayReady: false
09-23 09:56:25.735  3436  4436 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:56:25.735  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:56:25.735  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9fe03c00
09-23 09:56:25.735  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:56:25.735  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 09:56:25.735  3436  4436 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:56:25.735  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:25.735  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:25.735  3436  3603 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 09:56:25.735  6091  6091 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:56:25.735  3436  4965 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436
09-23 09:56:25.735  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:56:25.735  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:56:25.735  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:56:25.735  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:25.735  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:56:25.735  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:25.735  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:56:25.735  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:56:25.735  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:25.735  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:25.735  3436  3588 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:56:25.735  3436  3588 D PowerManagerService: mDisplayReady: true
09-23 09:56:25.745  3436  4056 V WindowStateAnimator: Finishing drawing window Window{e8a0d64 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 09:56:25.735  3436  3588 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:56:25.755  3436  4966 D ActivityManager:  Launching com.test.thalitest, updated priority
09-23 09:56:25.765  4278  4278 V ActivityThread: updateVisibility : ActivityRecord{bab85c9 token=android.os.BinderProxy@5f62c55 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-23 09:56:25.765  3436  3436 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-23 09:56:25.765  3436  3555 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-23 09:56:25.775  3005  3073 D libEGL  : eglTerminate EGLDisplay = 0x7f9953ee78
09-23 09:56:25.775  3005  3073 D libEGL  : eglTerminate EGLDisplay = 0x7f9953ee78
09-23 09:56:25.785  3436  3981 V WindowStateAnimator: Finishing drawing window Window{f3226f6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 09:56:25.785  6091  6091 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:56:25.785  3005  4336 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-23 09:56:25.785  3005  4316 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-23 09:56:25.795  6091  6091 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:56:25.795  4278  4278 D Launcher: onTrimMemory. Level: 20
09-23 09:56:25.795  6091  6091 V ActivityThread: updateVisibility : ActivityRecord{930b72e token=android.os.BinderProxy@c8cfee3 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-23 09:56:25.795  3005  4336 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-23 09:56:25.795  3005  4316 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-23 09:56:25.795  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff7276fc8
09-23 09:56:25.795  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff7276f98
09-23 09:56:25.795  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff7276f98
09-23 09:56:25.795  3005  4316 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-23 09:56:25.795  3005  4316 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-23 09:56:25.825  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff7276fc8
09-23 09:56:25.835  3436  5989 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:10), CP = 215, CUR = 7, LCD = 1
09-23 09:56:25.885  3436  3436 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436 (0x0)
09-23 09:56:25.895  3436  3436 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436 (0x0)
09-23 09:56:25.895  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:56:25.895  3436  3436 D PowerManagerService: mDisplayReady: false
09-23 09:56:25.895  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:56:25.895  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:56:25.895  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:25.895  3436  3436 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:56:25.895  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9fe03c00
09-23 09:56:25.895  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:56:25.895  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 09:56:25.895  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:25.895  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:25.895  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:56:25.895  3436  3603 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 09:56:25.895  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:56:25.895  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:56:25.895  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:56:25.895  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:25.895  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:25.895  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:56:25.895  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:56:25.895  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:25.895  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:25.895  3436  3588 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:56:25.895  3436  3588 D PowerManagerService: mDisplayReady: true
09-23 09:56:25.895  3436  3588 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:56:26.075  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:26.095  3436  4966 I WindowManager: Screenshot max retries 4 of Token{e0760ec ActivityRecord{de5879f u0 com.test.thalitest/.MainActivity t4}} appWin=Window{8b68a33 u0 d0 Starting com.test.thalitest} drawState=1
09-23 09:56:26.095  3436  3584 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:56:26.095  3436  3436 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:56:26.095  3436  3584 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 09:56:26.105  3436  5989 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:56:26.105  3436  3854 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-23 09:56:26.105  3436  5989 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:56:26.105  3436  3436 I KnoxTimeoutHandler: SD activityfalse
09-23 09:56:26.125  9357  9357 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 09:56:26.125  3436  4291 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-23 09:56:26.125  9357  9357 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-23 09:56:26.135  3436  5989 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 09:56:26.135  3436  5989 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:56:26.135  3436  3584 V WindowStateAnimator: Finishing drawing window Window{8b68a33 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-23 09:56:26.135  3436  3584 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:56:26.135  3436  3436 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:56:26.135  9357  9357 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:56:26.145  3436  3436 I KnoxTimeoutHandler: SD activityfalse
09-23 09:56:26.145  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7ff7276ea8
09-23 09:56:26.145  3436  5989 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 09:56:26.145  3436  5989 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:56:26.145  3436  5989 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:56:26.145  9357  9357 I InjectionManager: Inside getClassLibPath caller 
09-23 09:56:26.165  9357  9357 D InjectionManager: InjectionManager
09-23 09:56:26.165  9357  9357 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-23 09:56:26.165  9357  9357 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-23 09:56:26.165  9357  9357 I InjectionManager: featureStore :{}
09-23 09:56:26.175  9357  9357 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 09:56:26.175  9357  9357 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-23 09:56:26.175  9357  9357 D RelationGraph: garbageCollect()
09-23 09:56:26.185  9357  9357 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 09:56:26.215  9357  9357 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-23 09:56:26.255  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:26.255  9357  9357 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-23 09:56:26.265  9357  9357 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:56:26.265  9357  9357 I InjectionManager: Inside getClassLibPath caller 
09-23 09:56:26.265  9357  9357 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-23 09:56:26.325  9357  9357 I cr_LibraryLoader: Time to load native libraries: 35 ms (timestamps 1705-1740)
09-23 09:56:26.325  9357  9357 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 09:56:26.355  3436  3878 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-23 09:56:26.395  9357  9372 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-23 09:56:26.415  9357  9357 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4eb88dc}
09-23 09:56:26.415  9357  9357 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 09:56:26.435  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:26.435  9357  9357 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 09:56:26.455  3436  3878 I MdnieScenarioControlService: mGameModeLauncher : false
09-23 09:56:26.455  3436  3878 I MdnieScenarioControlService: setUIMode
09-23 09:56:26.465  9357  9357 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-23 09:56:26.585  3436  3555 W ActivityManager: Activity pause timeout for ActivityRecord{de5879f u0 com.test.thalitest/.MainActivity t4}
09-23 09:56:26.615  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:26.615  9357  9357 D libEGL  : eglInitialize EGLDisplay = 0xffc2f47c
09-23 09:56:26.695  3436  4291 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-23 09:56:26.695  3436  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-23 09:56:26.785  9357  9357 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-23 09:56:26.795  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:26.805  9357  9357 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-23 09:56:26.815  9357  9357 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-23 09:56:26.845  9357  9357 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-23 09:56:26.895  9357  9357 D Activity: performCreate Call Injection manager
09-23 09:56:26.895  9357  9357 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-23 09:56:26.895  9357  9357 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:56:26.905  9357  9357 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2410b4b I.E...... R.....ID 0,0-0,0}
09-23 09:56:26.905  9357  9409 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-23 09:56:26.915  3436  3487 W WindowManager: Failed looking up window
09-23 09:56:26.915  3436  3487 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@d4af502 does not exist
09-23 09:56:26.915  3436  3487 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 09:56:26.915  3436  3487 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 09:56:26.915  3436  3487 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 09:56:26.915  3436  3487 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-23 09:56:26.915  3436  3487 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-23 09:56:26.915  3436  3487 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-23 09:56:26.915  3436  4380 D ISSUE_DEBUG: InputChannelName : 11d1e13 com.test.thalitest/com.test.thalitest.MainActivity
09-23 09:56:26.925  3436  3976 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-23 09:56:26.925  3436  3976 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:56:26.925  3436  3436 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:56:26.925  3436  3436 I KnoxTimeoutHandler: Shared devices show user statefalse
09-23 09:56:26.925  9357  9357 V ActivityThread: updateVisibility : ActivityRecord{ccad641 token=android.os.BinderProxy@104e0f3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-23 09:56:26.935  9357  9372 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-23 09:56:26.965  9357  9357 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9357
09-23 09:56:26.965  3436  4277 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9357 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 09:56:26.965  3436  3865 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-23 09:56:26.965  3436  3865 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-23 09:56:26.975  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:26.975  3436  3865 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-23 09:56:26.985  3436  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-23 09:56:26.985  3436  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 09:56:26.985  9357  9357 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:56:26.985  3436  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 09:56:26.995  3436  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 09:56:26.995  3436  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-23 09:56:26.995  3436  3865 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 09:56:27.005  3005  3005 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
09-23 09:56:27.025  9357  9409 D libEGL  : eglInitialize EGLDisplay = 0xdc33f7c4
09-23 09:56:27.025  9357  9409 I OpenGLRenderer: Initialized EGL, version 1.4
09-23 09:56:27.025  9357  9409 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-23 09:56:27.035  3436  4388 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436
09-23 09:56:27.035  3436  4388 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:56:27.035  3436  4388 D PowerManagerService: mDisplayReady: false
09-23 09:56:27.035  3436  4388 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:56:27.035  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:56:27.035  3436  4388 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:56:27.035  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:56:27.035  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:27.035  3005  3005 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9fe03c00
09-23 09:56:27.035  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:27.035  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 09:56:27.035  3436  3603 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 09:56:27.035  3436  3584 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 09:56:27.035  3436  3584 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-23 09:56:27.045  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:56:27.045  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:56:27.045  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:27.045  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:27.055  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:56:27.045  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:56:27.055  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:56:27.045  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:56:27.045  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:27.045  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:27.045  3436  3588 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:56:27.055  3436  3588 D PowerManagerService: mDisplayReady: true
09-23 09:56:27.055  3436  3588 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:56:27.065  9357  9357 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-23 09:56:27.075  3436  4966 V WindowStateAnimator: Finishing drawing window Window{11d1e13 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-23 09:56:27.075  9357  9357 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 09:56:27.085  9357  9413 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 09:56:27.085  9357  9413 D libEGL  : eglInitialize EGLDisplay = 0xda7ec3f4
09-23 09:56:27.085  3436  4413 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436
09-23 09:56:27.085  3436  3584 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:56:27.085  3436  3436 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:56:27.085  3436  3584 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +998ms (total +1s411ms)
09-23 09:56:27.085  3436  3436 I KnoxTimeoutHandler: SD activityfalse
09-23 09:56:27.085  3436  3584 D ActivityManager: mDVFSHelper.release()
09-23 09:56:27.085  3436  3584 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{de5879f u0 com.test.thalitest/.MainActivity t4} time:212508
09-23 09:56:27.085  3436  4277 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436
09-23 09:56:27.085  3436  3584 D ViewRootImpl: #3 mView = null
09-23 09:56:27.085  3005  4336 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-23 09:56:27.095  3005  4336 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
09-23 09:56:27.095  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7ff7276fc8
09-23 09:56:27.095  9357  9413 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-23 09:56:27.095  3436  4435 V WindowStateAnimator: Finishing drawing window Window{11d1e13 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-23 09:56:27.095  3436  5990 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 09:56:27.105  9357  9357 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@104e0f3 time:212521
09-23 09:56:27.145  9357  9357 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9357
09-23 09:56:27.155  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:27.235  3436  3436 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436 (0x0)
09-23 09:56:27.235  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:56:27.235  3436  3436 D PowerManagerService: mDisplayReady: false
09-23 09:56:27.235  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:56:27.235  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:56:27.235  3436  3436 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:56:27.235  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:56:27.235  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:27.235  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:27.235  3436  3603 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 09:56:27.245  3005  3005 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9fe03c00
09-23 09:56:27.245  3436  3584 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 09:56:27.245  3005  3005 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 09:56:27.245  3436  3584 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-23 09:56:27.255  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:56:27.255  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:56:27.255  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:27.255  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:56:27.255  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:27.255  3436  3588 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:56:27.255  3436  3588 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:56:27.255  3436  3588 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:56:27.255  3436  3588 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:56:27.255  3436  3588 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:56:27.255  3436  3588 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:56:27.255  3436  3588 D PowerManagerService: mDisplayReady: true
09-23 09:56:27.255  3436  3588 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:56:27.335  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:27.375  9357  9357 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-23 09:56:27.465  9357  9420 D jxcore_app_log: JniHelper::setJavaVM(0xf4b74000), pthread_self() = -637011664
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4dc58 added. We now have 1 listener(s)
09-23 09:56:27.475  9357  9420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
09-23 09:56:27.475  9357  9420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 09:56:27.475  9357  9420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:56:27.475  9357  9420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 09:56:27.475  9357  9420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64c9217 added. We now have 1 listener(s)
09-23 09:56:27.475  9357  9420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:56:27.485  9357  9420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:56:27.485  9357  9420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 09:56:27.485  9357  9420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 09:56:27.485  9357  9420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 09:56:27.485  9357  9420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-23 09:56:27.485  9357  9420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:56:27.485  9357  9420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
09-23 09:56:27.495  9357  9420 D BluetoothAdapter: STATE_ON
09-23 09:56:27.495  9357  9420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:56:27.495  9357  9420 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:56:27.495  9357  9420 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 09:56:27.495  9357  9420 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:56:27.495  9357  9420 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 09:56:27.505  9357  9357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:56:27.505  9357  9357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:56:27.515  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:56:27.525  9357  9357 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-23 09:56:27.595  4021  4021 D Recents : onTaskStackChanged
09-23 09:56:27.595  4021  4021 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-23 09:56:27.605  4021  4021 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:27.665  3154  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 09:56:27.695  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:27.865  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:27.875  9357  9421 W jxcore-log: Initializing JXcore engine
09-23 09:56:27.875  9357  9421 W jxcore-log: JXcore engine is ready
,09-23 09:56:27.885  3436  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-23 09:56:27.885  3436  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-23 09:56:27.885  3436  3981 D BatteryService: online:4, current avg:-3, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-70
09-23 09:56:27.885  3436  3981 D BatteryService: stay LED for fully charged
09-23 09:56:27.885  3436  3436 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-23 09:56:27.895  3436  3436 I MotionRecognitionService: Plugged
09-23 09:56:27.895  3436  3436 D MotionRecognitionService:   cableConnection= 1
09-23 09:56:27.895  3436  3436 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-23 09:56:27.895  3436  3436 D MotionRecognitionService: skip setTransmitPower. 
,09-23 09:56:27.895  4961  4961 E audit   : type=1400 msg=audit(1474617387.895:264): avc:  denied  { ioctl } for  pid=9421 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1300 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 09:56:27.895  4961  4961 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 09:56:27.895  4961  4961 E audit   : type=1300 msg=audit(1474617387.895:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d9eff3c8 items=0 ppid=3180 pid=9421 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 09:56:27.895  4961  4961 E audit   : type=1327 msg=audit(1474617387.895:264): proctitle="com.test.thalitest"
09-23 09:56:27.895  4961  4961 E audit   : type=1320 msg=audit(1474617387.895:264): 
09-23 09:56:27.895  4961  4961 E audit   : type=1400 msg=audit(1474617387.895:265): avc:  denied  { ioctl } for  pid=9421 comm="Thread-160" path="socket:[12212]" dev="sockfs" ino=12212 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 09:56:27.895  4961  4961 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 09:56:27.895  4961  4961 E audit   : type=1300 msg=audit(1474617387.895:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d9eff3c8 items=0 ppid=3180 pid=9421 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 09:56:27.895  4961  4961 E audit   : type=1327 msg=audit(1474617387.895:265): proctitle="com.test.thalitest"
09-23 09:56:27.895  4961  4961 E audit   : type=1320 msg=audit(1474617387.895:265): 
,09-23 09:56:27.895  3436  3859 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-23 09:56:27.895  3935  3935 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-23 09:56:27.895  3935  3935 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-23 09:56:27.895  3935  3935 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-23 09:56:27.895  9357  9421 W jxcore-log: Starting JXcore engine
,09-23 09:56:27.895  4999  4999 D CommonServiceConfiguration: getStringValueSetting
09-23 09:56:27.905  4954  4954 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-23 09:56:27.905  4954  5379 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-23 09:56:27.905  4999  4999 D BatteryMonitor: new battery level: 100
,09-23 09:56:27.905  4689  4689 D BatteryController: saveBatteryData : level[100], status[5]
09-23 09:56:27.905  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 09:56:27.905  3935  3935 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-23 09:56:27.935  9357  9421 W jxcore-log: Platform android
09-23 09:56:27.935  9357  9421 W jxcore-log: 
,09-23 09:56:27.935  9357  9421 W jxcore-log: Process ARCH arm
09-23 09:56:27.935  9357  9421 W jxcore-log: 
,09-23 09:56:28.005  9357  9421 I jxcore-log: JXcore Cordova bridge is ready!
09-23 09:56:28.005  9357  9421 I jxcore-log: 
,09-23 09:56:28.005  9357  9421 W jxcore-log: JXcore engine is started
,09-23 09:56:28.015  9357  9420 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 09:56:28.015  9357  9357 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 09:56:28.055  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:28.235  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:28.415  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:28.595  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:28.685  3436  3903 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-23 09:56:28.775  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:28.955  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:29.115  3436  5989 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-23 09:56:29.135  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:29.315  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:29.495  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:29.675  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:29.855  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:30.035  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:30.215  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:30.395  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:30.575  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:30.755  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:30.935  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:31.115  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:31.295  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:31.475  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:31.655  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:31.835  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:32.005  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:32.165  3436  5989 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-23 09:56:32.195  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:32.285  9357  9421 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 09:56:32.285  9357  9421 I jxcore-log: 
,09-23 09:56:32.285  9357  9421 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 09:56:32.285  9357  9421 I jxcore-log: 
,09-23 09:56:32.295  9357  9421 D BluetoothAdapter: STATE_ON
,09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:56:32.295  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:56:32.295  9357  9421 D BluetoothAdapter: STATE_ON
,09-23 09:56:32.305  9357  9421 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:56:32.305  9357  9421 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 09:56:32.305  9357  9421 I jxcore-log: 
09-23 09:56:32.305  9357  9421 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 09:56:32.305  9357  9421 I jxcore-log: 
,09-23 09:56:32.375  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:32.535  9357  9421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:56:32.535  9357  9421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51f8f2f added. We now have 2 listener(s)
09-23 09:56:32.535  9357  9421 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 09:56:32.535  9357  9421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:56:32.535  9357  9421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:56:32.535  9357  9421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:56:32.535  9357  9421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96a793c added. We now have 2 listener(s)
09-23 09:56:32.535  9357  9421 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:56:32.535  9357  9421 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:56:32.535  9357  9421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:56:32.545  9357  9421 D BluetoothAdapter: STATE_ON
,09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:56:32.545  9357  9421 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:56:32.555  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:32.555  9357  9421 D BluetoothAdapter: STATE_ON
,09-23 09:56:32.555  9357  9421 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:56:32.555  9357  9421 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:56:32.555  9357  9421 D ExecuteNativeTests: Running unit tests
09-23 09:56:32.555  9357  9421 D BluetoothAdapter: enable()
,09-23 09:56:32.565  9357  9421 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 09:56:32.565  9357  9357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:56:32.565  9357  9357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:56:32.575  9357  9421 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-23 09:56:32.575  3436  3555 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{459b203 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d958b3b 4987:com.samsung.android.providers.context/u0a7}
09-23 09:56:32.585  3436  3981 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-23 09:56:32.585  3436  3981 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-23 09:56:32.585  3436  3981 D WifiService: setWifiEnabled: true pid=9357, uid=10171
,09-23 09:56:32.595  3436  3981 W ActivityManager: Permission Denial: getCurrentUser() from pid=9357, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-23 09:56:32.595  3436  3856 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-23 09:56:32.595  3436  3981 W WifiService: Failed getting userId using ActivityManagerNative
09-23 09:56:32.595  3436  3981 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9357, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-23 09:56:32.595  3436  3981 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-23 09:56:32.595  3436  3981 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-23 09:56:32.595  3436  3981 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-23 09:56:32.595  3436  3981 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-23 09:56:32.595  3436  3981 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 09:56:32.595  3436  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-23 09:56:32.605  3436  3981 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
09-23 09:56:32.605  3436  3981 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-23 09:56:32.605  3436  3856 D WifiBigDataLog: init : 
,09-23 09:56:32.605  3436  3859 D WifiController: [FCC]setFccChannel() is called !!!
09-23 09:56:32.605  3436  3859 D WifiStateMachine: setFccChannel: channel = 0
09-23 09:56:32.605  3436  3859 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-23 09:56:32.605  3436  3856 D WifiStateMachine: setFccChannelNative: channel = 0
,09-23 09:56:32.605  3436  3856 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-23 09:56:32.615  3436  3555 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fbfe580 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d958b3b 4987:com.samsung.android.providers.context/u0a7}
,09-23 09:56:32.735  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:32.915  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:33.095  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:33.275  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:33.455  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:33.635  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:33.815  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:33.995  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:34.175  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:34.355  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:34.535  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:34.715  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:34.895  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:35.075  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:35.255  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:35.435  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:35.615  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:35.725  3436  3612 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-23 09:56:35.755  3436  3612 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 09:56:35.795  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:35.975  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:36.115  3436  5989 D SSRM:n  : SIOP:: AP = 290, PST = 260 (W:6), CP = 223, CUR = -3, LCD = 1
,09-23 09:56:36.155  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:36.335  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:36.515  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:36.685  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:36.875  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:37.055  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:37.235  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:37.415  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:37.595  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:37.775  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:37.905  3436  4146 E Watchdog: !@Sync 7 [09-23 09:56:37.917]
,09-23 09:56:37.955  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:38.135  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:38.315  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:38.495  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:38.665  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:38.855  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:39.025  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:39.215  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:39.395  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:39.565  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:39.745  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:39.935  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:40.115  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:40.295  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:40.475  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:40.645  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:40.835  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:41.005  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:41.185  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:41.365  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:41.545  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:41.725  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:41.905  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:42.085  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:42.265  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:42.445  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:42.615  9357  9421 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 09:56:42.625  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:42.655  9357  9421 I jxcore-log: *Native tests were executed*
09-23 09:56:42.655  9357  9421 I jxcore-log: 
09-23 09:56:42.655  9357  9421 I jxcore-log: Total number of executed tests:  1
09-23 09:56:42.655  9357  9421 I jxcore-log: 
09-23 09:56:42.655  9357  9421 I jxcore-log: Number of passed tests:  1
09-23 09:56:42.655  9357  9421 I jxcore-log: 
,09-23 09:56:42.655  9357  9421 I jxcore-log: Number of failed tests:  0
09-23 09:56:42.655  9357  9421 I jxcore-log: 
09-23 09:56:42.655  9357  9421 I jxcore-log: Number of ignored tests:  0
09-23 09:56:42.655  9357  9421 I jxcore-log: 
,09-23 09:56:42.665  9357  9421 I jxcore-log: Total duration:  18
09-23 09:56:42.665  9357  9421 I jxcore-log: 
,09-23 09:56:42.665  9357  9421 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 09:56:42.665  9357  9421 I jxcore-log: 
,09-23 09:56:42.665  9357  9421 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 09:56:42.665  9357  9421 I jxcore-log: 
,09-23 09:56:42.675  9357  9421 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 09:56:42.675  9357  9421 I jxcore-log: 
,09-23 09:56:42.685  9357  9357 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-23 09:56:42.715  3154  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 09:56:42.805  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:42.985  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:43.115  9426  9426 I FIPS_bssl: FIPS approved mode (1) | 9426 | app_process
,09-23 09:56:43.125  9426  9426 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 09:56:43.125  9426  9426 D AndroidRuntime: CheckJNI is OFF
09-23 09:56:43.125  9426  9426 D AndroidRuntime: readGMSProperty: start
09-23 09:56:43.125  9426  9426 D AndroidRuntime: readGMSProperty: already setted!!
09-23 09:56:43.125  9426  9426 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 09:56:43.125  9426  9426 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 09:56:43.125  9426  9426 D AndroidRuntime: readGMSProperty: end
09-23 09:56:43.125  9426  9426 D AndroidRuntime: addProductProperty: start
,09-23 09:56:43.145  9426  9426 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 09:56:43.165  9426  9426 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 09:56:43.165  9426  9426 E AffinityControl: AffinityControl: registerfunction enter
,09-23 09:56:43.165  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:43.175  9426  9426 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 09:56:43.185  3436  4291 D PackageManager: START PACKAGE DELETE: observer{228714425}
09-23 09:56:43.185  3436  4291 D PackageManager: pkg{<packageName>}
09-23 09:56:43.185  3436  4291 D PackageManager: user{0}
09-23 09:56:43.185  3436  4291 D PackageManager: caller{2000}
09-23 09:56:43.185  3436  4291 D PackageManager: flags{2}
,09-23 09:56:43.185  3436  4291 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-23 09:56:43.185  3436  4291 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-23 09:56:43.185  3436  4291 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-23 09:56:43.185  3436  4291 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-23 09:56:43.185  3436  4291 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-23 09:56:43.185  3436  3612 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-23 09:56:43.185  3436  3612 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-23 09:56:43.185  3436  3612 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-23 09:56:43.185  3436  3612 D ApplicationPolicy: getApplicationUninstallationEnabled
09-23 09:56:43.185  3436  3612 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-23 09:56:43.185  3436  3612 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-23 09:56:43.185  3436  3612 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-23 09:56:43.185  3436  3612 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
09-23 09:56:43.185  3436  3612 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-23 09:56:43.185  3436  3612 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-23 09:56:43.185  3436  3555 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-23 09:56:43.185  3436  3555 I ActivityManager: Killing 9357:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-23 09:56:43.195  3436  3555 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-23 09:56:43.205  3436  3555 D ActivityManager: mDVFSHelper.acquire()
,09-23 09:56:43.215  3436  3584 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-23 09:56:43.215  3436  3584 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-23 09:56:43.215  3436  3584 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-23 09:56:43.215  3436  3584 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-23 09:56:43.215  3436  3584 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-23 09:56:43.215  3436  3584 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 09:56:43.215  3436  3584 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:56:43.215  3436  3584 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-23 09:56:43.215  3436  3584 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 09:56:43.215  3436  3584 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 09:56:43.215  3436  3584 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:56:43.215  3436  3584 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8555e7b V.E...... R.....ID 0,0-0,0}
,09-23 09:56:43.225  3436  3584 W WindowManager: Failed looking up window
09-23 09:56:43.225  3436  3584 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d44e498 does not exist
09-23 09:56:43.225  3436  3584 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 09:56:43.225  3436  3584 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 09:56:43.225  3436  3584 W WindowManager: view not successfully added to wm, removing view
09-23 09:56:43.225  3436  3584 D ViewRootImpl: #3 mView = null
,09-23 09:56:43.225  9435  9435 E Zygote  : v2
09-23 09:56:43.225  9435  9435 I libpersona: KNOX_SDCARD checking this for 10171
09-23 09:56:43.225  9435  9435 I libpersona: KNOX_SDCARD not a persona
09-23 09:56:43.225  9435  9435 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-23 09:56:43.235  9435  9435 E Zygote  : accessInfo : 0
09-23 09:56:43.235  9435  9435 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-23 09:56:43.235  3436  3612 D AASAinstall: there is not AASApackages.xml file
,09-23 09:56:43.235  3436  3555 I ActivityManager: Start proc 9435:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
,09-23 09:56:43.245  3436  3555 I ActivityManager:   Force finishing activity ActivityRecord{de5879f u0 com.test.thalitest/.MainActivity t4}
09-23 09:56:43.245  3436  3555 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-23 09:56:43.265  9435  9435 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 09:56:43.265  9435  9435 D ActivityThread: Added TimaKeyStore provider
,09-23 09:56:43.335  3436  4388 I WindowState: WIN DEATH: Window{11d1e13 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-23 09:56:43.335  3436  4291 D GraphicsStats: Buffer count: 5
,09-23 09:56:43.335  3436  4290 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@98bd4f1)
09-23 09:56:43.335  3436  3865 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 09:56:43.335  3436  3865 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 09:56:43.345  3436  3865 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-23 09:56:43.345  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:43.355  3005  4336 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
,09-23 09:56:43.355  3005  3016 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-23 09:56:43.365  3436  6036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-23 09:56:43.365  3005  3016 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-23 09:56:43.525  3436  3612 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-23 09:56:43.525  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:43.585  3436  3612 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 09:56:43.585  3167  3167 W keystore: ENTER clear_uid from uid 1000 for 10171
,09-23 09:56:43.585  3436  3612 I art     : Waiting for a blocking GC Explicit
,09-23 09:56:43.595  3005  3005 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-23 09:56:43.635  4278  4278 D Launcher: onRestart, Launcher: 112857694
,09-23 09:56:43.645  3436  3487 V WindowStateAnimator: Finishing drawing window Window{f3226f6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-23 09:56:43.645  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7ff7276ea8
,09-23 09:56:43.655  3436  3446 I art     : Background sticky concurrent mark sweep GC freed 193337(12MB) AllocSpace objects, 89(1920KB) LOS objects, 25% free, 41MB/56MB, paused 6.067ms total 132.102ms
09-23 09:56:43.655  3436  3612 I art     : WaitForGcToComplete blocked for 72.180ms for cause Explicit
09-23 09:56:43.655  3436  3612 I art     : Starting a blocking GC Explicit
,09-23 09:56:43.705  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:43.845  3436  3612 I art     : Explicit concurrent mark sweep GC freed 104636(6MB) AllocSpace objects, 4(1872KB) LOS objects, 32% free, 33MB/49MB, paused 1.612ms total 186.171ms
,09-23 09:56:43.885  3436  3612 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-23 09:56:43.885  3436  3612 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-23 09:56:43.885  3436  3612 D AASAinstall: there is not AASApackages.xml file
09-23 09:56:43.885  3436  3612 D PackageManager: result of delete: 1{228714425}
,09-23 09:56:43.885  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:43.885  3436  3612 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-23 09:56:43.885  3436  3612 D PackageManager: userId{-1}
09-23 09:56:43.885  3436  3612 D PackageManager: andCode{true}
09-23 09:56:43.885  9426  9426 I art     : System.exit called, status: 0
09-23 09:56:43.885  9426  9426 I AndroidRuntime: VM exiting with result code 0.
,09-23 09:56:43.925  3436  3555 I WindowManager: Screenshot max retries 4 of Token{2c9b659 ActivityRecord{4c14aa0 u0 com.samsung.android.MtpApplication/.USBConnection t3}} appWin=Window{f3226f6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=2
,09-23 09:56:43.925  3436  3436 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-23 09:56:43.955  3436  3584 I Choreographer: Skipped 34 frames!  The application may be doing too much work on its main thread.
09-23 09:56:43.955  3436  3555 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-23 09:56:43.955  4278  4278 D Launcher: onStart, Launcher: 112857694
09-23 09:56:43.955  4278  4278 D Launcher.HomeView: onStart
,09-23 09:56:43.955  4278  4278 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-23 09:56:43.965  4278  4278 V ActivityThread: updateVisibility : ActivityRecord{bab85c9 token=android.os.BinderProxy@5f62c55 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-23 09:56:43.965  4278  4278 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-23 09:56:43.965  4278  4278 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-23 09:56:43.965  4278  4278 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,09-23 09:56:43.975  4278  4278 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-23 09:56:43.975  4278  4278 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-23 09:56:43.975  4278  4278 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
,09-23 09:56:43.975  4278  4278 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-23 09:56:43.975  4278  4278 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-23 09:56:43.975  4278  4278 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-23 09:56:43.985  3436  3612 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-23 09:56:43.985  3436  3612 I ActivityManager: Killing 9435:com.test.thalitest/u0a171 (adj -100): stop com.test.thalitest cause pkg removed
,09-23 09:56:43.985  3436  3612 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-23 09:56:43.995  3005  3005 I SurfaceFlinger: id=21 createSurf (1440x2560),1 flag=4, MauncherAct
09-23 09:56:43.995  3436  3612 I ActivityManager:   Force finishing activity ActivityRecord{de5879f u0 com.test.thalitest/.MainActivity t4 f}
09-23 09:56:43.995  3436  3612 W ActivityManager: Duplicate finish request for ActivityRecord{de5879f u0 com.test.thalitest/.MainActivity t4 f}
,09-23 09:56:44.015  8914  9451 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-23 09:56:44.015  4278  4590 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-23 09:56:44.035  8914  9451 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-23 09:56:44.035  8914  9451 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-23 09:56:44.055  3436  3981 W ActivityManager: No pending application record for pid 9435 (IApplicationThread android.app.ApplicationThreadProxy@2f7cf2d); dropping process
,09-23 09:56:44.055  3436  3555 D InputDispatcher: Focused application released
,09-23 09:56:44.065  3436  4291 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-23 09:56:44.065  3436  4291 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:56:44.065  3436  3436 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-23 09:56:44.065  3436  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:56:44.065  3436  3584 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:56:44.065  3436  3584 D ActivityManager: mDVFSHelper.release()
09-23 09:56:44.065  3436  3584 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4c14aa0 u0 com.samsung.android.MtpApplication/.USBConnection t3} time:229488
,09-23 09:56:44.075  3436  3436 I KnoxTimeoutHandler: Shared devices show user statefalse
09-23 09:56:44.075  3436  3436 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
09-23 09:56:44.075  3436  3436 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-23 09:56:44.075  3005  3005 I SurfaceFlinger: id=22 createSurf (1592x384),1 flag=4, VSBConnecti
,09-23 09:56:44.085  3436  3436 I KnoxTimeoutHandler: SD activityfalse
,09-23 09:56:44.085  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-23 09:56:44.085  3436  3550 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-23 09:56:44.095  3436  3436 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.095  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-23 09:56:44.095  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-23 09:56:44.095  3436  3550 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.095  3436  3436 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:56:44.095  3436  3487 V WindowStateAnimator: Finishing drawing window Window{9fbe4e2 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,09-23 09:56:44.105  3436  3550 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-23 09:56:44.105  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-23 09:56:44.105  3436  3550 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.105  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7ff7276ea8
,09-23 09:56:44.105  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-23 09:56:44.105  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-23 09:56:44.105  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-23 09:56:44.105  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-23 09:56:44.105  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-23 09:56:44.105  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-23 09:56:44.105  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
09-23 09:56:44.105  3436  3550 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-23 09:56:44.115  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-23 09:56:44.115  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-23 09:56:44.115  3436  3550 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-23 09:56:44.115  3436  3436 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.115  3436  3550 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:56:44.115  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-23 09:56:44.115  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-23 09:56:44.115  3436  3550 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-23 09:56:44.115  3436  3550 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-23 09:56:44.125  3935  3935 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
,09-23 09:56:44.125  3935  3935 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
,09-23 09:56:44.125  3436  3436 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-23 09:56:44.125  3436  3550 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-23 09:56:44.125  3436  3550 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-23 09:56:44.125  3436  3436 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-23 09:56:44.125  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-23 09:56:44.125  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-23 09:56:44.135  3436  3550 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.135  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-23 09:56:44.135  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,09-23 09:56:44.135  3436  3550 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.135  3436  3436 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:56:44.135  3436  3550 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,09-23 09:56:44.135  3436  3550 D AccessibilityManagerService: onUserStateChangedLocked()
09-23 09:56:44.135  3436  3550 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
,09-23 09:56:44.135  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-23 09:56:44.135  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-23 09:56:44.135  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-23 09:56:44.135  4309  4787 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-23 09:56:44.135  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-23 09:56:44.145  3436  3436 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:56:44.145  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-23 09:56:44.145  3436  3436 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote

```
