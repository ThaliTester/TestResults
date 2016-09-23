#### Test 850469114943827_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-23 09:12:42.444  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:42.624  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:42.804  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:42.984  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:43.104  9237  9237 I FIPS_bssl: FIPS approved mode (1) | 9237 | app_process
09-23 09:12:43.114  9237  9237 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 09:12:43.114  9237  9237 D AndroidRuntime: CheckJNI is OFF
09-23 09:12:43.114  9237  9237 D AndroidRuntime: readGMSProperty: start
09-23 09:12:43.114  9237  9237 D AndroidRuntime: readGMSProperty: already setted!!
09-23 09:12:43.114  9237  9237 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 09:12:43.114  9237  9237 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 09:12:43.114  9237  9237 D AndroidRuntime: readGMSProperty: end
09-23 09:12:43.114  9237  9237 D AndroidRuntime: addProductProperty: start
09-23 09:12:43.134  9237  9237 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 09:12:43.154  9237  9237 I Radio-JNI: register_android_hardware_Radio DONE
09-23 09:12:43.154  9237  9237 E AffinityControl: AffinityControl: registerfunction enter
09-23 09:12:43.164  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:43.164  9237  9237 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-23 09:12:43.194  3421  3485 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-23 09:12:43.194  3421  3485 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 09:12:43.214  3421  3485 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:12:43.214  3421  3485 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:12:43.214  3421  3485 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-23 09:12:43.224  3421  3485 D ActivityManager: mDVFSHelper.acquire()
09-23 09:12:43.234  3421  3485 V WindowManager: addAppToken: AppWindowToken{d0b12e498 token=Token{49b5e7b ActivityRecord{e61d60a u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-23 09:12:43.234  3421  3559 I InjectionManager: Inside getClassLibPath caller 
09-23 09:12:43.244  3421  3559 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:12:43.244  3421  3559 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ee5aeb0 V.E...... R.....ID 0,0-0,0}
09-23 09:12:43.254  3421  3559 W WindowManager: Failed looking up window
09-23 09:12:43.254  3421  3559 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@f253129 does not exist
09-23 09:12:43.254  3421  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 09:12:43.254  3421  3559 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 09:12:43.254  3421  3559 D ISSUE_DEBUG: InputChannelName : 6869cae Starting com.test.thalitest
09-23 09:12:43.254  9246  9246 E Zygote  : v2
09-23 09:12:43.254  9246  9246 I libpersona: KNOX_SDCARD checking this for 10171
09-23 09:12:43.254  9246  9246 I libpersona: KNOX_SDCARD not a persona
09-23 09:12:43.254  9246  9246 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-23 09:12:43.254  9246  9246 E Zygote  : accessInfo : 0
09-23 09:12:43.254  9246  9246 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-23 09:12:43.254  3421  3485 I ActivityManager: Start proc 9246:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-23 09:12:43.254  3421  3485 D InputDispatcher: Focused application set to: xxxx
09-23 09:12:43.264  9237  9237 D AndroidRuntime: Shutting down VM
09-23 09:12:43.264  3421  3855 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-23 09:12:43.284  3006  3006 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-23 09:12:43.294  9246  9246 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 09:12:43.294  9246  9246 D ActivityThread: Added TimaKeyStore provider
09-23 09:12:43.314  6035  6035 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:12:43.324  3421  3978 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
09-23 09:12:43.324  3421  3978 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:12:43.324  3421  3978 D PowerManagerService: mDisplayReady: false
09-23 09:12:43.324  3421  3978 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:12:43.324  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:12:43.324  6035  6035 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:12:43.324  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:12:43.324  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:43.334  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fab243c00
09-23 09:12:43.324  3421  3978 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:12:43.334  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 09:12:43.324  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:43.324  3421  3576 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 09:12:43.334  3421  3483 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421
09-23 09:12:43.334  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:12:43.334  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:12:43.334  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:12:43.334  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:12:43.334  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:43.334  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:43.334  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:12:43.334  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:12:43.344  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:43.334  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:43.334  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:43.334  3421  3562 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:12:43.334  3421  3562 D PowerManagerService: mDisplayReady: true
09-23 09:12:43.334  3421  3562 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:12:43.344  3421  4775 D ActivityManager:  Launching com.test.thalitest, updated priority
09-23 09:12:43.354  3421  4379 V WindowStateAnimator: Finishing drawing window Window{a9f4b16 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 09:12:43.354  4282  4282 V ActivityThread: updateVisibility : ActivityRecord{39aec58 token=android.os.BinderProxy@6f62ca8 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-23 09:12:43.374  3421  3421 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-23 09:12:43.374  3421  3538 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-23 09:12:43.384  3006  3897 D libEGL  : eglTerminate EGLDisplay = 0x7fa5c3ee78
09-23 09:12:43.384  3006  3897 D libEGL  : eglTerminate EGLDisplay = 0x7fa5c3ee78
09-23 09:12:43.394  3421  4385 V WindowStateAnimator: Finishing drawing window Window{9340cd8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-23 09:12:43.394  6035  6035 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:12:43.394  6035  6035 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-23 09:12:43.394  6035  6035 V ActivityThread: updateVisibility : ActivityRecord{73d353f token=android.os.BinderProxy@298ac89 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-23 09:12:43.394  3006  3898 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-23 09:12:43.394  3006  3015 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-23 09:12:43.394  4282  4282 D Launcher: onTrimMemory. Level: 20
09-23 09:12:43.404  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fce295df8
09-23 09:12:43.404  3006  3898 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-23 09:12:43.404  3006  3015 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-23 09:12:43.414  3006  3898 D libEGL  : eglTerminate EGLDisplay = 0x7fa4953e78
09-23 09:12:43.414  3006  3015 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-23 09:12:43.414  3006  4574 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-23 09:12:43.434  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fce295df8
09-23 09:12:43.434  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fce295df8
09-23 09:12:43.444  3151  3706 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-23 09:12:43.474  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421 (0x0)
09-23 09:12:43.484  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3421 (0x0)
09-23 09:12:43.484  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:12:43.484  3421  3421 D PowerManagerService: mDisplayReady: false
09-23 09:12:43.484  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:12:43.484  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:12:43.484  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:12:43.484  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:12:43.484  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:43.484  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:43.484  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fab243c00
09-23 09:12:43.484  3421  3576 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 09:12:43.484  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 09:12:43.484  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:12:43.484  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:12:43.484  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:12:43.484  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:12:43.484  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:43.484  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:43.484  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:12:43.484  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:12:43.484  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:43.484  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:43.484  3421  3562 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:12:43.484  3421  3562 D PowerManagerService: mDisplayReady: true
09-23 09:12:43.484  3421  3562 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:12:43.524  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:43.684  3421  4775 I WindowManager: Screenshot max retries 4 of Token{49b5e7b ActivityRecord{e61d60a u0 com.test.thalitest/.MainActivity t4}} appWin=Window{6869cae u0 d0 Starting com.test.thalitest} drawState=1
09-23 09:12:43.694  3421  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:12:43.694  3421  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:12:43.694  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:12:43.694  3421  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:12:43.694  3421  3559 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 09:12:43.694  3421  3421 I KnoxTimeoutHandler: SD activityfalse
09-23 09:12:43.704  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:43.704  3421  3855 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-23 09:12:43.734  9246  9246 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 09:12:43.734  3421  5945 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 09:12:43.734  3421  4386 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-23 09:12:43.734  9246  9246 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-23 09:12:43.734  3421  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:12:43.744  3421  3559 V WindowStateAnimator: Finishing drawing window Window{6869cae u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-23 09:12:43.744  3421  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:12:43.744  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:12:43.744  3421  3559 D ActivityManager: mDVFSHelper.release()
09-23 09:12:43.744  3421  3559 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b7878f2 u0 com.samsung.android.MtpApplication/.USBConnection t3} time:213322
09-23 09:12:43.744  3421  3421 I KnoxTimeoutHandler: SD activityfalse
09-23 09:12:43.754  9246  9246 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:12:43.754  3421  5945 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-23 09:12:43.754  3421  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:12:43.754  3421  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
09-23 09:12:43.754  9246  9246 I InjectionManager: Inside getClassLibPath caller 
09-23 09:12:43.764  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fce295cd8
09-23 09:12:43.774  9246  9246 D InjectionManager: InjectionManager
09-23 09:12:43.774  9246  9246 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-23 09:12:43.774  9246  9246 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-23 09:12:43.774  9246  9246 I InjectionManager: featureStore :{}
09-23 09:12:43.774  3421  4775 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-23 09:12:43.774  3421  4775 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-23 09:12:43.774  3421  4775 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-23 09:12:43.774  3421  4775 D BatteryService: stay LED for fully charged
09-23 09:12:43.774  3421  3421 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-23 09:12:43.784  3421  3421 I MotionRecognitionService: Plugged
09-23 09:12:43.784  3421  3421 D MotionRecognitionService:   cableConnection= 1
09-23 09:12:43.784  3421  3421 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-23 09:12:43.784  3421  3421 D MotionRecognitionService: skip setTransmitPower. 
09-23 09:12:43.784  3421  3860 D WifiController: ApOrStaEnabledState  msg.what= 155652
09-23 09:12:43.784  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-23 09:12:43.784  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
09-23 09:12:43.784  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
09-23 09:12:43.784  9246  9246 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 09:12:43.794  9246  9246 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-23 09:12:43.794  9246  9246 D RelationGraph: garbageCollect()
09-23 09:12:43.794  5034  5034 D CommonServiceConfiguration: getStringValueSetting
09-23 09:12:43.794  4994  4994 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-23 09:12:43.794  4994  5396 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-23 09:12:43.794  9246  9246 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-23 09:12:43.794  5034  5034 D BatteryMonitor: new battery level: 100
09-23 09:12:43.794  4710  4710 D BatteryController: saveBatteryData : level[100], status[5]
09-23 09:12:43.804  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-23 09:12:43.804  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-23 09:12:43.824  9246  9246 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-23 09:12:43.854  9246  9246 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-23 09:12:43.854  9246  9246 D ResourcesManager: For user 0 new overlays fetched Null
09-23 09:12:43.854  9246  9246 I InjectionManager: Inside getClassLibPath caller 
09-23 09:12:43.864  9246  9246 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-23 09:12:43.884  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:43.914  9246  9246 I cr_LibraryLoader: Time to load native libraries: 33 ms (timestamps 3462-3495)
09-23 09:12:43.914  9246  9246 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 09:12:43.954  3421  3878 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-23 09:12:43.984  9246  9263 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-23 09:12:44.004  9246  9246 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8e75517}
09-23 09:12:44.004  9246  9246 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-23 09:12:44.024  9246  9246 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 09:12:44.054  3421  3878 I MdnieScenarioControlService: mGameModeLauncher : false
09-23 09:12:44.054  3421  3878 I MdnieScenarioControlService: setUIMode
09-23 09:12:44.064  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:44.064  9246  9246 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-23 09:12:44.194  3421  3538 W ActivityManager: Activity pause timeout for ActivityRecord{e61d60a u0 com.test.thalitest/.MainActivity t4}
09-23 09:12:44.244  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:44.284  9246  9246 D libEGL  : eglInitialize EGLDisplay = 0xff99c91c
,09-23 09:12:44.394  3421  3485 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-23 09:12:44.394  3421  3485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-23 09:12:44.424  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:44.494  9246  9246 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-23 09:12:44.514  9246  9246 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-23 09:12:44.524  9246  9246 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-23 09:12:44.554  9246  9246 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-23 09:12:44.614  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:44.624  9246  9246 D Activity: performCreate Call Injection manager
09-23 09:12:44.634  9246  9246 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-23 09:12:44.634  9246  9246 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:12:44.644  9246  9246 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d53ec82 I.E...... R.....ID 0,0-0,0}
09-23 09:12:44.654  9246  9300 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-23 09:12:44.664  3421  3852 W WindowManager: Failed looking up window
09-23 09:12:44.664  3421  3852 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@61e7809 does not exist
09-23 09:12:44.664  3421  3852 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 09:12:44.664  3421  3852 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 09:12:44.664  3421  3852 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 09:12:44.664  3421  3852 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-23 09:12:44.664  3421  3852 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-23 09:12:44.664  3421  3852 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-23 09:12:44.664  3421  4775 D ISSUE_DEBUG: InputChannelName : 3820a0e com.test.thalitest/com.test.thalitest.MainActivity
09-23 09:12:44.664  3421  3483 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-23 09:12:44.664  3421  3483 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:12:44.664  3421  3421 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:12:44.674  3421  3421 I KnoxTimeoutHandler: Shared devices show user statefalse
09-23 09:12:44.674  9246  9246 V ActivityThread: updateVisibility : ActivityRecord{5d24bd0 token=android.os.BinderProxy@89e96ca {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-23 09:12:44.684  9246  9263 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-23 09:12:44.694  3421  5946 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-23 09:12:44.714  9246  9246 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9246
09-23 09:12:44.714  3421  4294 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9246 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 09:12:44.714  3421  3866 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-23 09:12:44.714  3421  3866 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-23 09:12:44.724  3421  3866 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-23 09:12:44.724  3421  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 09:12:44.734  3421  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-23 09:12:44.734  9246  9246 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:12:44.744  3421  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-23 09:12:44.744  3421  3866 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-23 09:12:44.744  3421  3866 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 09:12:44.754  3006  3006 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
09-23 09:12:44.784  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:44.794  9246  9300 D libEGL  : eglInitialize EGLDisplay = 0xdc4ff7c4
09-23 09:12:44.794  9246  9300 I OpenGLRenderer: Initialized EGL, version 1.4
09-23 09:12:44.804  9246  9300 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-23 09:12:44.804  3421  3978 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
09-23 09:12:44.804  3421  3978 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:12:44.804  3421  3978 D PowerManagerService: mDisplayReady: false
09-23 09:12:44.804  3421  3978 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:12:44.804  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:12:44.804  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fab243c00
09-23 09:12:44.804  3421  3978 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:12:44.804  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 09:12:44.804  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:12:44.804  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:44.804  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:44.804  3421  3576 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 09:12:44.804  3421  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 09:12:44.814  3006  3051 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=214394135230)
09-23 09:12:44.804  3421  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-23 09:12:44.834  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:12:44.834  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:12:44.834  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:44.834  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:12:44.834  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:44.834  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:12:44.834  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:12:44.834  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:12:44.834  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:44.834  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:44.834  3421  3562 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:12:44.834  3421  3562 D PowerManagerService: mDisplayReady: true
09-23 09:12:44.834  3421  3562 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:12:44.844  9246  9246 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-23 09:12:44.864  3421  4385 V WindowStateAnimator: Finishing drawing window Window{3820a0e u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-23 09:12:44.864  9246  9246 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-23 09:12:44.874  3421  4387 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
09-23 09:12:44.874  3421  3559 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:12:44.874  3421  3559 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s185ms (total +1s643ms)
09-23 09:12:44.874  3421  3421 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-23 09:12:44.874  3421  3559 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e61d60a u0 com.test.thalitest/.MainActivity t4} time:214455
09-23 09:12:44.874  3421  3559 D ViewRootImpl: #3 mView = null
09-23 09:12:44.874  3006  3017 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
09-23 09:12:44.874  3006  3898 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
09-23 09:12:44.884  3421  3421 I KnoxTimeoutHandler: SD activityfalse
09-23 09:12:44.884  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fce295df8
09-23 09:12:44.884  3421  3980 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421
09-23 09:12:44.884  9246  9304 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 09:12:44.884  9246  9304 D libEGL  : eglInitialize EGLDisplay = 0xd980c3f4
09-23 09:12:44.894  3421  3978 V WindowStateAnimator: Finishing drawing window Window{3820a0e u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-23 09:12:44.894  9246  9246 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@89e96ca time:214476
09-23 09:12:44.904  9246  9304 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-23 09:12:44.954  9246  9246 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9246
09-23 09:12:44.964  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-23 09:12:45.034  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3421 (0x0)
09-23 09:12:45.034  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:12:45.034  3421  3421 D PowerManagerService: mDisplayReady: false
09-23 09:12:45.034  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:12:45.034  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:12:45.034  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:12:45.034  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:12:45.034  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:45.034  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:45.034  3421  3576 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-23 09:12:45.034  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fab243c00
09-23 09:12:45.034  3421  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-23 09:12:45.034  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-23 09:12:45.034  3421  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-23 09:12:45.054  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:12:45.054  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:12:45.054  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:45.054  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:12:45.054  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:45.054  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:12:45.054  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:12:45.054  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:12:45.054  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:12:45.054  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:12:45.054  3421  3562 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:12:45.054  3421  3562 D PowerManagerService: mDisplayReady: true
09-23 09:12:45.054  3421  3562 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-23 09:12:45.144  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:45.184  9246  9246 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 09:12:45.194  4024  4024 D Recents : onTaskStackChanged
,09-23 09:12:45.194  4024  4024 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-23 09:12:45.204  4024  4024 D ResourcesManager: For user 0 new overlays fetched Null
,09-23 09:12:45.284  9246  9311 D jxcore_app_log: JniHelper::setJavaVM(0xf4bf4000), pthread_self() = -653526736
,09-23 09:12:45.284  9246  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 09:12:45.284  9246  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 09:12:45.284  9246  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 09:12:45.284  9246  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 09:12:45.284  9246  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 09:12:45.284  9246  9311 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e647a32 added. We now have 1 listener(s)
,09-23 09:12:45.294  9246  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-23 09:12:45.294  9246  9311 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 09:12:45.294  9246  9311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:12:45.294  9246  9311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 09:12:45.294  9246  9311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8354539 added. We now have 1 listener(s)
09-23 09:12:45.294  9246  9311 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:12:45.294  9246  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:12:45.294  9246  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-23 09:12:45.294  9246  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 09:12:45.294  9246  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 09:12:45.294  9246  9311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 09:12:45.304  9246  9311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:12:45.304  9246  9311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-23 09:12:45.304  9246  9311 D BluetoothAdapter: STATE_ON
,09-23 09:12:45.314  9246  9311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:12:45.314  9246  9311 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:12:45.314  9246  9311 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 09:12:45.314  9246  9311 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:12:45.314  9246  9311 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 09:12:45.314  9246  9246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:12:45.314  9246  9246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:12:45.324  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:45.344  9246  9246 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 09:12:45.504  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:45.654  9246  9312 W jxcore-log: Initializing JXcore engine
09-23 09:12:45.654  9246  9312 W jxcore-log: JXcore engine is ready
,09-23 09:12:45.674  5002  5002 E audit   : type=1400 msg=audit(1474614765.674:262): avc:  denied  { ioctl } for  pid=9312 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1332 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 09:12:45.674  5002  5002 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 09:12:45.674  5002  5002 E audit   : type=1300 msg=audit(1474614765.674:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d8fba3c8 items=0 ppid=3177 pid=9312 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 09:12:45.674  5002  5002 E audit   : type=1327 msg=audit(1474614765.674:262): proctitle="com.test.thalitest"
09-23 09:12:45.674  5002  5002 E audit   : type=1320 msg=audit(1474614765.674:262): 
09-23 09:12:45.674  5002  5002 E audit   : type=1400 msg=audit(1474614765.674:263): avc:  denied  { ioctl } for  pid=9312 comm="Thread-160" path="socket:[10175]" dev="sockfs" ino=10175 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 09:12:45.674  5002  5002 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-23 09:12:45.674  5002  5002 E audit   : type=1300 msg=audit(1474614765.674:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d8fba3c8 items=0 ppid=3177 pid=9312 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-23 09:12:45.674  5002  5002 E audit   : type=1327 msg=audit(1474614765.674:263): proctitle="com.test.thalitest"
09-23 09:12:45.674  5002  5002 E audit   : type=1320 msg=audit(1474614765.674:263): 
,09-23 09:12:45.684  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:45.684  9246  9312 W jxcore-log: Starting JXcore engine
,09-23 09:12:45.714  9246  9312 W jxcore-log: Platform android
09-23 09:12:45.714  9246  9312 W jxcore-log: 
09-23 09:12:45.714  9246  9312 W jxcore-log: Process ARCH arm
09-23 09:12:45.714  9246  9312 W jxcore-log: 
,09-23 09:12:45.784  9246  9312 I jxcore-log: JXcore Cordova bridge is ready!
09-23 09:12:45.784  9246  9312 I jxcore-log: 
09-23 09:12:45.784  9246  9312 W jxcore-log: JXcore engine is started
,09-23 09:12:45.794  9246  9311 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 09:12:45.794  9246  9246 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 09:12:45.864  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:46.044  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:46.224  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:46.244  3421  3905 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-23 09:12:46.404  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:46.584  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:46.704  3421  5945 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-23 09:12:46.764  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:46.944  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:47.124  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:47.304  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:47.484  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:47.664  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:47.844  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:48.024  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:48.204  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:48.384  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:48.564  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:48.744  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:48.924  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:49.104  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:49.284  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:49.464  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:49.644  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:49.764  3421  5945 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-23 09:12:49.824  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:50.004  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:50.004  9246  9312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 09:12:50.004  9246  9312 I jxcore-log: 
,09-23 09:12:50.004  9246  9312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 09:12:50.004  9246  9312 I jxcore-log: 
,09-23 09:12:50.014  9246  9312 D BluetoothAdapter: STATE_ON
,09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:12:50.024  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:12:50.024  9246  9312 D BluetoothAdapter: STATE_ON
,09-23 09:12:50.034  9246  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:12:50.034  9246  9312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 09:12:50.034  9246  9312 I jxcore-log: 
09-23 09:12:50.034  9246  9312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 09:12:50.034  9246  9312 I jxcore-log: 
,09-23 09:12:50.174  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:50.264  9246  9312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:12:50.264  9246  9312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d181164 added. We now have 2 listener(s)
09-23 09:12:50.264  9246  9312 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-23 09:12:50.264  9246  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:12:50.264  9246  9312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:12:50.264  9246  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:12:50.264  9246  9312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe40fcd added. We now have 2 listener(s)
09-23 09:12:50.264  9246  9312 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:12:50.264  9246  9312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:12:50.264  9246  9312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:12:50.274  9246  9312 D BluetoothAdapter: STATE_ON
,09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:12:50.274  9246  9312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:12:50.284  9246  9312 D BluetoothAdapter: STATE_ON
,09-23 09:12:50.284  9246  9312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:12:50.284  9246  9312 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:12:50.284  9246  9312 D ExecuteNativeTests: Running unit tests
09-23 09:12:50.284  9246  9312 D BluetoothAdapter: enable()
,09-23 09:12:50.294  9246  9246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:12:50.294  9246  9312 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 09:12:50.294  9246  9246 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:12:50.304  3421  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{28b12be u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16905b3 5023:com.samsung.android.providers.context/u0a7}
,09-23 09:12:50.304  9246  9312 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-23 09:12:50.314  3421  4110 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-23 09:12:50.314  3421  4110 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-23 09:12:50.314  3421  4110 D WifiService: setWifiEnabled: true pid=9246, uid=10171
,09-23 09:12:50.314  3421  4110 W ActivityManager: Permission Denial: getCurrentUser() from pid=9246, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-23 09:12:50.314  3421  4110 W WifiService: Failed getting userId using ActivityManagerNative
09-23 09:12:50.314  3421  4110 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9246, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-23 09:12:50.314  3421  4110 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-23 09:12:50.314  3421  4110 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-23 09:12:50.314  3421  4110 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-23 09:12:50.314  3421  4110 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-23 09:12:50.314  3421  4110 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 09:12:50.324  3421  4110 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
09-23 09:12:50.324  3421  4110 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-23 09:12:50.324  3421  3860 D WifiStateMachine: setFccChannel: channel = 0
09-23 09:12:50.324  3421  3860 D WifiController: [FCC]setFccChannel() is called !!!
09-23 09:12:50.324  3421  3857 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-23 09:12:50.324  3421  3860 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-23 09:12:50.324  3421  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-23 09:12:50.324  3421  3857 D WifiBigDataLog: init : 
,09-23 09:12:50.324  3421  3857 D WifiStateMachine: setFccChannelNative: channel = 0
,09-23 09:12:50.324  3421  3857 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-23 09:12:50.334  3421  3538 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e10f1f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16905b3 5023:com.samsung.android.providers.context/u0a7}
,09-23 09:12:50.364  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:50.544  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:50.724  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:50.904  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:51.084  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:51.264  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:51.444  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:51.624  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:51.754  3421  5945 D SSRM:n  : SIOP:: AP = 300, PST = 262 (W:6), CP = 221, CUR = -2, LCD = 1
,09-23 09:12:51.804  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:51.984  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:52.164  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:52.344  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:52.524  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:52.704  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:52.884  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:53.064  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:53.244  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:53.294  3421  3581 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-23 09:12:53.304  3421  3581 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 09:12:53.424  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:53.604  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:53.774  3421  4145 E Watchdog: !@Sync 7 [09-23 09:12:53.777]
,09-23 09:12:53.784  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:53.964  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:54.144  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:54.324  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:54.504  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:54.684  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:54.864  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:55.044  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:55.224  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:55.404  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:55.584  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:55.764  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:55.944  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:56.124  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:56.304  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:56.484  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:56.664  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:56.844  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:57.024  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:57.204  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:57.384  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:57.564  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:57.744  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:57.924  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:58.104  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:58.284  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:58.454  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:58.464  3151  3706 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-23 09:12:58.644  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:58.824  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:59.004  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:59.084  3421  5980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-23 09:12:59.174  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:59.364  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:59.534  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:59.724  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:59.894  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:12:59.984  3421  3814 V AlarmManager: Expired Alarm result :8
,09-23 09:13:00.084  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:00.264  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:00.334  9246  9312 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 09:13:00.354  9246  9312 I jxcore-log: *Native tests were executed*
09-23 09:13:00.354  9246  9312 I jxcore-log: 
,09-23 09:13:00.354  9246  9312 I jxcore-log: Total number of executed tests:  1
09-23 09:13:00.354  9246  9312 I jxcore-log: 
09-23 09:13:00.354  9246  9312 I jxcore-log: Number of passed tests:  1
09-23 09:13:00.354  9246  9312 I jxcore-log: 
09-23 09:13:00.354  9246  9312 I jxcore-log: Number of failed tests:  0
09-23 09:13:00.354  9246  9312 I jxcore-log: 
09-23 09:13:00.354  9246  9312 I jxcore-log: Number of ignored tests:  0
09-23 09:13:00.354  9246  9312 I jxcore-log: 
09-23 09:13:00.354  9246  9312 I jxcore-log: Total duration:  2
09-23 09:13:00.354  9246  9312 I jxcore-log: 
09-23 09:13:00.354  9246  9312 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 09:13:00.354  9246  9312 I jxcore-log: 
,09-23 09:13:00.354  9246  9312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 09:13:00.354  9246  9312 I jxcore-log: 
09-23 09:13:00.354  9246  9312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 09:13:00.354  9246  9312 I jxcore-log: 
09-23 09:13:00.384  9246  9246 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-23 09:13:00.434  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:00.614  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:00.674  3421  3814 V AlarmManager: Expired Alarm result :4
,09-23 09:13:00.674  3421  3814 V AlarmManager: Send whitelist package alarm :PendingIntent{d21667: PendingIntentRecord{1cfe344 com.samsung.android.app.aodservice broadcastIntent}}
,09-23 09:13:00.674  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-23 09:13:00.674  3950  3950 D KeyguardUpdateMonitor: handleTimeUpdate
,09-23 09:13:00.694  3950  3950 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-23 09:13:00.754  3950  3950 D DateView: received broadcast android.intent.action.TIME_TICK
,09-23 09:13:00.784  4741  4741 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-23 09:13:00.784  4741  4741 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-23 09:13:00.794  4710  4710 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,09-23 09:13:00.794  4710  4710 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-23 09:13:00.794  3421  4387 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-23 09:13:00.794  3421  4387 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-23 09:13:00.794  3421  4387 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-23 09:13:00.794  3421  4387 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-23 09:13:00.794  3166  3166 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-23 09:13:00.794  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:00.794  3421  4387 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-23 09:13:00.794  3421  4387 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-23 09:13:00.794  3421  4387 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-23 09:13:00.794  4710  4710 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@e0e548d, service=Device Physical Context Monitor
09-23 09:13:00.794  4710  4710 I AlpmModeManager: startAlpmMode : state  = BLANK
,09-23 09:13:00.804  4710  4710 D DefaultClockView: Window showed. Time views updating
09-23 09:13:00.804  3421  3980 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,09-23 09:13:00.804  3421  3980 I libsuspend: !@autosuspend_wakeup_count_disable
,09-23 09:13:00.804  3421  3980 D PowerManagerService: mDisplayReady: false
09-23 09:13:00.804  3421  3980 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:13:00.804  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:13:00.804  4710  4710 D AODUpdatePositionController: updatePosition: direction[6] updatePosition: X[-14] Y[119] NewPositionTimer[56]
09-23 09:13:00.804  3421  3980 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:13:00.804  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fab243c00
09-23 09:13:00.804  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-23 09:13:00.804  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-23 09:13:00.804  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:13:00.804  4710  4710 D DefaultClockView: LocalTime Pattern : HH:mm
09-23 09:13:00.804  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-23 09:13:00.804  4710  4710 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 09:13 time02: null ampm: null
09-23 09:13:00.804  3421  3576 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-23 09:13:00.804  3421  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-23 09:13:00.804  3421  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-23 09:13:00.814  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-23 09:13:00.814  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:13:00.814  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:13:00.814  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:13:00.814  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:13:00.814  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-23 09:13:00.814  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-23 09:13:00.814  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-23 09:13:00.814  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:13:00.814  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:13:00.814  3421  3562 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-23 09:13:00.814  3421  3562 D PowerManagerService: mDisplayReady: true
09-23 09:13:00.814  3421  3562 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 09:13:00.824  4710  4710 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-23 09:13:00.824  4710  4710 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-23 09:13:00.824  4710  4710 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pt., 23 wrz 09:13
09-23 09:13:00.824  4710  4710 I AODService.ClockTimer: startAlarm : TICK
09-23 09:13:00.824  3421  4227 V AlarmManager: Add whitelist package alarm :PendingIntent{4619cca: PendingIntentRecord{1cfe344 com.samsung.android.app.aodservice broadcastIntent}}
,09-23 09:13:00.824  4710  4710 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
09-23 09:13:00.824  4710  4710 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,09-23 09:13:00.834  3421  4110 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-23 09:13:00.834  3421  4110 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-23 09:13:00.834  4710  4710 D DefaultClockView: RootView invalidate()
,09-23 09:13:00.834  3421  4385 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421
,09-23 09:13:00.834  3166  3200 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
09-23 09:13:00.834  3421  3817 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
09-23 09:13:00.834  3421  3816 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 7, 13, 0,
,09-23 09:13:00.834  3421  3816 D SensorHubManager: SendSensorHubData: send data = -63, 14, 7, 13, 0
09-23 09:13:00.834  3166  3201 D Sensorhubs: sendContextData: -63, 14, 7, 13, 0
,09-23 09:13:00.844  3421  3816 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-23 09:13:00.844  3421  3816 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-23 09:13:00.844  3421  3816 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,09-23 09:13:00.844  3421  3816 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
09-23 09:13:00.844  3421  3816 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
09-23 09:13:00.844  3421  3819 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-23 09:13:00.844  4710  4710 I AODService: onSContextChanged: AODScreenShown state is already true
,09-23 09:13:00.864  9315  9315 I FIPS_bssl: FIPS approved mode (1) | 9315 | app_process
,09-23 09:13:00.864  9315  9315 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 09:13:00.864  9315  9315 D AndroidRuntime: CheckJNI is OFF
,09-23 09:13:00.864  9315  9315 D AndroidRuntime: readGMSProperty: start
09-23 09:13:00.864  9315  9315 D AndroidRuntime: readGMSProperty: already setted!!
09-23 09:13:00.864  9315  9315 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-23 09:13:00.864  9315  9315 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-23 09:13:00.864  9315  9315 D AndroidRuntime: readGMSProperty: end
09-23 09:13:00.864  9315  9315 D AndroidRuntime: addProductProperty: start
,09-23 09:13:00.884  9315  9315 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 09:13:00.904  9315  9315 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 09:13:00.904  9315  9315 E AffinityControl: AffinityControl: registerfunction enter
,09-23 09:13:00.914  9315  9315 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 09:13:00.924  3421  4903 D PackageManager: START PACKAGE DELETE: observer{160529979}
09-23 09:13:00.924  3421  4903 D PackageManager: pkg{<packageName>}
09-23 09:13:00.924  3421  4903 D PackageManager: user{0}
09-23 09:13:00.924  3421  4903 D PackageManager: caller{2000}
09-23 09:13:00.924  3421  4903 D PackageManager: flags{2}
,09-23 09:13:00.924  3421  4903 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-23 09:13:00.924  3421  4903 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-23 09:13:00.924  3421  4903 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-23 09:13:00.924  3421  4903 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-23 09:13:00.924  3421  4903 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-23 09:13:00.924  3421  3581 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-23 09:13:00.924  3421  3581 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-23 09:13:00.924  3421  3581 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-23 09:13:00.924  3421  3581 D ApplicationPolicy: getApplicationUninstallationEnabled
09-23 09:13:00.924  3421  3581 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-23 09:13:00.924  3421  3581 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-23 09:13:00.924  3421  3581 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-23 09:13:00.924  3421  3581 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
09-23 09:13:00.924  3421  3538 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-23 09:13:00.924  3421  3538 I ActivityManager: Killing 9246:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-23 09:13:00.924  3421  3581 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-23 09:13:00.924  3421  3581 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-23 09:13:00.924  3421  3538 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-23 09:13:00.934  3421  3538 D ActivityManager: mDVFSHelper.acquire()
,09-23 09:13:00.944  3421  3581 D AASAinstall: there is not AASApackages.xml file
,09-23 09:13:00.944  9324  9324 E Zygote  : v2
09-23 09:13:00.944  9324  9324 I libpersona: KNOX_SDCARD checking this for 10171
09-23 09:13:00.944  9324  9324 I libpersona: KNOX_SDCARD not a persona
09-23 09:13:00.944  9324  9324 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-23 09:13:00.944  9324  9324 E Zygote  : accessInfo : 0
09-23 09:13:00.944  9324  9324 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-23 09:13:00.944  3421  3538 I ActivityManager: Start proc 9324:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
,09-23 09:13:00.954  3421  3538 I ActivityManager:   Force finishing activity ActivityRecord{e61d60a u0 com.test.thalitest/.MainActivity t4}
09-23 09:13:00.954  3421  3538 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-23 09:13:00.954  9324  9324 D TimaKeyStoreProvider: TimaSignature is unavailable
09-23 09:13:00.954  9324  9324 D ActivityThread: Added TimaKeyStore provider
,09-23 09:13:00.974  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:00.984  3421  3421 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3421 (0x0)
09-23 09:13:00.984  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable
09-23 09:13:00.984  3421  3421 D PowerManagerService: mDisplayReady: false
09-23 09:13:00.984  3421  3421 I libsuspend: !@autosuspend_wakeup_count_disable done
09-23 09:13:00.984  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:13:00.984  3421  3421 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-23 09:13:00.984  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:13:00.984  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:13:00.984  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:13:00.984  3421  3576 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-23 09:13:00.984  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fab243c00
09-23 09:13:00.984  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-23 09:13:00.984  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:13:00.984  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:13:00.984  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:13:00.984  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:13:00.984  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable
09-23 09:13:00.984  3421  3562 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-23 09:13:00.984  3421  3562 I libsuspend: !@autosuspend_wakeup_count_enable done
09-23 09:13:00.984  3421  3562 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-23 09:13:00.984  3421  3562 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-23 09:13:00.984  3421  3562 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-23 09:13:00.984  3421  3562 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-23 09:13:00.984  3421  3562 D PowerManagerService: mDisplayReady: true
09-23 09:13:00.984  3421  3562 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-23 09:13:01.004  3421  4227 D GraphicsStats: Buffer count: 5
,09-23 09:13:01.004  3421  3978 I WindowState: WIN DEATH: Window{3820a0e u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-23 09:13:01.004  3421  4597 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@e3cf0ed)
,09-23 09:13:01.004  3421  3866 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 09:13:01.004  3421  3866 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 09:13:01.004  3421  3866 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-23 09:13:01.004  3006  3017 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
09-23 09:13:01.004  3006  4574 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
09-23 09:13:01.014  3006  3015 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-23 09:13:01.154  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:01.214  3421  3581 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-23 09:13:01.244  3421  3431 I art     : Background sticky concurrent mark sweep GC freed 198370(12MB) AllocSpace objects, 93(2000KB) LOS objects, 25% free, 42MB/56MB, paused 3.754ms total 110.565ms
,09-23 09:13:01.284  3421  3581 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-23 09:13:01.284  3421  3559 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-23 09:13:01.284  3421  3559 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-23 09:13:01.284  3421  3559 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-23 09:13:01.284  3421  3559 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-23 09:13:01.284  3421  3559 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-23 09:13:01.284  3421  3559 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 09:13:01.284  3421  3559 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:13:01.284  3421  3559 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-23 09:13:01.284  3421  3559 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 09:13:01.284  3421  3559 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 09:13:01.284  3421  3559 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-23 09:13:01.284  3421  3559 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5a8fb22 V.E...... R.....ID 0,0-0,0}
,09-23 09:13:01.284  3421  3559 W WindowManager: Failed looking up window
09-23 09:13:01.284  3421  3559 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@3c379b3 does not exist
09-23 09:13:01.284  3421  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 09:13:01.284  3421  3559 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 09:13:01.284  3421  3559 D ISSUE_DEBUG: InputChannelName : cc18b70 Starting com.test.thalitest
,09-23 09:13:01.284  3421  3559 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,09-23 09:13:01.284  3421  3559 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-23 09:13:01.294  3164  3164 W keystore: ENTER clear_uid from uid 1000 for 10171
,09-23 09:13:01.294  3421  3581 I art     : Starting a blocking GC Explicit
,09-23 09:13:01.304  3006  3006 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-23 09:13:01.334  4282  4282 D Launcher: onRestart, Launcher: 156665925
,09-23 09:13:01.334  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:01.364  3421  4597 V WindowStateAnimator: Finishing drawing window Window{9340cd8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-23 09:13:01.364  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fce295cd8
,09-23 09:13:01.464  3421  3581 I art     : Explicit concurrent mark sweep GC freed 109298(7MB) AllocSpace objects, 6(1912KB) LOS objects, 32% free, 33MB/49MB, paused 1.490ms total 163.820ms
,09-23 09:13:01.504  3421  3581 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-23 09:13:01.504  3421  3581 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-23 09:13:01.504  3421  3581 D AASAinstall: there is not AASApackages.xml file
,09-23 09:13:01.504  3421  3581 D PackageManager: result of delete: 1{160529979}
,09-23 09:13:01.504  3421  3581 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-23 09:13:01.504  3421  3581 D PackageManager: userId{-1}
09-23 09:13:01.504  3421  3581 D PackageManager: andCode{true}
,09-23 09:13:01.504  9315  9315 I art     : System.exit called, status: 0
09-23 09:13:01.504  9315  9315 I AndroidRuntime: VM exiting with result code 0.
,09-23 09:13:01.514  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:01.624  3421  3538 I WindowManager: Screenshot max retries 4 of Token{4516b43 ActivityRecord{b7878f2 u0 com.samsung.android.MtpApplication/.USBConnection t3}} appWin=Window{9340cd8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
,09-23 09:13:01.624  3421  3421 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-23 09:13:01.644  3421  3980 I ActivityManager: Killing 7364:com.android.calendar/u0a137 (adj 15): DHA:empty #33
,09-23 09:13:01.654  4282  4282 D Launcher: onStart, Launcher: 156665925
09-23 09:13:01.654  4282  4282 D Launcher.HomeView: onStart
,09-23 09:13:01.664  4282  4282 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-23 09:13:01.664  4282  4282 V ActivityThread: updateVisibility : ActivityRecord{39aec58 token=android.os.BinderProxy@6f62ca8 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-23 09:13:01.664  4282  4282 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-23 09:13:01.664  4282  4282 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-23 09:13:01.664  4282  4282 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
09-23 09:13:01.664  3421  3538 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
09-23 09:13:01.664  3421  3581 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
09-23 09:13:01.664  3421  3581 I ActivityManager: Killing 9324:com.test.thalitest/u0a171 (adj 9): stop com.test.thalitest cause pkg removed
,09-23 09:13:01.664  3421  3581 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-23 09:13:01.674  4282  4282 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-23 09:13:01.674  4282  4282 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-23 09:13:01.674  4282  4282 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-23 09:13:01.674  4282  4282 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-23 09:13:01.674  4282  4282 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-23 09:13:01.674  4282  4282 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-23 09:13:01.674  3421  3581 I ActivityManager:   Force finishing activity ActivityRecord{e61d60a u0 com.test.thalitest/.MainActivity t4 f}
09-23 09:13:01.674  3421  3581 W ActivityManager: Duplicate finish request for ActivityRecord{e61d60a u0 com.test.thalitest/.MainActivity t4 f}
,09-23 09:13:01.684  3006  3006 I SurfaceFlinger: id=21 createSurf (1440x2560),1 flag=4, MauncherAct
,09-23 09:13:01.694  3421  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-23 09:13:01.694  8766  9341 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-23 09:13:01.704  8766  9341 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-23 09:13:01.704  4282  4573 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-23 09:13:01.704  8766  9341 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-23 09:13:01.724  3421  4379 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-23 09:13:01.724  3421  4379 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-23 09:13:01.724  3421  3421 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-23 09:13:01.734  3421  3421 I KnoxTimeoutHandler: Shared devices show user statefalse
09-23 09:13:01.734  3421  3421 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0

```
